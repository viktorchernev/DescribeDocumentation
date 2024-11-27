---
layout: page
title: Multiple tildes
permalink: /language/reference/versioning/v10/bugs/bug-6/
exclude: true
---
<br>_BUG: Multiple tildes on an item break translation_

<span style="color:red">Having multiple tildes on an item and no other items on that item seems problematic - the output is broken.</span>

```
line 7:122 no viable alternative at input '~ HTTPS Endpoint: Functions can be triggered via HTTP requests, making them suitable for creating microservices. <infoe>;\r\n\r\n\r\n\t'
"C:\Users\Viktor Chernev\Desktop\Lists-Cli\MyResearch\myAwsComputing\AwsLambdaAlternatives.ds" - failed to unfold tree: The child at index 1 of the provided Expression_listContext is not a valid ExpressionContext. (Parameter 'context')
```

<span style="color:blue">We should rework/reimplement the handling of tildes as decorators.</span>

<span style="color:green">This will be done in the next version. For now, tildes are implemented as regular items. However, our test file here contained some faulty logic, with semicolons after each tilde, instead of commas, making this bug faulty.</span>


## Links
[Back](/language/reference/versioning/v10/transpiler10/)