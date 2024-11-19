---
layout: page
title: String Array - Multiple Unfolds - Multiple Xml documents
permalink: /language/how-to-compile/api/example3/
exclude: true
---
<br>This example shows how to parse multiple Describe source files in strings to multiple Unfolds and then translate the unfolds to XML documents.<br><br>

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
List<string> sources = sourceArray.ToList();
List<DescribeUnfold> unfolds;
bool result = compiler.ParseStrings(sources, out unfolds);
```
<br>

### 5. Translate
Construct a translator of a desired type and translate the populated DescribeUnfold structure.
If result is not ```null``` then the translation process was successful, so save the resulted string to file.

```
XmlBasicTranslator translator = 
	new XmlBasicTranslator(
		ConsoleLog,
		ConsoleLogError,
		ConsoleLogParseInfo);

if(unfolds != null && unfolds.Count > 0)
{
	for(int i = 0; i < unfolds.Count; i++)
	{
		string? result = translator.TranslateUnfold(unfolds[i]);
		if (result != null)
		{
			// Construct the file path with the index
            		string filePath = @$"C:\result\path\output{i + 1}.xml";
            		File.WriteAllText(filePath, result);
		}
	}
}
```
<br>

<br>
### Links
[Folder - Unfold - Html Page](/language/how-to-compile/api/example1/)<br>
[File - Unfold - Json document](/language/how-to-compile/api/example2/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents (with filenames)](/language/how-to-compile/api/example4/)<br>
[String - Abstract Syntax Tree](/language/how-to-compile/api/example5/)<br>
[Back](/language/how-to-compile/api/)