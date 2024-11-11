### recrypt-folder

```DescribeCompilerCLI recrypt-folder "C:\parse\path\input\input.denc" "C:\result\path\input\input-changed-password.denc"```<br>
```password="qwerty123" auto```<br>

_recrypt-folder ENCRYPTED_PATH PLAIN_PATH password=PASSWORD
[ auto ][ theme=&lt;verb&gt; ]_

The recrypt-folder command is used to change the password of many encrypted describe source files in a folder - '.denc'. First we specify the command, followed by the source folder to be recrypted and the output folder path. Any arguments after these are optional. (Input and Output paths cannot be the same)

* <span style="color:blue">**_password_**</span><br>
The  password that will be used to recrypt the file.

* <span style="color:blue">**_auto_**</span><br>
The auto flag specifies that the tool is being invoked from a script or a tool. Essentially it removes stuff like changing console colors and prompts like ```Press any key to exit.```, as those can break or complicate automated scripts and tools.

* <span style="color:blue">**_theme_**</span><br>
The CLI Transpiler now supports different color themes, via this argument. Expected values are: ```DBLUE```, ```LBLUE```, ```GREEN```, ```PASTEL```, ```EARTH```, ```CONTRAST```, ```DEFAULT```, ```VIOLET``` and ```CYAN```. You can see those themes demonstrated [[here | https://github.com/viktorchernev/DescribeCompiler/wiki/output-themes]].  


## Links
[[Back | https://github.com/viktorchernev/DescribeCompiler/wiki/CliCompiler-how-to]]