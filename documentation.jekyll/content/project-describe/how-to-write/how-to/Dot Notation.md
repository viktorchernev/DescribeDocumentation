---
layout: page
title: Describe - Dot Notation
permalink: /language/how-to-write-dot-notation/
exclude: true
---
<br>The idea behind the "dot notation" scheme is to use namespaces to form complex dot "." separated ids. Instead of writing long ids though, we can use the namespace directive to set the namespace for the current file, and it will then be added as prefix to every id that starts with a dot. This is so, because if we have a namespaced id, we need the ability to tell if it is a child namespace we are referring to and needs to be added to the current namespace - so we prefix it with a dot, like `<.cars.rnode>`, or if it is a full path of its own `<cars.rnode>` e.g. 

Tag ids without a dot are called local ids, and can be referenced only in that particular file. What happens behind the scenes is that the transpiler creates a random namespace for each file being parsed, and that local namespace is appended to that id. This is done in order to avoid collisions in different files.   
  
Looking at the example 3 files below, we can observe that:  
* it is customary to name folders after namespaces,  
* it is customary that each folder contains one root source file, that is prefixed with dot '.' symbol,  
* root files often contain one root element, which can be tagged with an id like `rnode`, which stands for "root node"  
* namespace directive is used to add to id's:
<br><br>

<span style="color:blue">_Example (file-path: ```Public\@public.ds```):_</span>
```
directives ->
	namespace <treeofall.public>;


PUBLIC <rnode> ->

	culture <.culture.rnode>,
	science <.science.rnode>;
```

<span style="color:blue">_file-path: ```Public\Culture\@culture.ds```:_</span>
```
directives ->
	namespace <treeofall.public.culture>;


culture <rnode>->

	arts <gux>,
	recreation,
	cuisine;
```

<span style="color:blue">_file-path: ```Public\Science\@science.ds```:_</span>
```
directives ->
	namespace <treeofall.public.science>;


science <rnode> ->

	math <eqS>,
	informatics,
	physics <SDr>;
```

<br>
### Links
[Next](/language/how-to-write-file-names/)<br>
[Prev](/language/how-to-write-directives/)
