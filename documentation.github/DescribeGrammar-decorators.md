Decorators are basically some text enclosed in curly brackets - ```{``` and ```}```. Decorators are used to add different kinds of data to items - whether it is additional text or an instruction to change the color or the style of the item or even more <!--or add a particular icon image-->. Decorators can either be simple ones, consisting of just a key, or complex ones, consisting of a key and a value, delimited by a pipe symbol ```|```. 
(Decorators can even be ternary ones consisting of a name, key and value, again delimited by a pipe symbol, although those have not been implemented yet).

A list of decorators and instructions for their use follows. However, in the Describe language grammar, a decorator is just some text in curly brackets. What a particular decorator will do is implemented per translator, and if users are developing their own translators, they are free to implement their own decorators.

* <span style="color:blue">**_empty_** ```{empty}```</span><br>
The empty entry decorator is a simple decorator used to create empty entries. Those empty entries essentially act as new lines in lists. This decorator cannot be applied on an item that is a head of a production.

* <span style="color:blue">**_comment_** ```{comment}```</span><br>
The comment decorator is a simple decorator used to make an entry green and italicized.

* <span style="color:blue">**_nlcomment_** ```{nlcomment}```</span><br>
The nlcomment decorator is the same as the comment decorator, but adds an empty entry before the decorated entry, if the decorated entry is not the first in the list.

* <span style="color:blue">**_color_** ```{color|VALUE}```</span><br>
The color decorator is a complex one, and is used for setting the fore-color of the text of the item it is applied to. VALUE is any CSS compatible color - either in the hex notation #1234AA or a named color like limegreen.

* <span style="color:blue">**_bgcolor_** ```{bgcolor|VALUE}```</span><br>
The bgcolor decorator is a complex one, and is used for setting the back-color of the text of the item it is applied to. VALUE is any CSS compatible color - either in the hex notation #1234AA or a named color like limegreen.

* <span style="color:blue">**_bold_** ```{bold}```</span><br>
The bold decorator is a simple decorator used to make an entry bold.

* <span style="color:blue">**_italic_** ```{italic}```</span><br>
The italic decorator is a simple decorator used to make an entry italicized.

* <span style="color:blue">**_underline_** ```{underline}```</span><br>
The underline decorator is a simple decorator used to make an entry underlined.

* <span style="color:blue">**_striked_** ```{striked}```</span><br>
The striked decorator is a simple decorator used to add the strike-through CSS effect to an entry.

* <span style="color:blue">**_sensitive_** ```{sensitive}```</span><br>
Entries can be marked as sensitive and productions can as well. When marked as such, nothing happens until we use the cmd switch `censor`. 
If we do, marked entries are obscured with '?' instead. That is, if the translator supports the feature. Our inbuilt HTML translators do.

* <span style="color:blue">**_secret_** ```{secret}```</span><br>
Entries can be marked as secret and productions can as well. When marked as such, nothing happens until we use the cmd switch `censor`. 
If we do, marked entries are replaced with random number of black squares. That is, if the translator supports the feature. Our inbuilt HTML translators do.

* <span style="color:blue">**_hidden_** ```{hidden}```</span><br>
Entries can be marked as hidden and productions can as well. When marked as such, nothing happens until we use the cmd switch `censor`. 
If we do, marked entries are replaced with random gibberish text. That is, if the translator supports the feature. Our inbuilt HTML translators do.

<!--
* <span style="color:blue">**_style_** ```{style|VALUE}```</span><br>
The style decorator is a complex decorator used with HTML translators to provide CSS for an entry. Value is a valid CSS string that goes in the style attribute of some item like ```<li>``` or ```<span>```.

* <span style="color:blue">**_custom_** ```{custom|NAME}```</span><br>
The custom decorator is a way to add a user defined decorator. How this is handled depends on the translator implementing it.

* <span style="color:blue">**_custom_** ```{custom|NAME|VALUE}```</span><br>
The custom decorator is a way to add a user defined decorator with a value. How this is handled depends on the translator implementing it.
-->

***
Using decorators:  
![decorators 1](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/c047a39e-0c64-4b43-8b00-fd5ff117336c)  

Using decorators (added comments):  
![decorators 2](https://github.com/viktorchernev/DescribeCompiler/assets/72315339/90c5a867-0e16-4dfb-a9f4-84b4ced92909)  

  
### Links
[[Next|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-tags]]  
[[Prev|https://github.com/viktorchernev/DescribeCompiler/wiki/DescribeGrammar-links]]  
