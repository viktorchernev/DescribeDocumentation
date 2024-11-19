---
layout: page
title: Describe Compilation - API
permalink: /language/how-to-compile/api/
exclude: true
---
<br>The Describe Compiler API is a software library, containing the de-facto compiler for the Describe Markup Language, as well as some translators for different target languages. It is a .Net dll that targets .Net 8.0 and is licensed under the [AGPL v3](https://www.gnu.org/licenses/agpl-3.0) public license.

## Examples
The Describe Compiler is very straight-forward to implement. You can just look at some of those examples and adapt one for your needs, or you can continue reading about the overview below. Below is a list of few chosen examples:  

[Folder - Unfold - Html Page](/language/how-to-compile/api/example1/)<br>
[File - Unfold - Json document](/language/how-to-compile/api/example2/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents](/language/how-to-compile/api/example3/)<br>
[String Array - Multiple Unfolds - Multiple Xml documents (with filenames)](/language/how-to-compile/api/example4/)<br>
[String - Abstract Syntax Tree](/language/how-to-compile/api/example5/)<br><br>


## Оverview

### 1. Add a reference
You can either download the [Visual Studio project](https://github.com/viktorchernev/DescribeCompiler/tree/master/DescribeTranspiler) or the compiled dll file from the last release from [here](https://github.com/viktorchernev/DescribeCompiler/releases/), and reference it in your .Net project.<br><br>

### 2. Classes
Typically, a person would create an instance of the ```DescribeCompiler``` class, set it up, and use some of its methods to parse Describe source code, producing either an Unfold table or an Abstract Syntax Tree. Then, he/she would create an instance of a Translator class, set it up, and use it to translate the Unfold table or Abstract Syntax Tree to some desired output. Alternatively, he/she might use this Unfold or Abstract Syntax Tree classes in a C# project, directly.

```
namespace DescribeTranspiler
    DescribeCompiler

namespace DescribeTranspiler.Translators

    HtmlPageTranslator : DescribeUnfoldTranslator
    HtmlBasicTranslator : DescribeUnfoldTranslator
    JsonBasicTranslator : DescribeUnfoldTranslator
    JsonListiaryTranslator : DescribeUnfoldTranslator
    XmlBasicTranslator : DescribeUnfoldTranslator
    SqlFileFillTranslator : DescribeUnfoldTranslator
```
<br>

### 3. DescribeCompiler Log Handlers
The actual Describe Compiler is a class ```DescribeCompiler``` in the ```DescribeTranspiler``` namespace. The ```DescribeCompiler``` takes ```Action<string>``` log handlers to log data, so the first thing we probably want to do is to create one or a few log-handler methods, or we will not be able to see any output from our compiler. After that, we create the ```DescribeCompiler``` class and pass the handlers in the constructor (we can also set the handlers later).

```
DescribeCompiler

    // Add your method for logging info here
    public Action<string> LogInfo;

    // Add your method for logging errors here
    public Action<string> LogError;

    // Add your method for logging text here
    public Action<string> LogText;

    // Add your method for logging parser data here
    public Action<string> LogParserInfo;
```
<br>

### 4. DescribeCompiler Settings
Next, we set up some settings of the compiler, if needed.

```
DescribeCompiler

    // Weather to parse only .ds files, or all the files in a directory.
    public bool PARSE_DS_ONLY = true;

    // Weather to parse files in all sub-directories or only in the top directory.
    public bool PARSE_TOP_DIRECTORY_ONLY = false;

    // Weather to stop if there is an error in source code, or skip the file and continue parsing.
    public bool STOP_ON_ERROR = false;

    // The logging verbosity level
    public LogVerbosity Verbosity { get; set; }

    // Gets or sets current language to be used during parsing
    public DescribeVersionName LanguageName { get; set; }

    // Gets or sets current language to be used during parsing
    public DescribeVersionNumber LanguageVersion { get; set; }
```
<br>

### 5. Compilation
After all this is done, we are ready to compile Describe source code.
We have a bunch of options to choose from here, both in terms of input and output.
As for the input, we can parse a single file, or we can parse a folder full of source files - that will, of-course, combine together in a large list. We can provide the input as a file path - ```FileInfo``` / folder path - ```DirectoryInfo``` , or we might provide it in a ```string``` / ```List<string>``` / ```List<SourceCode>``` format - ```SourceCode``` being a simple ```struct``` representing a source code string with a file name.
As for the output, we can choose from an Unfold and an AST output. We also have the option to output a ```List<DescribeUnfold>```, given that we are parsing a multi-string / multi-file input, which is the same as bulk-parsing single source code files.

```
DescribeCompiler

    // Translate a folder of Describe source files to an Unfold
    public bool ParseFolder(DirectoryInfo dirInfo, ref DescribeUnfold unfold)

    // Translate a folder of Describe source files to a list of Unfolds
    public bool ParseFolder(DirectoryInfo dirInfo, out List<DescribeUnfold> unfolds)

    // Translate a folder of Describe source files to a list of AstScriptureNode
    public bool ParseFolder(DirectoryInfo dirInfo, out List<AstScriptureNode> roots)
 
    // Parse multiple Describe source code strings to an Unfold
    public bool ParseStrings(List<SourceCode> sourceCodes, ref DescribeUnfold unfold)

    // Parse multiple Describe source code strings to an Unfold
    public bool ParseStrings(List<string> sourceCodes, ref DescribeUnfold unfold)

    // Parse multiple Describe source code strings to multiple Unfolds.
    // This is basically the same as running ParseString multiple times.
    public bool ParseStrings(List<SourceCode> sourceCodes, out List<DescribeUnfold> unfolds)

    // Parse multiple Describe source code strings to multiple Unfolds.
    // This is basically the same as running ParseString multiple times.
    public bool ParseStrings(List<string> sourceCodes, out List<DescribeUnfold> unfolds)

    // Parse multiple Describe source code strings to multiple Unfolds.
    // This is basically the same as running ParseString multiple times.
    public bool ParseStrings(List<SourceCode> sourceCodes, out List<AstScriptureNode> roots)

    // Parse multiple Describe source code strings to multiple Unfolds.
    // This is basically the same as running ParseString multiple times.
    public bool ParseStrings(List<string> sourceCodes, out List<AstScriptureNode> roots)

    // Parse a Describe source file to an Unfold
    public bool ParseFile(FileInfo fileInfo, ref DescribeUnfold unfold)
	   
    // Parse a Describe source file to an AST
    public bool ParseFile(FileInfo fileInfo, out AstScriptureNode? root)

    // Parse a Describe source code string to an Unfold
    public bool ParseString(string source, string filename, ref DescribeUnfold unfold)

    // Parse a Describe source code string to an AST
    public bool ParseString(string source, string filename, out AstScriptureNode? rootNode)
```
<br>


### 6. Properties
The Properties of the DescribeCompiler hold valuable data about the parsing operation that you can retrieve.<br><br>

```
DescribeCompiler

    // Get Compiler log
    public string Log { get; set; }
	
    // Info

    // Get the name of the Compiler that is currently being used
    public static string CompilerName { get; }

    // Get the version of the Compiler that is currently being used
    public static string CompilerVersion { get; }

    // Get the name of the grammar that is currently loaded
	//in the compiler and will be used for parsing
    public string GrammarName { get; }

    // Get the version of the grammar that is currently loaded 
	//in the compiler and will be used for parsing
    public string GrammarVersion { get; }

    // Get the name with version of the grammar that is currently loaded 
	//in the compiler and will be used for parsing
    public string GrammarFullName { get; }


    // Statistics

    // Get wether the current Transpiler is initialized.
    public bool IsInitialized { get; }

    // Get wether the current Transpiler has been used.
    public bool IsUsed { get; }

    // Gets the number of parsed files in the current operation
    public int FileCount { get; }

    // Gets the number of folders parsed in the current operation
    public int FolderCount { get; }

    // Gets the number of files successfully parsed in the current operation
    public int ParsedFileCount { get; }

    // Gets the number of files failed to parse in the current operation
    public int FailedFileCount { get; }

    // Gets the number of characters red in the current operation
    public int CharacterCount { get; }

    // Gets the number of produced tokens in the current operation
    public int TokenCount { get; }

    // Gets the number of parsed reductions in the current operation
    public int ReductionCount { get; }

    // Gets the number of exceptions thrown in the current operation
    public int ErrorCount { get; }
```
<br>

### 7. The DescribeUnfold
The ```DescribeUnfold``` is a kind of a data table, represented by that class - it holds the data from the parsed Describe source code, without the specifics like code position, comments or white-spaces between items. It is more compact then a full Abstract Syntax Tree, and easier to work with, but it is not suitable for working with Describe code - like highlighting or code editing.

```
namespace DescribeParser.Unfold

// Represents the data structure for containing unfolded data, with links and decorators.
public class DescribeUnfold

    // Gets or sets the parse job object for the Unfold.
    // This class is used in the parsing process and does not need to be accessed directly.
    public IDescribeParseJob ParseJob { get; set; }

    //file stats

    // Gets or sets the list of all files.
    public List<string> AllFiles { get; set; }

    // Gets or sets the list of files that have been parsed successfully.
    public List<string> ParsedFiles { get; set; }

    // Gets or sets the list of files that have been parsed unsuccessfully.
    public List<string> FailedFiles { get; set; }

    //main data
    
    // Gets or sets the list of primary production IDs.
    public List<string> PrimaryProductions { get; set; }

    // Gets or sets the dictionary of productions (head item ID - body items ID's).
    public Dictionary<string, List<string>> Productions { get; set; }

    // Gets or sets the dictionary of translations (item ID - item Text).
    public Dictionary<string, string> Translations { get; set; }

    // Gets or sets the dictionary of links (item ID - links for that item).
    public Dictionary<string, List<DescribeLink>> Links { get; set; }

    // Gets or sets the dictionary of decorators (item ID - decorators for that item).
    public Dictionary<string, List<DescribeDecorator>> Decorators { get; set; }


    //main data place inside files
    
	// Gets or sets the item/file dictionary (item ID - filenames for that item).
    public Dictionary<string, List<string>> ItemidFile { get; set; }

    // Gets or sets the production/file dictionary (item ID - filenames for that production).
    public Dictionary<string, List<string>> ProdidFile { get; set; }


// Represents a link structure containing URL, title, and letter information.
public struct DescribeLink

    // Gets or sets the URL of the link.
    public string Url { get; set; }

    // Gets or sets the optional title of the link.
    public string? Title { get; set; }

    // Gets or sets the optional letter associated with the link.
    public string? Letter { get; set; }


// Represents a decorator structure containing name, value, and category information.
public struct DescribeDecorator

    // Gets or sets the name of the decorator.
    public string Name { get; set; }

    // Gets or sets the optional value of the decorator.
    public string? Value { get; set; }

    // Gets or sets the optional category of the decorator.
    public string? Category { get; set; }
```
<br>

### 8. The Abstract Syntax Tree
The Ast (Abstract Syntax Tree) on the other hand is a way to represent a Describe source code file by capturing all its aspects in a syntax tree. It is good for tasks related to code manipulation, but is poor in terms of data extraction. It is significantly more complex then the Unfold. Classes in the tree, also called Nodes are created by a factory class - ```AstFactory```. I will not provide a map of the classes here, as working with Describe code is a large topic on its own, but I will say that it is relatively straight-forward and we will cover it in the future.<br>

<br>
### Links
[Describe Compilation](/language/how-to-compile/)<br> 
[Use the CLI version](/language/how-to-compile/cli/)<br>
[Use the AWS version](/language/how-to-compile/aws/)<br>
[Back](/language/)
