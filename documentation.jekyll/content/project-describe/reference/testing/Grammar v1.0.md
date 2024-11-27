---
layout: page
title: Testing - Grammar 1.0
permalink: /language/reference/testing/test-files-grammar-v10/
exclude: true
---
<br>
_Describe Official (v1.0)_

<span style="font-style: italic;">```Grammar version 1.0 has to pass all the tests for Grammar versions 0.6, 0.7, 0.8 and 0.9```</span><br>

<span style="color:green">Group A - basic functionality</span><br>
<span style="color:blue">```A_control.ds```</span> - Some very simple list with nothing special - as a baseline<br>
<span style="color:blue">```A_inner_commas1.ds```</span> - Some simple list with text containing commas<br>
<span style="color:blue">```A_inner_commas2.ds```</span> - Some simple list with text containing commas on potentially more problematic places<br>
<span style="color:blue">```A_inner_commas3.ds```</span> - Some simple list with text containing commas on potentially even more problematic places<br>
<span style="color:blue">```A_producers1.ds```</span> - Some simple list with text containing producers<br>
<span style="color:blue">```A_producers2.ds```</span> - Some simple list with text containing producers on potentially more problematic places<br>
<span style="color:blue">```A_producers3.ds```</span> - Some simple list with text containing producers on potentially even more problematic places<br>
<span style="color:blue">```A_semicolons1.ds```</span> - Some simple list with text containing semi-colons<br>
<span style="color:blue">```A_semicolons2.ds```</span> - Some simple list with text containing semi-colons on potentially more problematic places<br>
<span style="color:blue">```A_semicolons3.ds```</span> - Some simple list with text containing semi-colons on potentially even more problematic places<br>
<span style="color:blue">```A_tilde.ds```</span> - Some simple list with tilde inversions<br>


<span style="color:green">Group B - how parser handles white-spaces after separators, producers and terminators</span><br>
<span style="color:blue">```B_exotic_spaces.ds```</span> - A list testing various exotic white-spaces<br>
<span style="color:blue">```B_spaces.ds```</span> -  A list testing single and double space characters<br>
<span style="color:blue">```B_tabs.ds```</span> - A list testing tabs.<br>


<span style="color:green">Group C - how parser handles comments after separators, producers and terminators</span><br>
<span style="color:blue">```C_block_comment.ds```</span> - List with block comments and spaces after separators, producers and terminators.<br>
<span style="color:blue">```C_comments_and_spaces.ds```</span> - List with line comments and spaces after separators, producers and terminators.<br>
<span style="color:blue">```C_line_comment.ds```</span> - List with single line comments and spaces after separators, producers and terminators.<br>
<span style="color:blue">```C_multiple_block_comments.ds```</span> - List with more complex mix of block comments.<br>
<span style="color:blue">```C_multiple_line_comments.ds```</span> - List with more complex mix of line comments.<br>
<span style="color:blue">```C_multiple_mixed_comments.ds```</span> - List with more complex mix of mixed comments.<br>


<span style="color:green">Group D - inline doubled symbols</span><br>
<span style="color:blue">```D_commas.ds```</span> - List with inline separators - `,,`<br>
<span style="color:blue">```D_producers.ds```</span> - List with inline producers - `->>`<br>
<span style="color:blue">```D_semicolons.ds```</span> - List with inline terminators - `;;`<br>


<span style="color:green">Group E - escaped inline doubled symbols</span><br>
<span style="color:blue">```E_escaped_double_commas.ds```</span> - List with escaped inline separators - `\,,`.<br>
<span style="color:blue">```E_escaped_double_producers.ds```</span> - List with escaped inline producers - `\->>`.<br>
<span style="color:blue">```E_escaped_double_semicolons.ds```</span> - List with escaped inline terminators - `\;;`.<br>

<br>
### Links
[Back](/language/reference/testing)