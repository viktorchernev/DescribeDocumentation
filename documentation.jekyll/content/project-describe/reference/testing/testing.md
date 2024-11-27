---
layout: page
title: Describe Transpiler - Testing
permalink: /language/reference/testing/
exclude: true
---
<br>We test the different projects and components - parser, compiler, etc. both via unit tests and integration tests. This page goes over some aspects of the integration testing we do. However, this section of the documentation is not complete. For the complete documentation you can directly browse the testing directory on [github](https://github.com/viktorchernev/DescribeDocumentation/tree/main/documentation.testing)
<br><br>


## Files

We have devised (and are devising) describe source code test files (.ds) that aim to test various different scenarios for each version of the Describe grammar, in order to run integration tests. These test files are grouped in folders by categories - `encrypted_files`, `decrypted_files`, `recrypted_files`, `TestFilesFor06`, `TestFilesFor07`, `TestFilesFor08`, `TestFilesFor09`, `TestFilesFor10`, `TestFilesFor11`, `live_Radio`.<br>

The `encrypted_files`, `decrypted_files`, and `recrypted_files` are source code files used to test encryption, decryption, and recryption functionality with the CLI app. These files are identical to those found in the live_Radio folder, which is a test project focused on Bulgarian radio playlists.<br>

All other folders contain test files designed for specific scenarios and features corresponding to different language versions. The goal is to ensure that each parser can successfully handle tests from previous language versions, thereby maintaining backward compatibility.<br>

<!--
## Grammars

Unlike previous versions powered by GOLD parser engine, with ANTLR it has been easier to test a grammar by testing the produced parser directly in C#, so this is what we do. This is due to the lack of good tools, to a significant extent. (There is a useful online test editor for grammars - the [ANTLR Lab](http://lab.antlr.org/), and a dedicated Java-based editorIDE named [ANTLRWorks](https://www.antlr3.org/works/) that I haven't be able to run successfully with ANTLR4 - as it is ANTLR3 based.)<br>


2. We parse those test files using the GOLD parser engine with the specific grammar tables version being tested and make sure that they are all parsed successfully. We are also running all the tests for all the previous versions, as grammars need to be backward compatible. The log output is documented.

3. We parse those test files using the GOLD Builder, making sure they are all parsed successfully. We are also running all the tests for all the previous versions, as grammars need to be backward compatible. The log output is documented.

4. The log outputs from the two different methods are compared, making sure the parsing process produced the same result in all the test cases.
-->

<br>
### Links
[Testing - Grammar v0.6](/language/reference/testing/test-files-grammar-v06)<br>
[Testing - Grammar v0.7](/language/reference/testing/test-files-grammar-v07)<br>
[Testing - Grammar v0.8](/language/reference/testing/test-files-grammar-v08)<br>
[Testing - Grammar v0.9](/language/reference/testing/test-files-grammar-v09)<br>
[Testing - Grammar v1.0](/language/reference/testing/test-files-grammar-v10)<br>
[Testing - Grammar v1.1](/language/reference/testing/test-files-grammar-v11)<br>
[Back](/language/reference)