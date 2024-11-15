The idea behind the "dot notation" scheme is to use namespaces to form complex dot "." separated ids. Instead of writing long ids though, we can use the namespace directive to set the namespace for the current file, and it will then be added as prefix to every id that starts with a dot. This is so, because if we have a namespaced id, we need the ability to tell if it is a child namespace we are referring to and needs to be added to the current namespace - so we prefix it with a dot, like `<.cars.rnode>`, or if it is a full path of its own `<cars.rnode>` e.g. 

Tag ids without a dot are called local ids, and can be referenced only in that particular file. What happens behind the scenes is that the transpiler creates a random namespace for each file being parsed, and that local namespace is appended to that id. This is done in order to avoid collisions in different files.   
  
Looking at the example 3 files below, we can observe that:  
* it is customary to name folders after namespaces,  
* it is customary that each folder contains one root source file, that is prefixed with dot '.' symbol,  
* root files often contain one root element, which can be tagged with an id like `rnode`, which stands for "root node"  
* namespace directive is used to add to id's:  
  
Example (file-path: `Public\.public.ds`):  
![dot notation 1](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/dba53511-0602-4e95-9f04-ca105a7a6903)

file-path: `Public\Culture\.culture.ds`:  
![dot notation 3](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/37f56df0-73c5-4c36-af26-ed149b4a5019)

file-path: `Public\Science\.science.ds`:  
![dot notation 2](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/6b5235a1-4c50-468f-b463-c14bfbf67479)  
  

### Links
[[Next|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-tildes]]  
[[Prev|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-directives]]  
