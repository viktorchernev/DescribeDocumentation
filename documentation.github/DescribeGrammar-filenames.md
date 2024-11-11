Like other programming languages, Describe has file extensions associated with different files. Some file prefixes might also be utilized as well.


### Extentions
A list of file extensions related to the Describe language and the Describe compiler follows:

* <span style="color:blue">**_.ds_** ```someFile.ds```</span><br>
```.ds``` or ```.DS```, by convention, is the extention for describe source files. It stands for "Describe Scripture". By default, the compiler will read only files with those extensions, and ignore others. 

* <span style="color:blue">**_.dr_** ```someDraftFile.dr```</span><br>
Also by convention, source files that are not ready to be compiled (aka draft files) are named with the ```.dr``` or ```.DR``` extension, which stands for "Describe dRaft", and are omitted by the compiler.

<!--
* <span style="color:blue">**_.dart_** ```someArtifact.dart```</span><br>
```.dart``` or ```.DART``` stands for "Describe ARTifact". Those are artifact files for the compiler.
-->

* <span style="color:blue">**_.denc_** ```someSecret.denc```</span><br>
```.denc``` or ```.DENC``` stands for "Describe ENCrypted". Those files are Describe source code files that have been encrypted.


### Prefixes

When parsing folders or multiple source files, it’s essential to identify the root entry or entries. Typically, these are the root entries in the root file. But this raises the question: which file is the root one? By convention, the root file is the one that begins with a dot `.` Without following this convention, we risk inconsistent results, potentially ending up with orphaned lists that don’t appear in the output, as the transpiler may incorrectly choose the wrong list for a root one.   

* <span style="color:blue">**_._** ```.someSource.ds```</span><br>
Dot symbol might indicate that the source file is a root one.

<!--
* <span style="color:blue">**_@_** ```@someSource.ds```</span><br>
"At" symbol might indicate that the source file is a root one.
-->

* <span style="color:blue">**_#_** ```#someSource.ds```</span><br>
hash symbol (aka octothorpe) might indicate that source file is encrypted.

### Links
[[Back|https://github.com/viktorchernev/DescribeCompiler/wiki/Grammar-How-To]]  
[[Prev|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-tildes]] 
