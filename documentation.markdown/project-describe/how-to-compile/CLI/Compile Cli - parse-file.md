---
layout: page
title: Describe Compilation - CLI - parse-file
permalink: /language/how-to-compile/cli/parse-file/
exclude: true
---
<br>
```DescribeCompilerCLI parse-file "C:\parse\path\input.ds" "C:\result\path\output.json"```<br>
```input-password="qwertyi" output-password="qwertyo" log-password="qwertyl"```<br>
```language-version=1.0 translator=JSON verbosity=low beautify=true logfile="C:\parse\path\log.txt"```<br>
```censor auto theme=DBLUE```<br>

_parse-file PARSE_PATH RESULT_PATH
[ input-password=INPUT_PASSWORD ][ output-password=OUTPUT_PASSWORD ][ log-password=LOG_PASSWORD ]
[ language-version=&lt;verb&gt; | lang-ver=&lt;verb&gt; ][ translator=(TARGET_LANGUAGE|TRANSLATOR_NAME) ]
[ beautify=&lt;verb&gt; ][ verbosity=&lt;verb&gt; | log-verbosity=&lt;verb&gt; ][ logfile=LOG_PATH | log-file=LOG_PATH ][ theme=&lt;verb&gt; ][ censor ][ auto ]_

<br>
The parse-file command is used to parse a single file. First we specify the command - ```parse-file```, followed by the path of the source file to be parsed and the output file path. Any arguments after these are optional. If the output file path we have specified is a path to an existing file, that file will be overwritten.<br><br>


* <span style="color:blue">**_input-password_**</span><br>
The Describe Transpiler Cli v1.0 now supports working with encrypted files. The ```input-password``` argument is used to provide a password that will be used to decrypt an encrypted source file ('.denc') before trying to parse it (Which will fail if the password is incorrect or if the file has been encrypted with a different tool that uses incompatible encryption algorithm/implementation).

* <span style="color:blue">**_output-password_**</span><br>
The Describe Transpiler Cli v1.0 now supports working with encrypted files. The ```output-password``` is used to provide a password that will be used to encrypt the output file (the transpilation result).

* <span style="color:blue">**_log-password_**</span><br>
The Describe Transpiler Cli v1.0 now supports working with encrypted files. The ```log-password``` is used to provide a password that will be used to encrypt the log file, as to prevent leaking secret information in the logs, in cases where working with encrypted data and utilizing log files.

* <span style="color:blue">**_language-version_**</span><br>
Can also be written as ```lang-ver```. The ```language-version``` specifies what Describe version to be used as a default. However, if the file to be parsed contains a ```language-version``` directive, this argument will be overwritten in favor of the directive. Expected values are - ```0.6``` or the shorthand version  - ```06```, ```0.7``` or the shorthand version - ```07```, ```0.8``` or the shorthand version - ```08```, ```0.9``` or the shorthand version - ```09```, ```1.0``` or the shorthand version - ```10```, ```1.1``` or the shorthand version - ```11```. If not specified, the default is Describe v1.0.

* <span style="color:blue">**_translator_**</span><br>
Either the desired output language or the name of the translator to be used. The logic here is simple - each language has a default inbuilt translator for it, and that translator will be used if only the desired output language is specified. Expected values are: for languages - ```JSON```, ```HTML```, ```XML```, ```SQL```; for translator names - ```HTML_PLAIN```, ```HTML_PAGE```, ```XML_PLAIN```, ```SQL_FILEFILL```, ```JSON_BASIC```, ```JSON_LISTIARY```. If not specified, the default is ```HTML_PAGE```.

* <span style="color:blue">**_beautify_**</span><br>
Whether the output should be beautified/formatted with new lines and indentation. The logic behind this is that if you are going to manually work with the transpiled output, you would probably want it in an appropriate format, but if not, the extra whitespace is undesirable as it only bulks up the data. This is supported on per-translator basis, although most translators support this. Expected values are: ```true``` and ```false```. Default is false.

* <span style="color:blue">**_verbosity_**</span><br>
The log verbosity of the CLI app. Same as ```log-verbosity```. ```l``` or ```low``` for low verbosity, ```m``` or ```medium``` for medium verbosity or ```h``` or ```high``` for high verbosity. Low is default.

* <span style="color:blue">**_logfile_**</span><br>
Specifies path of directory or file to output logs to. If not specified, logs will be outputted only to the console, which is the default. If the specified path is a path to an existing file, that file will be overwritten.

* <span style="color:blue">**_censor_**</span><br>
The censor flag provides a way to cover up some sensitive data. For example, I might have a personal list that is absolutely fine for my personal use. However, if I need to share it publicly, I might want to edit out some of my private or sensitive information. The censor flag is a convenient way to do just that. The way it works is that users use the ```{sensitive}```, ```{secret}``` and ```{hidden}``` decorators in their describe source code, and when they need to get a censored output, they use the ```censor``` flag. ```{sensitive}``` entries will have every character that is not a whitespace replaced with a question mark. ```{secret}``` and ```{hidden}``` will completely hide the data - ```{secret}``` will produce a random number of black squares and ```{hidden}``` will produce some random-length gibberish text. This is implemented per translator, and not every translator might support this argument. Currently it is supported only in the inbuilt HTML translators.

* <span style="color:blue">**_auto_**</span><br>
The auto flag specifies that the tool is being invoked from a script or a tool. Essentially, it removes stuff like changing console colors and prompts like ```Press any key to exit.```, as those can break or complicate automated scripts and tools.

* <span style="color:blue">**_theme_**</span><br>
The CLI Transpiler now supports different color themes, via this argument. Expected values are: ```DBLUE```, ```LBLUE```, ```GREEN```, ```PASTEL```, ```EARTH```, ```CONTRAST```, ```DEFAULT```, ```VIOLET``` and ```CYAN```. You can see those themes demonstrated [here](https://github.com/viktorchernev/DescribeCompiler/wiki/output-themes).  

<br>
### Links
[help](/language/how-to-compile/cli/help/)<br>
[parse-folder](/language/how-to-compile/cli/parse-folder/)<br>
[encrypt-file](/language/how-to-compile/cli/encrypt-file/)<br>
[decrypt-file](/language/how-to-compile/cli/decrypt-file/)<br>
[recrypt-file](/language/how-to-compile/cli/recrypt-file/)<br>
[encrypt-folder](/language/how-to-compile/cli/encrypt-folder/)<br>
[decrypt-folder](/language/how-to-compile/cli/decrypt-folder/)<br>
[recrypt-folder](/language/how-to-compile/cli/recrypt-folder/)<br>
[Back](/language/how-to-compile/cli/)