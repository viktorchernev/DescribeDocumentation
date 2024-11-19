---
layout: page
title: String - Abstract Syntax Tree
permalink: /language/how-to-compile/api/example5/
exclude: true
---
<br>This example shows how to parse Describe source code from a string to an Abstract Syntax Tree.<br><br>

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
The Describe compiler will produce an AstScriptureNode.

```
AstScriptureNode? rootNode;
bool result = compiler.ParseString(source, fileName, out rootNode);
```
<br>

<br>
### Links
[Folder - Unfold - Html Page](/language/how-to-compile/api/example1/)<br>
[File - Unfold - Json document](/language/how-to-compile/api/example2/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents](/language/how-to-compile/api/example3/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents (with filenames)](/language/how-to-compile/api/example4/)<br>
[Back](/language/how-to-compile/api/)