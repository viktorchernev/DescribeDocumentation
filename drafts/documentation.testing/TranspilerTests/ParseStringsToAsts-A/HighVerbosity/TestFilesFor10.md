========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String[] -> Unfold[]' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
Preprocessed source code - 83 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 83 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
Preprocessed source code - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 84 characters, into 14 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
Preprocessed source code - 88 characters long

Parsing sequence: T(DATA|'fabrics') T(COMMA|', ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(COMMA|', ') T(DATA|'fa') T(COMMA|',') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(COMMA|',') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 88 characters, into 20 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
Preprocessed source code - 87 characters long

Parsing sequence: T(COMMA|',') T(DATA|'fabrics ') T(COMMA|',') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',,\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(COMMA|',') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 87 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
Preprocessed source code - 85 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 85 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fa') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 23 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
Preprocessed source code - 89 characters long

Parsing sequence: T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 89 characters, into 18 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
Preprocessed source code - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 84 characters, into 14 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
Preprocessed source code - 87 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEMICOLON|'; ') T(DATA|'fa') T(SEMICOLON|';') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(SEMICOLON|';') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 87 characters, into 19 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
Preprocessed source code - 86 characters long

Parsing sequence: T(SEMICOLON|';') T(DATA|'fabrics ') T(SEMICOLON|';') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEMICOLON|';') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 86 characters, into 15 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
Preprocessed source code - 118 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<someid>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<someid2> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<someid> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 118 characters, into 17 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
Preprocessed source code - 736 characters long

Parsing sequence: T(DATA|'A vertical tab character (ASCII 11) ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'A form feed character (ASCII 12)') T(SEPARATOR|',\r\n\t') T(DATA|'A next line (NEL) character (Unicode character U+0085)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A non') T(HYPHEN|'-') T(DATA|'breaking space (Unicode character U+00A0)') T(SEPARATOR|', \r\n\t') T(DATA|'An ogham space mark (Unicode character U+1680)') T(SEPARATOR|', \r\n\t') T(DATA|'En Quad (U+2000)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Quad (U+2001)') T(SEPARATOR|', \r\n\t') T(DATA|'En Space (U+2002)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Space (U+2003)') T(SEPARATOR|', \r\n\t') T(DATA|'Three') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2004)') T(SEPARATOR|', \r\n\t') T(DATA|'Four') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2005)') T(SEPARATOR|', \r\n\t') T(DATA|'Six') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2006)') T(SEPARATOR|', \r\n\t') T(DATA|'Punctuation Space (U+2008)') T(SEPARATOR|', \r\n\t') T(DATA|'Thin Space (U+2009)') T(SEPARATOR|', \r\n\t') T(DATA|'Hair Space (U+200A)') T(SEPARATOR|', \r\n\t') T(DATA|'A paragraph separator (Unicode character U+2029)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A narrow no') T(HYPHEN|'-') T(DATA|'break space (Unicode character U+202F)') T(SEPARATOR|', \r\n\t') T(DATA|'A medium mathematical space (Unicode character U+205F)') T(SEPARATOR|', \r\n\t') T(DATA|'An ideographic space (Unicode character U+3000)') T(SEPARATOR|',　\r\n\t') T(DATA|'Figure Space') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 736 characters, into 58 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
Preprocessed source code - 89 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> \r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',  \r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 89 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\t\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t\t\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\t\t\t\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
Preprocessed source code - 138 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /* comment *//* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment */') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 138 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
Preprocessed source code - 184 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t  // comment\r\n ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';  /* comment */ /* comment */\t\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 184 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
Preprocessed source code - 116 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 116 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
Preprocessed source code - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment *//* comment */\r\n/* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /*comment*/\r\n\t/* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment *//* comment */') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 180 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
Preprocessed source code - 156 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 156 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
Preprocessed source code - 175 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>// comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';/* comment *//* comment */\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 175 characters, into 12 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEPARATOR|',, ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 20 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
Preprocessed source code - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 180 characters, into 29 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
Preprocessed source code - 100 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(TERMINATOR|';;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(TERMINATOR|';;') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 100 characters, into 23 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
Preprocessed source code - 95 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_SEPARATOR|'\,') T(COMMA|',') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\,') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 95 characters, into 24 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
Preprocessed source code - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(ESCAPE_HYPHEN|'\-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(ESCAPE_RIGHT_ARROW|'\> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(RIGHT_ARROW|'>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 193 characters, into 36 tokens.
Those were translated to an AST.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
Preprocessed source code - 112 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(SEMICOLON|'; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(SEMICOLON|';') T(ESCAPE_TERMINATOR|'\; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(ESCAPE_TERMINATOR|'\;') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 112 characters, into 30 tokens.
Those were translated to an AST.
All Files: 26, Succeeded: 26, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

