---
layout: page
title: Testing - Grammar 0.7
permalink: /language/reference/testing/test-files-grammar-v07/
exclude: true
---
<br>
_Describe Tags (v0.7)_

<span style="font-style: italic;">```Those tests are mostly the same as the tests for Describe version 0.6, but with tags. Grammar version 0.7 parsers have to pass all the tests for Grammar version 0.6 before passing the following:```</span>


<span style="color:green">Group A - basic functionality</span><br>
<span style="color:blue">```A_basic1.ds```</span> - Some very simple list, with tags<br>
<span style="color:blue">```A_basicP.ds```</span> - Some very simple list, with tags<br>
<span style="color:blue">```A_basic2.ds```</span> - Some very simple list with 1 entry, with tags<br>
<span style="color:blue">```A_basic3.ds```</span> - Some very simple list with 1 entry on the same line (in-lined production), with tags<br>
<span style="color:blue">```A_basic4.ds```</span>  - Some very simple list ending with a new line character, with tags<br>
<span style="color:blue">```A_twoRoots.ds```</span>  - Two very simple lists, with tags<br>


<span style="color:green">Group B - testing how comments work</span><br>
<span style="color:blue">```B_comments1.ds```</span> - Some very simple list with a line comment ("//"), with tags<br> 
<span style="color:blue">```B_comments2.ds```</span> - Some very simple list with a line comment ("//") and a commented out entry - delimited comment (/* ... */), with tags<br>
<span style="color:blue">```B_comments3.ds```</span> - Some very simple list with a line comment ("//") and a commented out logic - multiple delimited comments (/* ... */), with tags<br>
<span style="color:blue">```B_comments4.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on a new line, with tags.<br>
<span style="color:blue">```B_comments5.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on the same line, with tags.<br>


<span style="color:green">Group C - the idea here is to test empty productions (without entries)</span><br>
<span style="color:blue">```C_empty1.ds```</span> - Simple empty production, with tags.<br>
<span style="color:blue">```C_empty2.ds```</span> - Simple empty production, no spaces, with tags.<br>
<span style="color:blue">```C_empty3.ds```</span> - Simple empty production, with spaces, with tags.<br>
<span style="color:blue">```C_empty4.ds```</span> - Simple empty production, with spaces and new lines, with tags.<br>


<span style="color:green">Group D - double characters - testing if characters that are a start of a multi-character terminal are correctly handled. Escaped double characters - testing escape sequences</span><br>
<span style="color:blue">```D_double_characters1.ds```</span> - Some very simple list containing a hyphen "-", as it is a start character of a producer "->", with tags<br> 
<span style="color:blue">```D_double_characters2.ds```</span> - Some very simple list containing a forward slash "/", as it is a start character of a comment "//" or "\/\*", with tags<br> 
<span style="color:blue">```D_double_characters3.ds```</span> - Some very simple list containing a back slash "\", as it is a start character of escape sequences "\,", with tags<br>
<span style="color:blue">```D_escaped_double_characters1.ds```</span> - Testing escape sequence - escaped dash, with tags.<br>
<span style="color:blue">```D_escaped_double_characters2.ds```</span> - Testing escape sequence - escaped forward slash, with tags.<br>
<span style="color:blue">```D_escaped_double_characters3.ds```</span> - Testing escape sequence - escaped backward slash (escape escape), with tags.<br>
<span style="color:blue">```D_cyrillic.ds```</span> - Some very simple list in Cyrillic, with Cyrillic tags.<br>


<span style="color:green">Group E - spaces, escapes and new lines</span><br>
<span style="color:blue">```E_spaces_escapes_N.ds```</span> - Testing a combination of spaces, new lines and escape sequences, with tags. Linux style new lines ("\n").<br>
<span style="color:blue">```E_spaces_escapes_RN.ds```</span> - Testing a combination of spaces, new lines and escape sequences, with tags. Windows style new lines ("\r\n").<br>


<span style="color:green">Group F - productions</span><br>
<span style="color:blue">```F_production_in_production1.ds```</span> - Production containing a child production as first child, with tags.<br>
<span style="color:blue">```F_production_in_production2.ds```</span> - Production containing a child production as last child, with tags.<br>
<span style="color:blue">```F_production_in_production3.ds```</span> - Production containing a child production as middle child, with tags.<br>
<span style="color:blue">```F_production_in_production4.ds```</span> - Production containing 2 child productions as first and second child, with tags.<br>
<span style="color:blue">```F_production_in_production5.ds```</span> - Production containing 2 child productions as last and next to last child, with tags.<br>
<span style="color:blue">```F_production_in_production6.ds```</span> - Production containing a child production containing a child production, with tags.<br>
<span style="color:blue">```F_production_in_production7.ds```</span> - Production containing a child production containing a child production as last, with tags.<br>


<span style="color:green">Group G - long files for benchmarks</span><br>
<span style="color:blue">```G_long50```</span> - A larger list with 50 elements, with tags.<br>
<span style="color:blue">```G_long100```</span> - A larger list with 100 elements, with tags.<br>
<span style="color:blue">```G_long100a```</span> - A larger list with 100 elements, with tags.<br>

<br>
### Links
[Back](/language/reference/testing)