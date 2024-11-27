---
layout: page
title: Testing - Grammar 0.9
permalink: /language/reference/testing/test-files-grammar-v09/
exclude: true
---
<br>
_Describe Decorators (v0.9)_


<span style="font-style: italic;">```Grammar version 0.9 has to pass all the tests for Grammar versions 0.6, 0.7 and 0.8, before passing the following:```</span><br>


<span style="color:green">Group A - basic functionality</span><br>
<span style="color:blue">```A_basic1.ds```</span> - Some very simple list, with tags and links empty decorators<br>
<span style="color:blue">```A_basic2.ds```</span> - Some very simple list with 1 entry, with tags and links and a decorator on multiple lines<br>
<span style="color:blue">```A_basic3.ds```</span> - Some very simple list with 1 entry on the same line (in-lined production), with tags and links and a decorator<br>
<span style="color:blue">```A_basic4.ds```</span>  - Some very simple list ending with a new line character, with tags and links and a decorator<br>
<span style="color:blue">```A_twoRoots.ds```</span> - Two simple lists in one file, with tags, links and decorators.<br>

<span style="color:green">Group B - testing how comments work</span><br>
<span style="color:blue">```B_comments1.ds```</span> - Some very simple list with a line comment ("//"), with tags and links, empty links and erroneously placed decorators<br>
<span style="color:blue">```B_comments2.ds```</span> - Some very simple list with a line comment ("//") and a commented out entry - delimited comment (/* ... */), with tags and links, empty links, multiple empty decorators<br>
<span style="color:blue">```B_comments3.ds```</span> - Some very simple list with a line comment ("//") and a commented out logic - multiple delimited comments (/* ... */), with tags, links and decorators<br>
<span style="color:blue">```B_comments4.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on a new line, with tags, links and decorators (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>
<span style="color:blue">```B_comments5.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on the same line, with tags, links and decorators (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>


<span style="color:green">Group C - other</span><br>
<span style="color:blue">```C_cyrillic.ds```</span> - Some very simple list in Cyrillic, with Cyrillic decorators, with Cyrillic tags and Cyrillic links. This is for testing the pre-processor, as the GOLD Parser can't parse Cyrillic.

<br>
### Links
[Back](/language/reference/testing)