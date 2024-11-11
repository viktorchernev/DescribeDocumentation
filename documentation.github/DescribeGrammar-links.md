Links in describe are enclosed in square brackets. A link consists of an URL, or an URL and a title that follows the URL, with a pipe "|" symbol between the title and the URL, or an URL and a title that follows the URL and a letter that follows the title, with a pipe "|" symbol as a delimiter. However, for now the title and letter are largely being ignored in the pre-existing inbuilt translators  

One entry can have zero, one or more links, and each of those links must be enclosed in square brackets of its own. All the links need to follow one another though (aka link-train) - we cannot have links decorators then more links, as this breaks the grammar rules. This is mostly done for the sake of grammar simplicity, but also in favor of writing cleaner, more robust Describe code.  

It is advisable to use URLs that start with a protocol name - "http://" or "https://".  
Some examples follow:

Simple links:  
![simple links](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/cb92d9c4-a96a-46fd-b887-c17ebdbfe1ea)
  
Titled links:  
![titled links](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/33e964aa-e816-4ed4-b187-de3996a4152a)
  
Multiple links:  
![multiple links](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/08c512d3-75f5-443b-b872-c9cafb3ba999)

***
_Interesting fact - In the early stages of the D#scribe language development it was possible write two or more links in the same square brackets, divided by a comma, but this functionality has been scraped as an unnecessary complication._  
  
### Links
[[Next|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-decorators]]  
[[Prev|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-comments]]  