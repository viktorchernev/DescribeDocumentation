---
layout: page
title: Powered by ANTLR!
permalink: /language/reference/versioning/v10/features/feature-1/
exclude: true
---
<br>_FEATURE: Powered by ANTLR!_<br>

The Describe Transpiler v1.0 has been partially rewritten in order to integrate ANTLR 4 based parser from scratch.

Problems with using GOLD piled up, and we had to either reverse-engineer the GOLD builder from scratch and hope to fix some bugs with workarounds and stay within the realm of LALR parsing, or switch to a different parser generator. We did thorough assessment and research and stopped on ANTLR 4.13. 

ANTLR 4 is state of the art tool with more than 25 years of development behind it. It supports multiple parsing algorithms, adaptive error recovery strategies, robust grammars. It is stupidly fast for a lightweight language like Describe Markup. It also have a steeper learning curve.

GOLD is good for what it is - an exclusively LALR parser, but it is far from being mature and polished. It is also an abandoned project that receives no updates, and all of the source code is not readily available. It cannot handle non-Latin input out of the box, and has few annoying bugs on its own. The reason I choose it was because I was somewhat familiar with the source code of the tool, and had no insight about the different parser-generator tools available. So, mistakes have been made. 
<br>

<br>
### Links
[Back](/language/reference/versioning/v10/transpiler10/)