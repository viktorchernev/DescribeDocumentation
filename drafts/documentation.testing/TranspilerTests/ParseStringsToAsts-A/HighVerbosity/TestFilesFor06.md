========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_twoRoots.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_cyrillic.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.E_spaces_escapes_N.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.E_spaces_escapes_RN.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production6.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production7.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long100.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long100a.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long50.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String[] -> Unfold[]' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
Preprocessed source code - 98 characters long

Parsing sequence: T(DATA|'fabric') T(STAR|'*') T(DATA|'s ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool http') T(PROTO_SLASHES|'://') T(DATA|'abc.de fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 98 characters, into 16 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic2.ds"
Preprocessed source code - 35 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\t\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 35 characters, into 6 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic3.ds"
Preprocessed source code - 29 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 29 characters, into 6 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic4.ds"
Preprocessed source code - 97 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 97 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
Preprocessed source code - 98 characters long

Parsing sequence: T(DATA|'fabric') T(STAR|'*') T(DATA|'s ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool http') T(PROTO_SLASHES|'://') T(DATA|'abc.de fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 98 characters, into 16 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_twoRoots.ds"
Preprocessed source code - 114 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'fiber') T(SEPARATOR|',\n    ') T(DATA|'water') T(TERMINATOR|';\n\n') T(DATA|'micronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'vitamins (ABCDEK)') T(SEPARATOR|',\n    ') T(DATA|'minerals (micronutrients)') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 114 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments1.ds"
Preprocessed source code - 111 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 111 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments2.ds"
Preprocessed source code - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 117 characters, into 10 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments3.ds"
Preprocessed source code - 104 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>        ') T(DATA|'wool fabrics') T(SEPARATOR|', ') T(DATA|'cotton fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 104 characters, into 8 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments4.ds"
Preprocessed source code - 130 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 130 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.B_comments5.ds"
Preprocessed source code - 126 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 126 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty1.ds"
Preprocessed source code - 11 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 11 characters, into 5 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty2.ds"
Preprocessed source code - 10 characters long

Parsing sequence: T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 10 characters, into 5 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty3.ds"
Preprocessed source code - 12 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 12 characters, into 5 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.C_empty4.ds"
Preprocessed source code - 16 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\r\n') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 16 characters, into 5 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_cyrillic.ds"
Preprocessed source code - 93 characters long

Parsing sequence: T(DATA|'платове ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'вълнени платове') T(SEPARATOR|',\r\n\t') T(DATA|'памучни платове') T(SEPARATOR|',\r\n\t') T(DATA|'копринени платове') T(SEPARATOR|',\r\n\t') T(DATA|'синтетични платове') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 93 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters1.ds"
Preprocessed source code - 106 characters long

Parsing sequence: T(DATA|'fa ') T(HYPHEN|'-') T(DATA|' br') T(HYPHEN|'-') T(DATA|'ics') T(HYPHEN|'-') T(DATA|' ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(HYPHEN|'-') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(HYPHEN|'-') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(HYPHEN|'-') T(DATA|' silk ') T(HYPHEN|'-') T(DATA|' fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(HYPHEN|'-') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 106 characters, into 25 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters2.ds"
Preprocessed source code - 106 characters long

Parsing sequence: T(DATA|'fa ') T(FORWARD_SLASH|'/ ') T(DATA|'br') T(FORWARD_SLASH|'/') T(DATA|'ics') T(FORWARD_SLASH|'/ ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(FORWARD_SLASH|'/') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(FORWARD_SLASH|'/') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(FORWARD_SLASH|'/ ') T(DATA|'silk ') T(FORWARD_SLASH|'/ ') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(FORWARD_SLASH|'/') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 106 characters, into 24 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_double_characters3.ds"
Preprocessed source code - 105 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE|'\ ') T(DATA|'br') T(ESCAPE|'\') T(DATA|'ics') T(ESCAPE|'\ ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE|'\') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\ ') T(DATA|'silk ') T(ESCAPE|'\ ') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 105 characters, into 23 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters1.ds"
Preprocessed source code - 103 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'> ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 103 characters, into 18 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters2.ds"
Preprocessed source code - 110 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics') T(ESCAPE_LCOMMENT|'\// ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE_SEPARATOR|'\,') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 110 characters, into 22 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters3.ds"
Preprocessed source code - 114 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'br') T(ESCAPE_ESCAPE|'\\') T(DATA|'ics') T(ESCAPE_ESCAPE|'\\ ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_ESCAPE|'\\') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE_ESCAPE|'\\') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'silk ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_ESCAPE|'\\') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 114 characters, into 24 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.E_spaces_escapes_N.ds"
Preprocessed source code - 107 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n\t') T(DATA|'wool   fabrics\t') T(SEPARATOR|',\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles  ') T(SEPARATOR|',\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(SEPARATOR|',\n    ') T(DATA|'syntic \t\tfabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 107 characters, into 17 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.E_spaces_escapes_RN.ds"
Preprocessed source code - 112 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool   fabrics\t') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles  ') T(SEPARATOR|',\r\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'syntic \t\tfabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 112 characters, into 17 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production1.ds"
Preprocessed source code - 82 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 82 characters, into 13 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production2.ds"
Preprocessed source code - 74 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 74 characters, into 14 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production3.ds"
Preprocessed source code - 89 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\r\n\t') T(DATA|'somth else') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 89 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production4.ds"
Preprocessed source code - 152 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water') T(SEPARATOR|',\r\n    ') T(DATA|'salt') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 152 characters, into 24 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production5.ds"
Preprocessed source code - 144 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water') T(SEPARATOR|',\r\n    ') T(DATA|'salt') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 144 characters, into 25 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production6.ds"
Preprocessed source code - 186 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry') T(TERMINATOR|';\r\n\t\t\t\r\n\t\t') T(DATA|'informathics') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water') T(SEPARATOR|',\r\n    ') T(DATA|'salt') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 186 characters, into 29 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production7.ds"
Preprocessed source code - 179 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water') T(SEPARATOR|',\r\n    ') T(DATA|'salt') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t\r\n\t\t') T(DATA|'informathics') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine') T(SEPARATOR|',\r\n\t\t\r\n\t\t') T(DATA|'math ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry') T(TERMINATOR|';') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 179 characters, into 31 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long100.ds"
Preprocessed source code - 4864 characters long

Parsing sequence: T(DATA|'huge list for time benchmark ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'Elephants parade through the jungle') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent castles overlook vast landscapes') T(SEPARATOR|',\r\n\t') T(DATA|'The shimmering ocean reflects the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Enormous mountains pierce the clear sky') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient ruins stand as testaments to history') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic waterfalls cascade down rocky cliffs') T(SEPARATOR|',\r\n\t') T(DATA|'Lush forests teem with diverse wildlife') T(SEPARATOR|',\r\n\t') T(DATA|'Spectacular fireworks light up the night sky') T(SEPARATOR|',\r\n\t') T(DATA|'Grand cathedrals echo with sacred chants') T(SEPARATOR|',\r\n\t') T(DATA|'Endless deserts stretch across barren plains') T(SEPARATOR|',\r\n\t') T(DATA|'Vibrant tulip fields paint the countryside') T(SEPARATOR|',\r\n\t') T(DATA|'Glorious sunsets set the horizon ablaze') T(SEPARATOR|',\r\n\t') T(DATA|'Whimsical fairies dance under moonlight') T(SEPARATOR|',\r\n\t') T(DATA|'Towering skyscrapers reach for the clouds') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil rivers meander through lush valleys') T(SEPARATOR|',\r\n\t') T(DATA|'Quaint cottages nestle in picturesque villages') T(SEPARATOR|',\r\n\t') T(DATA|'Roaring waterfalls plunge into misty abysses') T(SEPARATOR|',\r\n\t') T(DATA|'Snow') T(HYPHEN|'-') T(DATA|'capped mountains glisten in the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Winding cobblestone streets lead to hidden treasures') T(SEPARATOR|',\r\n\t') T(DATA|'Rustling palm trees sway in the tropical breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Crystal') T(HYPHEN|'-') T(DATA|'clear lakes mirror the surrounding landscape') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient temples whisper tales of bygone eras') T(SEPARATOR|',\r\n\t') T(DATA|'Cascading waterfalls create rainbows in the mist') T(SEPARATOR|',\r\n\t') T(DATA|'Mighty glaciers carve their way through rugged terrain') T(SEPARATOR|',\r\n\t') T(DATA|'Twinkling stars illuminate the midnight sky') T(SEPARATOR|',\r\n\t') T(DATA|'Fragrant flower gardens bloom with vibrant colors') T(SEPARATOR|',\r\n\t') T(DATA|'Towering lighthouses guide ships safely to shore') T(SEPARATOR|',\r\n\t') T(DATA|'Rolling hillsides are dotted with grazing sheep') T(SEPARATOR|',\r\n\t') T(DATA|'Bustling marketplaces buzz with activity') T(SEPARATOR|',\r\n\t') T(DATA|'Steep cliffs plunge into the crashing waves below') T(SEPARATOR|',\r\n\t') T(DATA|'Chirping crickets fill the warm summer night') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent palaces stand as symbols of power') T(SEPARATOR|',\r\n\t') T(DATA|'Endless fields of wheat sway in the gentle breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Whistling winds sweep across vast open plains') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic eagles soar high above rugged peaks') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil ponds reflect the surrounding forest') T(SEPARATOR|',\r\n\t') T(DATA|'Golden sand dunes stretch as far as the eye can see') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient castles whisper secrets of the past') T(SEPARATOR|',\r\n\t') T(DATA|'Glistening dewdrops adorn the morning grass') T(SEPARATOR|',\r\n\t') T(DATA|'Mystical forests are home to mythical creatures') T(SEPARATOR|',\r\n\t') T(DATA|'Towering redwoods reach for the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Serene meadows stretch out beneath the sun') T(SEPARATOR|',\r\n\t') T(DATA|'Gigantic icebergs float gracefully in frigid waters') T(SEPARATOR|',\r\n\t') T(DATA|'Quivering aspen leaves rustle in the autumn breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Towering cliffs overlook crashing ocean waves') T(SEPARATOR|',\r\n\t') T(DATA|'Colorful hot air balloons dot the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Gentle waves lap against sandy shores') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient pyramids rise from the desert sands') T(SEPARATOR|',\r\n\t') T(DATA|'Whirling tornadoes carve paths of destruction') T(SEPARATOR|',\r\n\t') T(DATA|'Crumbling ruins hint at ancient civilizations') T(SEPARATOR|',\r\n\t') T(DATA|'Elephants parade through the jungle') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent castles overlook vast landscapes') T(SEPARATOR|',\r\n\t') T(DATA|'The shimmering ocean reflects the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Enormous mountains pierce the clear sky') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient ruins stand as testaments to history') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic waterfalls cascade down rocky cliffs') T(SEPARATOR|',\r\n\t') T(DATA|'Lush forests teem with diverse wildlife') T(SEPARATOR|',\r\n\t') T(DATA|'Spectacular fireworks light up the night sky') T(SEPARATOR|',\r\n\t') T(DATA|'Grand cathedrals echo with sacred chants') T(SEPARATOR|',\r\n\t') T(DATA|'Endless deserts stretch across barren plains') T(SEPARATOR|',\r\n\t') T(DATA|'Vibrant tulip fields paint the countryside') T(SEPARATOR|',\r\n\t') T(DATA|'Glorious sunsets set the horizon ablaze') T(SEPARATOR|',\r\n\t') T(DATA|'Whimsical fairies dance under moonlight') T(SEPARATOR|',\r\n\t') T(DATA|'Towering skyscrapers reach for the clouds') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil rivers meander through lush valleys') T(SEPARATOR|',\r\n\t') T(DATA|'Quaint cottages nestle in picturesque villages') T(SEPARATOR|',\r\n\t') T(DATA|'Roaring waterfalls plunge into misty abysses') T(SEPARATOR|',\r\n\t') T(DATA|'Snow') T(HYPHEN|'-') T(DATA|'capped mountains glisten in the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Winding cobblestone streets lead to hidden treasures') T(SEPARATOR|',\r\n\t') T(DATA|'Rustling palm trees sway in the tropical breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Crystal') T(HYPHEN|'-') T(DATA|'clear lakes mirror the surrounding landscape') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient temples whisper tales of bygone eras') T(SEPARATOR|',\r\n\t') T(DATA|'Cascading waterfalls create rainbows in the mist') T(SEPARATOR|',\r\n\t') T(DATA|'Mighty glaciers carve their way through rugged terrain') T(SEPARATOR|',\r\n\t') T(DATA|'Twinkling stars illuminate the midnight sky') T(SEPARATOR|',\r\n\t') T(DATA|'Fragrant flower gardens bloom with vibrant colors') T(SEPARATOR|',\r\n\t') T(DATA|'Towering lighthouses guide ships safely to shore') T(SEPARATOR|',\r\n\t') T(DATA|'Rolling hillsides are dotted with grazing sheep') T(SEPARATOR|',\r\n\t') T(DATA|'Bustling marketplaces buzz with activity') T(SEPARATOR|',\r\n\t') T(DATA|'Steep cliffs plunge into the crashing waves below') T(SEPARATOR|',\r\n\t') T(DATA|'Chirping crickets fill the warm summer night') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent palaces stand as symbols of power') T(SEPARATOR|',\r\n\t') T(DATA|'Endless fields of wheat sway in the gentle breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Whistling winds sweep across vast open plains') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic eagles soar high above rugged peaks') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil ponds reflect the surrounding forest') T(SEPARATOR|',\r\n\t') T(DATA|'Golden sand dunes stretch as far as the eye can see') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient castles whisper secrets of the past') T(SEPARATOR|',\r\n\t') T(DATA|'Glistening dewdrops adorn the morning grass') T(SEPARATOR|',\r\n\t') T(DATA|'Mystical forests are home to mythical creatures') T(SEPARATOR|',\r\n\t') T(DATA|'Towering redwoods reach for the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Serene meadows stretch out beneath the sun') T(SEPARATOR|',\r\n\t') T(DATA|'Gigantic icebergs float gracefully in frigid waters') T(SEPARATOR|',\r\n\t') T(DATA|'Quivering aspen leaves rustle in the autumn breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Towering cliffs overlook crashing ocean waves') T(SEPARATOR|',\r\n\t') T(DATA|'Colorful hot air balloons dot the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Gentle waves lap against sandy shores') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient pyramids rise from the desert sands') T(SEPARATOR|',\r\n\t') T(DATA|'Whirling tornadoes carve paths of destruction') T(SEPARATOR|',\r\n\t') T(DATA|'Crumbling ruins hint at ancient civilizations ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 4864 characters, into 212 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long100a.ds"
Preprocessed source code - 4864 characters long

Parsing sequence: T(DATA|'huge list for time benchmark ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'Elephants parade through the jungle') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent castles overlook vast landscapes') T(SEPARATOR|',\r\n\t') T(DATA|'The shimmering ocean reflects the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Enormous mountains pierce the clear sky') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient ruins stand as testaments to history') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic waterfalls cascade down rocky cliffs') T(SEPARATOR|',\r\n\t') T(DATA|'Lush forests teem with diverse wildlife') T(SEPARATOR|',\r\n\t') T(DATA|'Spectacular fireworks light up the night sky') T(SEPARATOR|',\r\n\t') T(DATA|'Grand cathedrals echo with sacred chants') T(SEPARATOR|',\r\n\t') T(DATA|'Endless deserts stretch across barren plains') T(SEPARATOR|',\r\n\t') T(DATA|'Vibrant tulip fields paint the countryside') T(SEPARATOR|',\r\n\t') T(DATA|'Glorious sunsets set the horizon ablaze') T(SEPARATOR|',\r\n\t') T(DATA|'Whimsical fairies dance under moonlight') T(SEPARATOR|',\r\n\t') T(DATA|'Towering skyscrapers reach for the clouds') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil rivers meander through lush valleys') T(SEPARATOR|',\r\n\t') T(DATA|'Quaint cottages nestle in picturesque villages') T(SEPARATOR|',\r\n\t') T(DATA|'Roaring waterfalls plunge into misty abysses') T(SEPARATOR|',\r\n\t') T(DATA|'Snow') T(HYPHEN|'-') T(DATA|'capped mountains glisten in the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Winding cobblestone streets lead to hidden treasures') T(SEPARATOR|',\r\n\t') T(DATA|'Rustling palm trees sway in the tropical breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Crystal') T(HYPHEN|'-') T(DATA|'clear lakes mirror the surrounding landscape') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient temples whisper tales of bygone eras') T(SEPARATOR|',\r\n\t') T(DATA|'Cascading waterfalls create rainbows in the mist') T(SEPARATOR|',\r\n\t') T(DATA|'Mighty glaciers carve their way through rugged terrain') T(SEPARATOR|',\r\n\t') T(DATA|'Twinkling stars illuminate the midnight sky') T(SEPARATOR|',\r\n\t') T(DATA|'Fragrant flower gardens bloom with vibrant colors') T(SEPARATOR|',\r\n\t') T(DATA|'Towering lighthouses guide ships safely to shore') T(SEPARATOR|',\r\n\t') T(DATA|'Rolling hillsides are dotted with grazing sheep') T(SEPARATOR|',\r\n\t') T(DATA|'Bustling marketplaces buzz with activity') T(SEPARATOR|',\r\n\t') T(DATA|'Steep cliffs plunge into the crashing waves below') T(SEPARATOR|',\r\n\t') T(DATA|'Chirping crickets fill the warm summer night') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent palaces stand as symbols of power') T(SEPARATOR|',\r\n\t') T(DATA|'Endless fields of wheat sway in the gentle breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Whistling winds sweep across vast open plains') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic eagles soar high above rugged peaks') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil ponds reflect the surrounding forest') T(SEPARATOR|',\r\n\t') T(DATA|'Golden sand dunes stretch as far as the eye can see') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient castles whisper secrets of the past') T(SEPARATOR|',\r\n\t') T(DATA|'Glistening dewdrops adorn the morning grass') T(SEPARATOR|',\r\n\t') T(DATA|'Mystical forests are home to mythical creatures') T(SEPARATOR|',\r\n\t') T(DATA|'Towering redwoods reach for the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Serene meadows stretch out beneath the sun') T(SEPARATOR|',\r\n\t') T(DATA|'Gigantic icebergs float gracefully in frigid waters') T(SEPARATOR|',\r\n\t') T(DATA|'Quivering aspen leaves rustle in the autumn breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Towering cliffs overlook crashing ocean waves') T(SEPARATOR|',\r\n\t') T(DATA|'Colorful hot air balloons dot the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Gentle waves lap against sandy shores') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient pyramids rise from the desert sands') T(SEPARATOR|',\r\n\t') T(DATA|'Whirling tornadoes carve paths of destruction') T(SEPARATOR|',\r\n\t') T(DATA|'Crumbling ruins hint at ancient civilizations') T(SEPARATOR|',\r\n\t') T(DATA|'Elephants parade through the jungle') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent castles overlook vast landscapes') T(SEPARATOR|',\r\n\t') T(DATA|'The shimmering ocean reflects the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Enormous mountains pierce the clear sky') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient ruins stand as testaments to history') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic waterfalls cascade down rocky cliffs') T(SEPARATOR|',\r\n\t') T(DATA|'Lush forests teem with diverse wildlife') T(SEPARATOR|',\r\n\t') T(DATA|'Spectacular fireworks light up the night sky') T(SEPARATOR|',\r\n\t') T(DATA|'Grand cathedrals echo with sacred chants') T(SEPARATOR|',\r\n\t') T(DATA|'Endless deserts stretch across barren plains') T(SEPARATOR|',\r\n\t') T(DATA|'Vibrant tulip fields paint the countryside') T(SEPARATOR|',\r\n\t') T(DATA|'Glorious sunsets set the horizon ablaze') T(SEPARATOR|',\r\n\t') T(DATA|'Whimsical fairies dance under moonlight') T(SEPARATOR|',\r\n\t') T(DATA|'Towering skyscrapers reach for the clouds') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil rivers meander through lush valleys') T(SEPARATOR|',\r\n\t') T(DATA|'Quaint cottages nestle in picturesque villages') T(SEPARATOR|',\r\n\t') T(DATA|'Roaring waterfalls plunge into misty abysses') T(SEPARATOR|',\r\n\t') T(DATA|'Snow') T(HYPHEN|'-') T(DATA|'capped mountains glisten in the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Winding cobblestone streets lead to hidden treasures') T(SEPARATOR|',\r\n\t') T(DATA|'Rustling palm trees sway in the tropical breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Crystal') T(HYPHEN|'-') T(DATA|'clear lakes mirror the surrounding landscape') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient temples whisper tales of bygone eras') T(SEPARATOR|',\r\n\t') T(DATA|'Cascading waterfalls create rainbows in the mist') T(SEPARATOR|',\r\n\t') T(DATA|'Mighty glaciers carve their way through rugged terrain') T(SEPARATOR|',\r\n\t') T(DATA|'Twinkling stars illuminate the midnight sky') T(SEPARATOR|',\r\n\t') T(DATA|'Fragrant flower gardens bloom with vibrant colors') T(SEPARATOR|',\r\n\t') T(DATA|'Towering lighthouses guide ships safely to shore') T(SEPARATOR|',\r\n\t') T(DATA|'Rolling hillsides are dotted with grazing sheep') T(SEPARATOR|',\r\n\t') T(DATA|'Bustling marketplaces buzz with activity') T(SEPARATOR|',\r\n\t') T(DATA|'Steep cliffs plunge into the crashing waves below') T(SEPARATOR|',\r\n\t') T(DATA|'Chirping crickets fill the warm summer night') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent palaces stand as symbols of power') T(SEPARATOR|',\r\n\t') T(DATA|'Endless fields of wheat sway in the gentle breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Whistling winds sweep across vast open plains') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic eagles soar high above rugged peaks') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil ponds reflect the surrounding forest') T(SEPARATOR|',\r\n\t') T(DATA|'Golden sand dunes stretch as far as the eye can see') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient castles whisper secrets of the past') T(SEPARATOR|',\r\n\t') T(DATA|'Glistening dewdrops adorn the morning grass') T(SEPARATOR|',\r\n\t') T(DATA|'Mystical forests are home to mythical creatures') T(SEPARATOR|',\r\n\t') T(DATA|'Towering redwoods reach for the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Serene meadows stretch out beneath the sun') T(SEPARATOR|',\r\n\t') T(DATA|'Gigantic icebergs float gracefully in frigid waters') T(SEPARATOR|',\r\n\t') T(DATA|'Quivering aspen leaves rustle in the autumn breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Towering cliffs overlook crashing ocean waves') T(SEPARATOR|',\r\n\t') T(DATA|'Colorful hot air balloons dot the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Gentle waves lap against sandy shores') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient pyramids rise from the desert sands') T(SEPARATOR|',\r\n\t') T(DATA|'Whirling tornadoes carve paths of destruction') T(SEPARATOR|',\r\n\t') T(DATA|'Crumbling ruins hint at ancient civilizations ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 4864 characters, into 212 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.G_long50.ds"
Preprocessed source code - 2449 characters long

Parsing sequence: T(DATA|'huge list for time benchmark ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'Elephants parade through the jungle') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent castles overlook vast landscapes') T(SEPARATOR|',\r\n\t') T(DATA|'The shimmering ocean reflects the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Enormous mountains pierce the clear sky') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient ruins stand as testaments to history') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic waterfalls cascade down rocky cliffs') T(SEPARATOR|',\r\n\t') T(DATA|'Lush forests teem with diverse wildlife') T(SEPARATOR|',\r\n\t') T(DATA|'Spectacular fireworks light up the night sky') T(SEPARATOR|',\r\n\t') T(DATA|'Grand cathedrals echo with sacred chants') T(SEPARATOR|',\r\n\t') T(DATA|'Endless deserts stretch across barren plains') T(SEPARATOR|',\r\n\t') T(DATA|'Vibrant tulip fields paint the countryside') T(SEPARATOR|',\r\n\t') T(DATA|'Glorious sunsets set the horizon ablaze') T(SEPARATOR|',\r\n\t') T(DATA|'Whimsical fairies dance under moonlight') T(SEPARATOR|',\r\n\t') T(DATA|'Towering skyscrapers reach for the clouds') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil rivers meander through lush valleys') T(SEPARATOR|',\r\n\t') T(DATA|'Quaint cottages nestle in picturesque villages') T(SEPARATOR|',\r\n\t') T(DATA|'Roaring waterfalls plunge into misty abysses') T(SEPARATOR|',\r\n\t') T(DATA|'Snow') T(HYPHEN|'-') T(DATA|'capped mountains glisten in the sunlight') T(SEPARATOR|',\r\n\t') T(DATA|'Winding cobblestone streets lead to hidden treasures') T(SEPARATOR|',\r\n\t') T(DATA|'Rustling palm trees sway in the tropical breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Crystal') T(HYPHEN|'-') T(DATA|'clear lakes mirror the surrounding landscape') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient temples whisper tales of bygone eras') T(SEPARATOR|',\r\n\t') T(DATA|'Cascading waterfalls create rainbows in the mist') T(SEPARATOR|',\r\n\t') T(DATA|'Mighty glaciers carve their way through rugged terrain') T(SEPARATOR|',\r\n\t') T(DATA|'Twinkling stars illuminate the midnight sky') T(SEPARATOR|',\r\n\t') T(DATA|'Fragrant flower gardens bloom with vibrant colors') T(SEPARATOR|',\r\n\t') T(DATA|'Towering lighthouses guide ships safely to shore') T(SEPARATOR|',\r\n\t') T(DATA|'Rolling hillsides are dotted with grazing sheep') T(SEPARATOR|',\r\n\t') T(DATA|'Bustling marketplaces buzz with activity') T(SEPARATOR|',\r\n\t') T(DATA|'Steep cliffs plunge into the crashing waves below') T(SEPARATOR|',\r\n\t') T(DATA|'Chirping crickets fill the warm summer night') T(SEPARATOR|',\r\n\t') T(DATA|'Magnificent palaces stand as symbols of power') T(SEPARATOR|',\r\n\t') T(DATA|'Endless fields of wheat sway in the gentle breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Whistling winds sweep across vast open plains') T(SEPARATOR|',\r\n\t') T(DATA|'Majestic eagles soar high above rugged peaks') T(SEPARATOR|',\r\n\t') T(DATA|'Tranquil ponds reflect the surrounding forest') T(SEPARATOR|',\r\n\t') T(DATA|'Golden sand dunes stretch as far as the eye can see') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient castles whisper secrets of the past') T(SEPARATOR|',\r\n\t') T(DATA|'Glistening dewdrops adorn the morning grass') T(SEPARATOR|',\r\n\t') T(DATA|'Mystical forests are home to mythical creatures') T(SEPARATOR|',\r\n\t') T(DATA|'Towering redwoods reach for the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Serene meadows stretch out beneath the sun') T(SEPARATOR|',\r\n\t') T(DATA|'Gigantic icebergs float gracefully in frigid waters') T(SEPARATOR|',\r\n\t') T(DATA|'Quivering aspen leaves rustle in the autumn breeze') T(SEPARATOR|',\r\n\t') T(DATA|'Towering cliffs overlook crashing ocean waves') T(SEPARATOR|',\r\n\t') T(DATA|'Colorful hot air balloons dot the sky') T(SEPARATOR|',\r\n\t') T(DATA|'Gentle waves lap against sandy shores') T(SEPARATOR|',\r\n\t') T(DATA|'Ancient pyramids rise from the desert sands') T(SEPARATOR|',\r\n\t') T(DATA|'Whirling tornadoes carve paths of destruction') T(SEPARATOR|',\r\n\t') T(DATA|'Crumbling ruins hint at ancient civilizations ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 2449 characters, into 108 tokens.
Those were translated to an AST.
All Files: 34, Succeeded: 34, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

