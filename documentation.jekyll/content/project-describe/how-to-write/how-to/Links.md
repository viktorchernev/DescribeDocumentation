---
layout: page
title: Describe - Links
permalink: /language/how-to-write-links/
exclude: true
---
<br>Links in describe are enclosed in square brackets. A link consists of an URL, or an URL and a title that follows the URL, with a pipe `|` symbol between the title and the URL, or an URL and a title that follows the URL and a letter that follows the title, with a pipe `|` symbol as a delimiter. However, for now the title and letter are largely being ignored in the pre-existing inbuilt translators  

One entry can have zero, one or more links, and each of those links must be enclosed in square brackets of its own. All the links need to follow one another though (aka link-train) - we cannot have links decorators then more links, as this breaks the grammar rules. This is mostly done for the sake of grammar simplicity, but also in favor of writing cleaner, more robust Describe code.  

It is advisable to use URLs that start with a protocol name - `http://` or `https://`.  
Some examples follow:

<br><br>
<span style="color:blue">_Simple links:_</span>
```
famous websites ->

    wikipedia [https://www.wikipedia.org/],
    fandom [https://www.fandom.com/],
    github [https://github.com/];
```

<span style="color:blue">_Titled links:_</span>
```
famous websites ->

    wikipedia [https://www.wikipedia.org/ | Wikipedia],
    fandom [https://www.fandom.com/ | Fandom],
    github [https://github.com/ | Github];
```

<span style="color:blue">_Multiple links:_</span>
```
famous websites ->

    wikipedia [https://www.wikipedia.org/][https://en.wikipedia.org/wiki/Main_Page],
    
	fandom [https://www.fandom.com/]
	[https://www.fandom.com/articles],
    
	github 
	[https://github.com/ | Github]
	[https://github.blog/ | Github blog];
```

<span style="color:green">_Interesting fact - In the early stages of the Describe language development it was possible write two or more links in the same square brackets, divided by a comma, but this functionality has been scraped as an unnecessary complication._</span>

<br>
### Links
[Next](/language/how-to-write-decorators/)<br>
[Prev](/language/how-to-write-comments/)
