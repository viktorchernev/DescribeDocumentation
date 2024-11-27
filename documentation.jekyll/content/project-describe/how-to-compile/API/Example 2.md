---
layout: page
title: File - Unfold - Json document
permalink: /language/how-to-compile/api/example2/
exclude: true
---
<br>This example shows how to parse a folder of Describe source files to an Unfold and then translate the unfold to an HTML page.<br><br>

### 1. Add a reference
You can either download the [Visual Studio project](https://github.com/viktorchernev/DescribeCompiler/tree/master/DescribeTranspiler) or the compiled dll file from the last release from [here](https://github.com/viktorchernev/DescribeCompiler/releases/), and reference it in your .Net project.<br><br>

### 2. Create log handlers
Create handler methods that are used for logging data. This is how we are going to get logs from the parser. In the example below, we are creating methods that will log data to the console in different colors.

```
//log text
private static void ConsoleLog(string text)
{
    Console.WriteLine(text);
}

//log info gray
private static void ConsoleLogInfo(string text)
{
    Console.ForegroundColor = ConsoleColor.DarkGray;
    Console.WriteLine(text);
    Console.ForegroundColor = ConsoleColor.White;
}

//log errors red
private static void ConsoleLogError(string text)
{
    Console.ForegroundColor = ConsoleColor.Red;
    Console.WriteLine(text);
    Console.ForegroundColor = ConsoleColor.White;
}

//log parser data green
private static void ConsoleLogParseInfo(string text)
{
    Console.ForegroundColor = ConsoleColor.Green;
    Console.WriteLine(text);
    Console.ForegroundColor = ConsoleColor.White;
}
```
<br>

### 3. Construct and set the compiler 
The constructor for the compiler takes verbosity and log handlers as optional arguments, so that the user does not need to set them one by one. Some or all of log handlers can be omitted and corresponding output won't be logged.

```
DescribeCompiler.DescribeCompiler compiler =
	new DescribeCompiler.DescribeCompiler(
		LogVerbosity.High,
		Messages.ConsoleLog,
		Messages.ConsoleLogError,
		Messages.ConsoleLogInfo,
		Messages.ConsoleLogParseInfo);

//settings
compiler.LanguageVersion = DescribeVersionNumber.Version10;
```
<br>

### 4. Compile
The Describe compiler will populate a DescribeUnfold structure with data.

```
DescribeUnfold unfold = new DescribeUnfold();
bool result = compiler.ParseFile(new FileInfo(filePath), unfold);
```
<br>

### 5. Translate
Construct a translator of a desired type and translate the populated DescribeUnfold structure.
If result is not ```null``` then the translation process was successful, so save the resulted string to file.

```
JsonBasicTranslator translator = 
	new JsonBasicTranslator(
		ConsoleLog,
		ConsoleLogError,
		ConsoleLogParseInfo);

string? result = translator.TranslateUnfold(unfold);
if (result != null)
{
	File.WriteAllText(@"C:\result\path\output.json", result);
}
```
<br>


<br>
### Links
[Folder - Unfold - Html Page](/language/how-to-compile/api/example1/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents](/language/how-to-compile/api/example3/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents (with filenames)](/language/how-to-compile/api/example4/)<br>
[String - Abstract Syntax Tree](/language/how-to-compile/api/example5/)<br>
[Back](/language/how-to-compile/api/)