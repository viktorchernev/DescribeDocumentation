---
layout: page
title: Remove .Net framework
permalink: /language/reference/versioning/v10/features/feature-3/
exclude: true
---
<br>_FEATURE: Remove support for .Net framework_<br>

Support for Describe Compiler Framework has been discontinued. Using the CLI version instead.<br>
Both Core and Framework versions of the CLI app do the same. At this moment, there is no need to keep both.<br><br>

To surmise, there was a distinct CLI project, named "DescribeCompiler.Cli.Framework" or something similar. It was the same project as the CLI app, but targeted a version of .Net specific for Windows, and had a few specific minor quirks related to manipulation of the console window. However, keeping two similar versions of the same app is cumbersome and unnecessary, so the project has been removed.

<br>
### Links
[Back](/language/reference/versioning/v10/transpiler10/)