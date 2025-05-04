========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String[] -> Unfold[]' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
Preprocessed source code - 127 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 127 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
Preprocessed source code - 134 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_CURL|'{') T(DATA|'fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_CURL|'} ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(DATA|'fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 134 characters, into 24 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
Preprocessed source code - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 150 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
Preprocessed source code - 159 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_SQUARE|'[') T(DATA|'fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(RIGHT_SQUARE|']') T(LEFT_SQUARE|'[ ') T(DATA|'fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_SQUARE|'[') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 159 characters, into 25 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
Preprocessed source code - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 117 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
Preprocessed source code - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 121 characters, into 22 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
Preprocessed source code - 124 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<<someid2>> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 124 characters, into 17 tokens.
Those were translated to an AST.
All Files: 7, Succeeded: 7, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

