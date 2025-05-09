---
layout: page
title: Describe - Tagging
permalink: /language/how-to-write-tagging/
exclude: true
---
<br>
### IDs
Tag Ids are case sensitive, and should contain alphanumeric characters with letters of upper or lower case. It is not advisable to use special characters in ids. Good idea for creating ids is to either use random strings that are 3 to 8 characters long or camel cased / pascal cased descriptive names - just like variable names in many programming languages. It is advisable to use random strings for entries in the same file, and descriptive ids for entries in another files, where the descriptive id is the same as or hints of the file name.<br><br>

### Public and Private entries

Simply put, public entries can be referenced from other files, while private entries can be referenced only inside lists in the current file. A tag id starting with a dot `.` or containing a dot indicates a public item, while a tag id not containing dots indicates a private item.<br><br>

### Addressing schemes 

It wouldn't make a whole lot of sense to have large describe lists in single files, and users often compile many files contained in many folders to one list. The question that arises then, is how to refer to an id in another file in a convenient manner? This is what addressing schemes are for.

The current addressing scheme in Describe is called "dot notation". The idea here is to use namespaces to form complex dot "." separated ids for the public lists. Instead of writing long ids, we use the namespace directive to set the namespace we are in, and that namespace is then added as prefix to every id that that starts with a dot. Look the example in the section on [dot notation](https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-dot-notation).

An older scheme exists, that is deprecated and cannot be used. It was called "slash notation", and it is the idea that we can prefix tag ids with their filename or file-path, using forward slashes. It has number of issues and has been discontinued. <!-- but can be reimplemented in the future if the need arises. -->
<br><br>
### Markers 
 
 Markers are some symbols that are used at the beginning of a tag id to mark the item, thus adding functionality. For example, a tag id to an encrypted entry can start with a hash symbol (aka octothorpe) - ```encrypted item <#someid>```

<br>
### Links
[Next](/language/how-to-write-directives/)<br>
[Prev](/language/how-to-write-tags/)
