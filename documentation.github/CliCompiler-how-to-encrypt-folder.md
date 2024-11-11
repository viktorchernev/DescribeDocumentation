### encrypt-folder

```DescribeCompilerCLI encrypt-folder "C:\parse\path\input\" "C:\result\path\output\"```<br>
```password="qwerty123" auto```<br>

_encrypt-folder PLAIN_PATH ENCRYPTED_PATH password=PASSWORD
[ auto ][ theme=&lt;verb&gt; ]_

The encrypt-folder command is used to encrypt a folder full of Describe source files - '.ds'. First we specify the command, followed by the source folder to be encrypted and the output folder path, that will contain the encrypted files. Any arguments after these are optional. (Input and Output paths cannot be the same)

* <span style="color:blue">**_password_**</span><br>
The  password that will be used to encrypt the files.

* <span style="color:blue">**_auto_**</span><br>
The auto flag specifies that the tool is being invoked from a script or a tool. Essentially it removes stuff like changing console colors and prompts like ```Press any key to exit.```, as those can break or complicate automated scripts and tools.

* <span style="color:blue">**_theme_**</span><br>
The CLI Transpiler now supports different color themes, via this argument. Expected values are: ```DBLUE```, ```LBLUE```, ```GREEN```, ```PASTEL```, ```EARTH```, ```CONTRAST```, ```DEFAULT```, ```VIOLET``` and ```CYAN```. You can see those themes demonstrated [[here | https://github.com/viktorchernev/DescribeCompiler/wiki/output-themes]].  


## Links
[[Back | https://github.com/viktorchernev/DescribeCompiler/wiki/CliCompiler-how-to]]