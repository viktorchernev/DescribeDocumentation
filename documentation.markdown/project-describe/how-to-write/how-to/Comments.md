---
layout: page
title: Describe - Comments
permalink: /language/how-to-write-comments/
exclude: true
---
<br>Comments in describe are much like comments in C++ or C#, or other C type languages - we have single line comments, that start with two slashes `//` and end with a new line, and we also have the delimited type, starting with slash and a star - `/*` and ending with a star and a slash - `*/`. 

Note that, a colon before two forward slashes `://` will escape the comment. This is done because we want to be able to write links in text - `https://abc...` e.g. without the need to escape the forward slashes, which would be annoying. On the other hand, we can escape the colon, if need to have a comment right after a column - `\://`. This feature, however - about the colon before two forward slashes - will only work in Describe language version 1.0 or higher.
<br><br>

<span style="color:blue">_Example:_</span>
```
//our solar system
solar system ->

	rocky planets -> //innermost

		/* 1-st */ Mercury,
		/* 2-nd */ Venus,
		/* 3-rd */ Earth,
		/* 4-th */ Mars;

	gas giants ->

		Jupiter,
		Saturn;

	ice giants -> //outermost

		Uranus,
		Neptune;
```

<!--<span style="color:green">_Note - Nesting of comments is not supported, as in most major programming languages._</span>-->

<br>
### Links
[Next](/language/how-to-write-links/)<br>
[Prev](/language/how-to-write-lists/)