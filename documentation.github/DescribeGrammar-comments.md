Comments in describe are much like comments in C++ or C#, or other C type languages - we have single line comments, that start with two slashes `//` and end with a new line, and we also have the delimited type, starting with slash and a star - `/*` and ending with a star and a slash - `*/`. 

Note that, a colon before two forward slashes `://` will escape the comment. This is done because we want to be able to write links in text - `https://abc...` e.g. without the need to escape the forward slashes, which would be annoying. On the other hand, we can escape the colon, if need to have a comment right after a column - `\://`. This feature, however - about the colon before two forward slashes - will only work in Describe language version 1.0 or higher.
    
Example:  
![comments](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/1e25fb7b-b285-4717-abcd-657d75c8d7a4)

  
### Links
[[Next|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-links]]  
[[Prev|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-lists]]  
 