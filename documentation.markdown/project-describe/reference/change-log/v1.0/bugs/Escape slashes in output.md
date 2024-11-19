---
layout: page
title: Escape slashes in output
permalink: /language/reference/versioning/v10/bugs/bug-2/
exclude: true
---
<br>_BUG: Escape slashes present in output_

<span style="color:red">In outputted HTML, we have escape slashes - `\,`, instead of the coma we were trying to output."</span>

<span style="color:green">There was simply no mechanism implemented to deal with the escape sequence in tokens properly.
I have implemented a method that does that and turns every sequence of white-space characters to a single space.</span>


## Links
[Back](/language/reference/versioning/v10/transpiler10/)