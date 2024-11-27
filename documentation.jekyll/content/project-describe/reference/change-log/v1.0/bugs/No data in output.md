---
layout: page
title: No data in output
permalink: /language/reference/versioning/v10/bugs/bug-7/
exclude: true
---
<br>_BUG: No data in translation output_

<span style="color:red">Result is devoid of the information it should contain. Only empty template is outputted.</span>

```
DescribeTranspiler.CLI parse-file "C:\Users\Viktor Chernev\Desktop\@Ds\MyLife\!MySchemes\mySchemesULOT.txt" "C:\Users\Viktor Chernev\Desktop\testing\!compiled\MySchemes.html" translator=html_page beautify=true verbosity=h logfile="C:\Users\Viktor Chernev\Desktop\testing\!compiled\MySchemes.log" theme="DBLUE"
```

<span style="color:blue">We forgot to set root file for the unfold object's ParseJob. Because of that, the translator could not find which productions were root productions, and since we start translation from the root productions, if we have no root productions, we have no data in the final output, apart from the actual template.</span>

<span style="color:green">First of all, in the transpiler's methods for parsing file or string this has been remediated.<br>
Second, we have added a verification check at ValidateUnfold method, that will throw an exception should RootFile be null again.</span>


## Links
[Back](/language/reference/versioning/v10/transpiler10/)