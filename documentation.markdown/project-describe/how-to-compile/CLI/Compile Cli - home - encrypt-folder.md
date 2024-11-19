---
layout: page
title: Describe Compilation - CLI - encrypt-folder
permalink: /language/how-to-compile/cli/encrypt-folder/
exclude: true
---
<br>The encrypt-folder command is used to encrypt a folder full of Describe source files - '.ds'. First we specify the command, followed by the source folder to be encrypted and the output folder path, that will contain the encrypted files. Any arguments after these are optional. (Input and Output paths cannot be the same)<br><br>

```DescribeCompilerCLI encrypt-folder "C:\parse\path\input\" "C:\result\path\output\"```<br>
```password="qwerty123" auto```<br>

_encrypt-folder PLAIN_PATH ENCRYPTED_PATH password=PASSWORD
[ auto ][ theme=&lt;verb&gt; ]_
<br>

* <span style="color:blue">**_password_**</span><br>
The  password that will be used to encrypt the files.

* <span style="color:blue">**_auto_**</span><br>
The auto flag specifies that the tool is being invoked from a script or a tool. Essentially it removes stuff like changing console colors and prompts like ```Press any key to exit.```, as those can break or complicate automated scripts and tools.

* <span style="color:blue">**_theme_**</span><br>
The CLI Transpiler now supports different color themes, via this argument. Expected values are: ```DBLUE```, ```LBLUE```, ```GREEN```, ```PASTEL```, ```EARTH```, ```CONTRAST```, ```DEFAULT```, ```VIOLET``` and ```CYAN```. You can see those themes demonstrated [here](https://github.com/viktorchernev/DescribeCompiler/wiki/output-themes).  

<br>
### Links
[help](/language/how-to-compile/cli/help/)<br>
[parse-file](/language/how-to-compile/cli/parse-file/)<br>
[parse-folder](/language/how-to-compile/cli/parse-folder/)<br>
[encrypt-file](/language/how-to-compile/cli/encrypt-file/)<br>
[decrypt-file](/language/how-to-compile/cli/decrypt-file/)<br>
[recrypt-file](/language/how-to-compile/cli/recrypt-file/)<br>
[decrypt-folder](/language/how-to-compile/cli/decrypt-folder/)<br>
[recrypt-folder](/language/how-to-compile/cli/recrypt-folder/)<br>
[Back](/language/how-to-compile/cli/)