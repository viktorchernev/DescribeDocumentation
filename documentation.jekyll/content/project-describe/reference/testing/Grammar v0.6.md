---
layout: page
title: Testing - Grammar 0.6
permalink: /language/reference/testing/test-files-grammar-v06/
exclude: true
---
<br>
_Describe Basics (v0.6)_

<span style="color:green">Group A - basic functionality</span><br>
<span style="color:blue">```A_basic1.ds```</span> - Some very simple list<br>
<span style="color:blue">```A_basicP.ds```</span> - Some very simple list<br>
<span style="color:blue">```A_basic2.ds```</span> - Some very simple list with 1 entry<br>
<span style="color:blue">```A_basic3.ds```</span> - Some very simple list with 1 entry on the same line (in-lined production)<br>
<span style="color:blue">```A_basic4.ds```</span>  - Some very simple list ending with a new line character<br>
<span style="color:blue">```A_twoRoots.ds```</span>  - Two very simple lists<br>


<span style="color:green">Group B - testing how comments work</span><br>
<span style="color:blue">```B_comments1.ds```</span> - Some very simple list with a line comment ("//")<br> 
<span style="color:blue">```B_comments2.ds```</span> - Some very simple list with a line comment ("//") and a commented out entry - delimited comment (/* ... */)<br>
<span style="color:blue">```B_comments3.ds```</span> - Some very simple list with a line comment ("//") and a commented out logic - multiple delimited comments (/* ... */)<br>
<span style="color:blue">```B_comments4.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on a new line (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>
<span style="color:blue">```B_comments5.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on the same line (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>


<span style="color:green">Group C - the idea here is to test empty productions (without entries)</span><br>
<span style="color:blue">```C_empty1.ds```</span> - Simple empty production.<br>
<span style="color:blue">```C_empty2.ds```</span> - Simple empty production, no spaces.<br>
<span style="color:blue">```C_empty3.ds```</span> - Simple empty production, with spaces.<br>
<span style="color:blue">```C_empty4.ds```</span> - Simple empty production, with spaces and new lines.<br>


<span style="color:green">Group D - double characters - testing if characters that are a start of a multi-character terminal are correctly handled. Escaped double characters - testing escape sequences</span><br>
<span style="color:blue">```D_double_characters1.ds```</span> - Some very simple list containing a hyphen "-", as it is a start character of a producer "->"<br> 
<span style="color:blue">```D_double_characters2.ds```</span> - Some very simple list containing a forward slash "/", as it is a start character of a comment "//" or "/*"<br> 
<span style="color:blue">```D_double_characters3.ds```</span> - Some very simple list containing a back slash "\", as it is a start character of escape sequences "\,"<br>
<span style="color:blue">```D_escaped_double_characters1.ds```</span> - Testing escape sequence - escaped dash.<br>
<span style="color:blue">```D_escaped_double_characters2.ds```</span> - Testing escape sequence - escaped forward slash.<br>
<span style="color:blue">```D_escaped_double_characters3.ds```</span> - Testing escape sequence - escaped backward slash (escape escape).<br>
<span style="color:blue">```D_cyrillic.ds```</span> - Some very simple list in Cyrillic.<br>


<span style="color:green">Group E - spaces, escapes and new lines</span><br>
<span style="color:blue">```E_spaces_escapes_N.ds```</span> - Testing a combination of spaces, new lines and escape sequences. Linux style new lines ("\n").<br>
<span style="color:blue">```E_spaces_escapes_RN.ds```</span> - Testing a combination of spaces, new lines and escape sequences. Windows style new lines ("\r\n").<br>


<span style="color:green">Group F - productions</span><br>
<span style="color:blue">```F_production_in_production1.ds```</span> - Production containing a child production as first child.<br>
<span style="color:blue">```F_production_in_production2.ds```</span> - Production containing a child production as last child.<br>
<span style="color:blue">```F_production_in_production3.ds```</span> - Production containing a child production as middle child.<br>
<span style="color:blue">```F_production_in_production4.ds```</span> - Production containing 2 child productions as first and second child.<br>
<span style="color:blue">```F_production_in_production5.ds```</span> - Production containing 2 child productions as last and next to last child.<br>
<span style="color:blue">```F_production_in_production6.ds```</span> - Production containing a child production containing a child production.<br>
<span style="color:blue">```F_production_in_production7.ds```</span> - Production containing a child production containing a child production as last.<br>


<span style="color:green">Group G - long files for benchmarks</span><br>
<span style="color:blue">```G_long50```</span> - A larger list with 50 elements.<br>
<span style="color:blue">```G_long100```</span> - A larger list with 100 elements.<br>
<span style="color:blue">```G_long100a```</span> - A larger list with 100 elements.<br>


<br>
### Links
[Back](/language/reference/testing)