---
layout: page
title: Testing - Grammar 0.8
permalink: /language/reference/testing/test-files-grammar-v08/
exclude: true
---
<br>
_Describe Links (v0.8)_

<span style="font-style: italic;">```Grammar version 0.8 has to pass all the tests for Grammar versions 0.6 and 0.7 before passing the following:```</span><br>


<span style="color:green">Group A - basic functionality</span><br>
<span style="color:blue">```A_basic1.ds```</span> - Some very simple list, with tags and links<br>
<span style="color:blue">```A_basic2.ds```</span> - Some very simple list with 1 entry, with tags and links<br>
<span style="color:blue">```A_basic3.ds```</span> - Some very simple list with 1 entry on the same line (in-lined production), with tags and links<br>
<span style="color:blue">```A_basic4.ds```</span>  - Some very simple list ending with a new line character, with tags and links<br>
<span style="color:blue">```A_twoRoots.ds```</span>  - Some very simple list with two root nodes, with tags and links<br>


<span style="color:green">Group B - testing how comments work</span><br>
<span style="color:blue">```B_comments1.ds```</span> - Some very simple list with a line comment ("//"), with tags and links, empty links<br>
<span style="color:blue">```B_comments2.ds```</span> - Some very simple list with a line comment ("//") and a commented out entry - delimited comment (/* ... */), with tags and links, empty links<br>
<span style="color:blue">```B_comments3.ds```</span> - Some very simple list with a line comment ("//") and a commented out logic - multiple delimited comments (/* ... */), with tags and links<br>
<span style="color:blue">```B_comments4.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on a new line, with tags and links (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>
<span style="color:blue">```B_comments5.ds```</span> - Some very simple list with 2 line comments ("//"), ending with a comment on the same line, with tags and links (there is an issue with the GOLD parsed engine that results in a runaway group if source file ends with a comment. We handle it during preprocessing though).<br>


<span style="color:green">Group C - the idea here is to test empty productions (without entries)</span><br>
<span style="color:blue">```C_empty1.ds```</span> - Simple empty production, with tags and a link.<br>
<span style="color:blue">```C_empty2.ds```</span> - Simple empty production, no spaces, with tags and a link.<br>
<span style="color:blue">```C_empty3.ds```</span> - Simple empty production, with spaces and new lines, with tags and 2 links and an empty link.<br>


<span style="color:green">Group D - testing escape sequences</span><br>
<span style="color:blue">```D_escaped_double_characters1.ds```</span> - Testing escape sequence - escaped forward slash, with tags and an escaped square bracket.<br>
<span style="color:blue">```D_cyrillic.ds```</span> - Some very simple list in Cyrillic, with Cyrillic tags and Cyrillic links. This is for testing the pre-processor, as the GOLD Parser can't parse Cyrillic.

<span style="color:green">Group E - spaces, escapes and new lines</span><br>
<span style="color:blue">```E_spaces_escapes_N.ds```</span> - Testing a combination of spaces, new lines and escape sequences, with tags. Linux style new lines ("\n").<br>
<span style="color:blue">```E_spaces_escapes_RN.ds```</span> - Testing a combination of spaces, new lines and escape sequences, with tags. Windows style new lines ("\r\n").<br>

<span style="color:green">Group F - productions</span><br>
<span style="color:blue">```F_production_in_production1.ds```</span> - Production containing a child production as first child.<br>
<span style="color:blue">```F_production_in_production2.ds```</span> - Production containing a child production as last child.<br>
<span style="color:blue">```F_production_in_production3.ds```</span> - Production containing a child production as middle child.<br>
<span style="color:blue">```F_production_in_production4.ds```</span> - Production containing 2 child productions as first and second child.<br>
<span style="color:blue">```F_production_in_production5.ds```</span> - Production containing 2 child productions as last and next to last child.<br>
<span style="color:blue">```F_production_in_production6.ds```</span> - Production containing a child production containing a child production.<br>
<span style="color:blue">```F_production_in_production7.ds```</span> - Production containing a child production containing a child production as last.<br>


<br>
### Links
[Back](/language/reference/testing)