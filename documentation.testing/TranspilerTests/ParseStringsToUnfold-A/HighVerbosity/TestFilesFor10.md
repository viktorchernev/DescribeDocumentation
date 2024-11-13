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
Starting a 'String[] -> Unfold' operation...
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
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
Preprocessed source code - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 84 characters, into 14 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
Preprocessed source code - 88 characters long

Parsing sequence: T(DATA|'fabrics') T(COMMA|', ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(COMMA|', ') T(DATA|'fa') T(COMMA|',') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(COMMA|',') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 88 characters, into 20 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
Preprocessed source code - 87 characters long

Parsing sequence: T(COMMA|',') T(DATA|'fabrics ') T(COMMA|',') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',,\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(COMMA|',') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 87 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
Preprocessed source code - 85 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 85 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fa') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 23 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
Preprocessed source code - 89 characters long

Parsing sequence: T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 89 characters, into 18 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
Preprocessed source code - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 84 characters, into 14 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
Preprocessed source code - 87 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEMICOLON|'; ') T(DATA|'fa') T(SEMICOLON|';') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(SEMICOLON|';') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 87 characters, into 19 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
Preprocessed source code - 86 characters long

Parsing sequence: T(SEMICOLON|';') T(DATA|'fabrics ') T(SEMICOLON|';') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEMICOLON|';') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 86 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
Preprocessed source code - 118 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<someid>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<someid2> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<someid> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 118 characters, into 17 tokens.
Those were translated to 1 productions, containing 4 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
Preprocessed source code - 736 characters long

Parsing sequence: T(DATA|'A vertical tab character (ASCII 11) ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'A form feed character (ASCII 12)') T(SEPARATOR|',\r\n\t') T(DATA|'A next line (NEL) character (Unicode character U+0085)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A non') T(HYPHEN|'-') T(DATA|'breaking space (Unicode character U+00A0)') T(SEPARATOR|', \r\n\t') T(DATA|'An ogham space mark (Unicode character U+1680)') T(SEPARATOR|', \r\n\t') T(DATA|'En Quad (U+2000)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Quad (U+2001)') T(SEPARATOR|', \r\n\t') T(DATA|'En Space (U+2002)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Space (U+2003)') T(SEPARATOR|', \r\n\t') T(DATA|'Three') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2004)') T(SEPARATOR|', \r\n\t') T(DATA|'Four') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2005)') T(SEPARATOR|', \r\n\t') T(DATA|'Six') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2006)') T(SEPARATOR|', \r\n\t') T(DATA|'Punctuation Space (U+2008)') T(SEPARATOR|', \r\n\t') T(DATA|'Thin Space (U+2009)') T(SEPARATOR|', \r\n\t') T(DATA|'Hair Space (U+200A)') T(SEPARATOR|', \r\n\t') T(DATA|'A paragraph separator (Unicode character U+2029)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A narrow no') T(HYPHEN|'-') T(DATA|'break space (Unicode character U+202F)') T(SEPARATOR|', \r\n\t') T(DATA|'A medium mathematical space (Unicode character U+205F)') T(SEPARATOR|', \r\n\t') T(DATA|'An ideographic space (Unicode character U+3000)') T(SEPARATOR|',　\r\n\t') T(DATA|'Figure Space') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 736 characters, into 58 tokens.
Those were translated to 1 productions, containing 20 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
Preprocessed source code - 89 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> \r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',  \r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 89 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\t\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t\t\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\t\t\t\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
Preprocessed source code - 138 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /* comment *//* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment */') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 138 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
Preprocessed source code - 184 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t  // comment\r\n ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';  /* comment */ /* comment */\t\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 184 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
Preprocessed source code - 116 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 116 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
Preprocessed source code - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment *//* comment */\r\n/* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /*comment*/\r\n\t/* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment *//* comment */') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 180 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
Preprocessed source code - 156 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 156 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
Preprocessed source code - 175 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>// comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';/* comment *//* comment */\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 175 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
Preprocessed source code - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEPARATOR|',, ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 91 characters, into 20 tokens.
Those were translated to 1 productions, containing 9 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
Preprocessed source code - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 180 characters, into 29 tokens.
Those were translated to 4 productions, containing 12 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
Preprocessed source code - 100 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(TERMINATOR|';;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(TERMINATOR|';;') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 100 characters, into 23 tokens.
Those were translated to 4 productions, containing 9 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
Preprocessed source code - 95 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_SEPARATOR|'\,') T(COMMA|',') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\,') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 95 characters, into 24 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
Preprocessed source code - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(ESCAPE_HYPHEN|'\-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(ESCAPE_RIGHT_ARROW|'\> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(RIGHT_ARROW|'>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 193 characters, into 36 tokens.
Those were translated to 4 productions, containing 8 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
Preprocessed source code - 112 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(SEMICOLON|'; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(SEMICOLON|';') T(ESCAPE_TERMINATOR|'\; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(ESCAPE_TERMINATOR|'\;') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 112 characters, into 30 tokens.
Those were translated to 4 productions, containing 6 entries.
All Files: 26, Succeeded: 26, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "l.LVWHWCRA.Y6X17I9U" 

    .Productions
        "l.LVWHWCRA.Y6X17I9U" -> "l.LVWHWCRA.0UJ53XA4", "l.LVWHWCRA.2AZS7GN6", "l.LVWHWCRA.0M7YTDER", "l.LVWHWCRA.GJLBS73G";
        "l.HBXDGN4P.VJXRDTV9" -> "l.HBXDGN4P.4G3FA1DD", "l.HBXDGN4P.SGRGP6DW", "l.HBXDGN4P.N6UYYTUR", "l.HBXDGN4P.71TD2UFP";
        "l.8WUDZBQM.W4R79R8G" -> "l.8WUDZBQM.Z8UBWTE7", "l.8WUDZBQM.ZW6HBOE1", "l.8WUDZBQM.37MOSTM4", "l.8WUDZBQM.XH85TXZY";
        "l.LJV1Q4MY.LUMPHR49" -> "l.LJV1Q4MY.SK54JBB0", "l.LJV1Q4MY.1R2S8958", "l.LJV1Q4MY.9E0Y938M", "l.LJV1Q4MY.M5RDZWG0";
        "l.ICW61ZPG.WJ76C7TO" -> "l.ICW61ZPG.DOC6Y7J2", "l.ICW61ZPG.BKWZ8N2Y", "l.ICW61ZPG.YM472NXC", "l.ICW61ZPG.GS53LW2Z";
        "l.GWXJ9EU0.HS0X0D3N" -> "l.GWXJ9EU0.EY5AEUZ6", "l.GWXJ9EU0.WJ4O8KTD", "l.GWXJ9EU0.G8X5LN18", "l.GWXJ9EU0.XEQFHLYB";
        "l.WAZBDHJW.NA44IY0I" -> "l.WAZBDHJW.NKMUUNZ7", "l.WAZBDHJW.BBDPHSZA", "l.WAZBDHJW.0A7MGNZ8", "l.WAZBDHJW.BGDHGENA";
        "l.I6L3CYB8.UT7Y2A7Z" -> "l.I6L3CYB8.UHI99WVR", "l.I6L3CYB8.SYNGKOEI", "l.I6L3CYB8.4HN0MWBK", "l.I6L3CYB8.KMKPLEQG";
        "l.XEJCDGUN.FM5DP46U" -> "l.XEJCDGUN.5L5P14F1", "l.XEJCDGUN.UINBHO9N", "l.XEJCDGUN.GDARNFE6", "l.XEJCDGUN.71A8PS9L";
        "l.SY52SW9O.PO0OEWK6" -> "l.SY52SW9O.VL4BWQOQ", "l.SY52SW9O.ZTU474JM", "l.SY52SW9O.YDR5O4BZ", "l.SY52SW9O.EGETWB94";
        "l.FY60N5WI.6N5AIIEP" -> "l.FY60N5WI.someid", "l.FY60N5WI.V5B13CEJ";
        "l.817R158N.UAYSVLNT" -> 
            "l.817R158N.R8PD7R8X", "l.817R158N.G75G49CV", "l.817R158N.D78ODN7Y", "l.817R158N.JWT48DVE", "l.817R158N.T17S6YE2", "l.817R158N.I4PK3ADG", "l.817R158N.4BVVU2U5", "l.817R158N.2Q5QNFUF", "l.817R158N.XSFNZTWP", "l.817R158N.P8K3Q80V", 
            "l.817R158N.HOPJ11SX", "l.817R158N.PAJAHVBN", "l.817R158N.D2Y4ILDL", "l.817R158N.FIG6J2NL", "l.817R158N.FLXZ36H9", "l.817R158N.SYSHIR8L", "l.817R158N.CWPMKB5T", "l.817R158N.EDDYVBC8", "l.817R158N.CT6H2WZH";
        "l.SUXDU7CR.F8ED956J" -> "l.SUXDU7CR.TG2KSW6X", "l.SUXDU7CR.F92JTDCS", "l.SUXDU7CR.IZROWYBR", "l.SUXDU7CR.DL96XGL1";
        "l.QYR27W3C.XYDW0VAS" -> "l.QYR27W3C.J5WZLA97", "l.QYR27W3C.AIYR6H5F", "l.QYR27W3C.JU7HQ9XL", "l.QYR27W3C.A073IWVI";
        "l.4GVUK4G2.Z0FKZRMQ" -> "l.4GVUK4G2.P0H87IPT", "l.4GVUK4G2.HXBAH90N", "l.4GVUK4G2.3UATJ7SI", "l.4GVUK4G2.SYSSJADU";
        "l.RUOJBUN4.09HRE3C8" -> "l.RUOJBUN4.XIAM7N96", "l.RUOJBUN4.4YVHIQ8S", "l.RUOJBUN4.FBXI0X8C", "l.RUOJBUN4.QAVO7LUP";
        "l.UTFH9D1Q.QSTZA5V4" -> "l.UTFH9D1Q.0BVW1W8Z", "l.UTFH9D1Q.GG0VC7Q1", "l.UTFH9D1Q.KHG2TTX4", "l.UTFH9D1Q.IE67LXHU";
        "l.4JRSOXJV.W88TJMOF" -> "l.4JRSOXJV.TFN2JEWI", "l.4JRSOXJV.YWP32A94", "l.4JRSOXJV.URR301IG", "l.4JRSOXJV.X7191SJG";
        "l.NYTQWDNK.RQ0IICXH" -> "l.NYTQWDNK.1W2ASL5L", "l.NYTQWDNK.4MU3NG9T", "l.NYTQWDNK.DH8V0RVE", "l.NYTQWDNK.37RDZ3F9";
        "l.NQV67GAK.IY60ML3O" -> "l.NQV67GAK.UYR1ULBJ", "l.NQV67GAK.KUCXVEX5", "l.NQV67GAK.RII1A0WL", "l.NQV67GAK.DP940KC3";
        "l.2TKBJRZA.3S79PGAT" -> "l.2TKBJRZA.HHOZIESQ", "l.2TKBJRZA.AJGCEZBT", "l.2TKBJRZA.5JCK9WK4", "l.2TKBJRZA.QNFPBWIP", "l.2TKBJRZA.S4H60IWV", "l.2TKBJRZA.PGSJNCAK", "l.2TKBJRZA.8NG9NV1X", "l.2TKBJRZA.VKDV7CMP";
        "l.DSRKZWY1.703J2K3E" -> "l.DSRKZWY1.P6ZF6TSV", "l.DSRKZWY1.2SHR03C6";
        "l.DSRKZWY1.HCHXVCRK" -> "l.DSRKZWY1.SKFB1V2G", "l.DSRKZWY1.QCF4GQQG";
        "l.DSRKZWY1.R5B9MGRZ" -> "l.DSRKZWY1.V504CME5", "l.DSRKZWY1.KSPGTOA2";
        "l.DSRKZWY1.532KF35E" -> "l.DSRKZWY1.I5QNI44G", "l.DSRKZWY1.EOQAVGZD";
        "l.UGBN1NUG.2067RIMW" -> ".UGBN1NUG.A0FY43BF";
        "l.UGBN1NUG.SL1FKTEG" -> ".UGBN1NUG.FTFAQWNW";
        "l.UGBN1NUG.CN72ARYD" -> ".UGBN1NUG.ES87JMS0";
        "l.UGBN1NUG.U5QWRKLK" -> "l.UGBN1NUG.DRJ7Q27I", "l.UGBN1NUG.A9UVC6B9";
        "l.B2RJ56CA.73W7P1G7" -> "l.B2RJ56CA.4NIE5C2E", "l.B2RJ56CA.5BR74SQK", "l.B2RJ56CA.L4QR4BQ4", "l.B2RJ56CA.YVJ9NOC8";
        "l.QA54EXG8.DICPAZRM" -> ".QA54EXG8.Y8QW9JKA";
        "l.QA54EXG8.9A4NCVEP" -> ".QA54EXG8.LQLIYWLV";
        "l.QA54EXG8.UTO16474" -> ".QA54EXG8.QDU7E72K";
        "l.QA54EXG8.6EHU886B" -> ".QA54EXG8.OTU5W6SF";
        "l.OCWYRYBR.CC0H3ZAD" -> "l.OCWYRYBR.IM7TDYOS", "l.OCWYRYBR.S7HY6T15";
        "l.OCWYRYBR.ZR6BJ9WM" -> "l.OCWYRYBR.CC0H3ZAD";
        "l.OCWYRYBR.17UGQZLD" -> "l.OCWYRYBR.ZR6BJ9WM";
        "l.OCWYRYBR.JU8LRTW8" -> "l.OCWYRYBR.17UGQZLD";

    .Translations
        "l.LVWHWCRA.Y6X17I9U" - "fabrics"
        "l.LVWHWCRA.0UJ53XA4" - "wool fabrics"
        "l.LVWHWCRA.2AZS7GN6" - "cotton fabrics"
        "l.LVWHWCRA.0M7YTDER" - "silk fabrics"
        "l.LVWHWCRA.GJLBS73G" - "synthetic fabrics"
        "l.HBXDGN4P.VJXRDTV9" - "fabrics"
        "l.HBXDGN4P.4G3FA1DD" - "wool, fabrics"
        "l.HBXDGN4P.SGRGP6DW" - "cotton fabrics"
        "l.HBXDGN4P.N6UYYTUR" - "silk fabrics"
        "l.HBXDGN4P.71TD2UFP" - "synthetic fabrics"
        "l.8WUDZBQM.W4R79R8G" - "fabrics,"
        "l.8WUDZBQM.Z8UBWTE7" - "wool, fabrics"
        "l.8WUDZBQM.ZW6HBOE1" - "cotton, fa,brics"
        "l.8WUDZBQM.37MOSTM4" - ",silk fabrics"
        "l.8WUDZBQM.XH85TXZY" - "synthetic fabrics"
        "l.LJV1Q4MY.LUMPHR49" - ",fabrics ,"
        "l.LJV1Q4MY.SK54JBB0" - "wool fabrics"
        "l.LJV1Q4MY.1R2S8958" - "cotton fabrics"
        "l.LJV1Q4MY.9E0Y938M" - "silk fabrics"
        "l.LJV1Q4MY.M5RDZWG0" - "synthetic fabrics,"
        "l.ICW61ZPG.WJ76C7TO" - "fabrics"
        "l.ICW61ZPG.DOC6Y7J2" - "wool-> fabrics"
        "l.ICW61ZPG.BKWZ8N2Y" - "cotton fabrics"
        "l.ICW61ZPG.YM472NXC" - "silk fabrics"
        "l.ICW61ZPG.GS53LW2Z" - "synthetic fabrics"
        "l.GWXJ9EU0.HS0X0D3N" - "fabrics"
        "l.GWXJ9EU0.EY5AEUZ6" - "wool-> fabrics"
        "l.GWXJ9EU0.WJ4O8KTD" - "cotton-> fa->brics"
        "l.GWXJ9EU0.G8X5LN18" - "->silk fabrics"
        "l.GWXJ9EU0.XEQFHLYB" - "synthetic fabrics"
        "l.WAZBDHJW.NA44IY0I" - "->fabrics ->"
        "l.WAZBDHJW.NKMUUNZ7" - "wool fabrics->"
        "l.WAZBDHJW.BBDPHSZA" - "cotton fabrics"
        "l.WAZBDHJW.0A7MGNZ8" - "silk fabrics"
        "l.WAZBDHJW.BGDHGENA" - "synthetic fabrics"
        "l.I6L3CYB8.UT7Y2A7Z" - "fabrics"
        "l.I6L3CYB8.UHI99WVR" - "wool; fabrics"
        "l.I6L3CYB8.SYNGKOEI" - "cotton fabrics"
        "l.I6L3CYB8.4HN0MWBK" - "silk fabrics"
        "l.I6L3CYB8.KMKPLEQG" - "synthetic fabrics"
        "l.XEJCDGUN.FM5DP46U" - "fabrics"
        "l.XEJCDGUN.5L5P14F1" - "wool; fabrics"
        "l.XEJCDGUN.UINBHO9N" - "cotton; fa;brics"
        "l.XEJCDGUN.GDARNFE6" - ";silk fabrics"
        "l.XEJCDGUN.71A8PS9L" - "synthetic fabrics"
        "l.SY52SW9O.PO0OEWK6" - ";fabrics ;"
        "l.SY52SW9O.VL4BWQOQ" - "wool fabrics;"
        "l.SY52SW9O.ZTU474JM" - "cotton fabrics"
        "l.SY52SW9O.YDR5O4BZ" - "silk fabrics"
        "l.SY52SW9O.EGETWB94" - "synthetic fabrics"
        "l.FY60N5WI.6N5AIIEP" - "fabrics"
        "l.FY60N5WI.someid" - "silk fabrics"
        "l.FY60N5WI.someid2" - "cotton fabrics"
        "l.FY60N5WI.V5B13CEJ" - "synthetic fabrics"
        "l.817R158N.UAYSVLNT" - "A vertical tab character (ASCII 11)"
        "l.817R158N.R8PD7R8X" - "A form feed character (ASCII 12)"
        "l.817R158N.G75G49CV" - "A next line (NEL) character (Unicode character U+0085)"
        "l.817R158N.D78ODN7Y" - "A non-breaking space (Unicode character U+00A0)"
        "l.817R158N.JWT48DVE" - "An ogham space mark (Unicode character U+1680)"
        "l.817R158N.T17S6YE2" - "En Quad (U+2000)"
        "l.817R158N.I4PK3ADG" - "Em Quad (U+2001)"
        "l.817R158N.4BVVU2U5" - "En Space (U+2002)"
        "l.817R158N.2Q5QNFUF" - "Em Space (U+2003)"
        "l.817R158N.XSFNZTWP" - "Three-Per-Em Space (U+2004)"
        "l.817R158N.P8K3Q80V" - "Four-Per-Em Space (U+2005)"
        "l.817R158N.HOPJ11SX" - "Six-Per-Em Space (U+2006)"
        "l.817R158N.PAJAHVBN" - "Punctuation Space (U+2008)"
        "l.817R158N.D2Y4ILDL" - "Thin Space (U+2009)"
        "l.817R158N.FIG6J2NL" - "Hair Space (U+200A)"
        "l.817R158N.FLXZ36H9" - "A paragraph separator (Unicode character U+2029)"
        "l.817R158N.SYSHIR8L" - "A narrow no-break space (Unicode character U+202F)"
        "l.817R158N.CWPMKB5T" - "A medium mathematical space (Unicode character U+205F)"
        "l.817R158N.EDDYVBC8" - "An ideographic space (Unicode character U+3000)"
        "l.817R158N.CT6H2WZH" - "Figure Space"
        "l.SUXDU7CR.F8ED956J" - "fabrics"
        "l.SUXDU7CR.TG2KSW6X" - "wool fabrics"
        "l.SUXDU7CR.F92JTDCS" - "cotton fabrics"
        "l.SUXDU7CR.IZROWYBR" - "silk fabrics"
        "l.SUXDU7CR.DL96XGL1" - "synthetic fabrics"
        "l.QYR27W3C.XYDW0VAS" - "fabrics"
        "l.QYR27W3C.J5WZLA97" - "wool fabrics"
        "l.QYR27W3C.AIYR6H5F" - "cotton fabrics"
        "l.QYR27W3C.JU7HQ9XL" - "silk fabrics"
        "l.QYR27W3C.A073IWVI" - "synthetic fabrics"
        "l.4GVUK4G2.Z0FKZRMQ" - "fabrics"
        "l.4GVUK4G2.P0H87IPT" - "wool fabrics"
        "l.4GVUK4G2.HXBAH90N" - "cotton fabrics"
        "l.4GVUK4G2.3UATJ7SI" - "silk fabrics"
        "l.4GVUK4G2.SYSSJADU" - "synthetic fabrics"
        "l.RUOJBUN4.09HRE3C8" - "fabrics"
        "l.RUOJBUN4.XIAM7N96" - "wool fabrics"
        "l.RUOJBUN4.4YVHIQ8S" - "cotton fabrics"
        "l.RUOJBUN4.FBXI0X8C" - "silk fabrics"
        "l.RUOJBUN4.QAVO7LUP" - "synthetic fabrics"
        "l.UTFH9D1Q.QSTZA5V4" - "fabrics"
        "l.UTFH9D1Q.0BVW1W8Z" - "wool fabrics"
        "l.UTFH9D1Q.GG0VC7Q1" - "cotton fabrics"
        "l.UTFH9D1Q.KHG2TTX4" - "silk fabrics"
        "l.UTFH9D1Q.IE67LXHU" - "synthetic fabrics"
        "l.4JRSOXJV.W88TJMOF" - "fabrics"
        "l.4JRSOXJV.TFN2JEWI" - "wool fabrics"
        "l.4JRSOXJV.YWP32A94" - "cotton fabrics"
        "l.4JRSOXJV.URR301IG" - "silk fabrics"
        "l.4JRSOXJV.X7191SJG" - "synthetic fabrics"
        "l.NYTQWDNK.RQ0IICXH" - "fabrics"
        "l.NYTQWDNK.1W2ASL5L" - "wool fabrics"
        "l.NYTQWDNK.4MU3NG9T" - "cotton fabrics"
        "l.NYTQWDNK.DH8V0RVE" - "silk fabrics"
        "l.NYTQWDNK.37RDZ3F9" - "synthetic fabrics"
        "l.NQV67GAK.IY60ML3O" - "fabrics"
        "l.NQV67GAK.UYR1ULBJ" - "wool fabrics"
        "l.NQV67GAK.KUCXVEX5" - "cotton fabrics"
        "l.NQV67GAK.RII1A0WL" - "silk fabrics"
        "l.NQV67GAK.DP940KC3" - "synthetic fabrics"
        "l.2TKBJRZA.3S79PGAT" - "fabrics"
        "l.2TKBJRZA.HHOZIESQ" - "wool"
        "l.2TKBJRZA.AJGCEZBT" - "fabrics"
        "l.2TKBJRZA.5JCK9WK4" - "cotton"
        "l.2TKBJRZA.QNFPBWIP" - "fabrics"
        "l.2TKBJRZA.S4H60IWV" - "silk"
        "l.2TKBJRZA.PGSJNCAK" - "fabrics"
        "l.2TKBJRZA.8NG9NV1X" - "synthetic"
        "l.2TKBJRZA.VKDV7CMP" - "fabrics"
        "l.DSRKZWY1.703J2K3E" - "fabrics"
        "l.DSRKZWY1.P6ZF6TSV" - "wool fabrics"
        "l.DSRKZWY1.2SHR03C6" - "synthetic fabrics"
        "l.DSRKZWY1.HCHXVCRK" - "fabrics"
        "l.DSRKZWY1.SKFB1V2G" - "wool fabrics"
        "l.DSRKZWY1.QCF4GQQG" - "cotton fabrics"
        "l.DSRKZWY1.R5B9MGRZ" - "fabrics"
        "l.DSRKZWY1.V504CME5" - "wool fabrics"
        "l.DSRKZWY1.KSPGTOA2" - "silk fabrics"
        "l.DSRKZWY1.532KF35E" - "fabrics"
        "l.DSRKZWY1.I5QNI44G" - "wool fabrics"
        "l.DSRKZWY1.EOQAVGZD" - "other fabrics"
        "l.UGBN1NUG.2067RIMW" - "fabrics"
        "l.UGBN1NUG.A0FY43BF" - "wool"
        "l.UGBN1NUG.SL1FKTEG" - "fabrics"
        "l.UGBN1NUG.FTFAQWNW" - "cotton"
        "l.UGBN1NUG.CN72ARYD" - "fabrics"
        "l.UGBN1NUG.ES87JMS0" - "silk"
        "l.UGBN1NUG.U5QWRKLK" - "fabrics"
        "l.UGBN1NUG.DRJ7Q27I" - "synthetic"
        "l.UGBN1NUG.A9UVC6B9" - "fabrics"
        "l.B2RJ56CA.73W7P1G7" - "fabrics"
        "l.B2RJ56CA.4NIE5C2E" - "wool\,,fabrics"
        "l.B2RJ56CA.5BR74SQK" - "cotton\,, fabrics"
        "l.B2RJ56CA.L4QR4BQ4" - "silk ,\,fabrics"
        "l.B2RJ56CA.YVJ9NOC8" - "synthetic ,\, fabrics"
        "l.QA54EXG8.DICPAZRM" - "fabrics \->> wool fabrics"
        "l.QA54EXG8.Y8QW9JKA" - "synthetic fabrics"
        "l.QA54EXG8.9A4NCVEP" - "fabrics->\> wool fabrics"
        "l.QA54EXG8.LQLIYWLV" - "cotton fabrics"
        "l.QA54EXG8.UTO16474" - "fabrics -\>>wool fabrics"
        "l.QA54EXG8.QDU7E72K" - "silk fabrics"
        "l.QA54EXG8.6EHU886B" - "fabrics-\>\>wool fabrics"
        "l.QA54EXG8.OTU5W6SF" - "other fabrics"
        "l.OCWYRYBR.JU8LRTW8" - "fabrics"
        "l.OCWYRYBR.17UGQZLD" - "wool\;; fabrics"
        "l.OCWYRYBR.ZR6BJ9WM" - "cotton ;\; fabrics"
        "l.OCWYRYBR.CC0H3ZAD" - "silk \;\;fabrics"
        "l.OCWYRYBR.IM7TDYOS" - "synthetic"
        "l.OCWYRYBR.S7HY6T15" - "fabrics\;"

    .Links
        "l.LVWHWCRA.Y6X17I9U" - 
        "l.LVWHWCRA.0UJ53XA4" - 
        "l.LVWHWCRA.2AZS7GN6" - 
        "l.LVWHWCRA.0M7YTDER" - 
        "l.LVWHWCRA.GJLBS73G" - 
        "l.HBXDGN4P.VJXRDTV9" - 
        "l.HBXDGN4P.4G3FA1DD" - 
        "l.HBXDGN4P.SGRGP6DW" - 
        "l.HBXDGN4P.N6UYYTUR" - 
        "l.HBXDGN4P.71TD2UFP" - 
        "l.8WUDZBQM.W4R79R8G" - 
        "l.8WUDZBQM.Z8UBWTE7" - 
        "l.8WUDZBQM.ZW6HBOE1" - 
        "l.8WUDZBQM.37MOSTM4" - 
        "l.8WUDZBQM.XH85TXZY" - 
        "l.LJV1Q4MY.LUMPHR49" - 
        "l.LJV1Q4MY.SK54JBB0" - 
        "l.LJV1Q4MY.1R2S8958" - 
        "l.LJV1Q4MY.9E0Y938M" - 
        "l.LJV1Q4MY.M5RDZWG0" - 
        "l.ICW61ZPG.WJ76C7TO" - 
        "l.ICW61ZPG.DOC6Y7J2" - 
        "l.ICW61ZPG.BKWZ8N2Y" - 
        "l.ICW61ZPG.YM472NXC" - 
        "l.ICW61ZPG.GS53LW2Z" - 
        "l.GWXJ9EU0.HS0X0D3N" - 
        "l.GWXJ9EU0.EY5AEUZ6" - 
        "l.GWXJ9EU0.WJ4O8KTD" - 
        "l.GWXJ9EU0.G8X5LN18" - 
        "l.GWXJ9EU0.XEQFHLYB" - 
        "l.WAZBDHJW.NA44IY0I" - 
        "l.WAZBDHJW.NKMUUNZ7" - 
        "l.WAZBDHJW.BBDPHSZA" - 
        "l.WAZBDHJW.0A7MGNZ8" - 
        "l.WAZBDHJW.BGDHGENA" - 
        "l.I6L3CYB8.UT7Y2A7Z" - 
        "l.I6L3CYB8.UHI99WVR" - 
        "l.I6L3CYB8.SYNGKOEI" - 
        "l.I6L3CYB8.4HN0MWBK" - 
        "l.I6L3CYB8.KMKPLEQG" - 
        "l.XEJCDGUN.FM5DP46U" - 
        "l.XEJCDGUN.5L5P14F1" - 
        "l.XEJCDGUN.UINBHO9N" - 
        "l.XEJCDGUN.GDARNFE6" - 
        "l.XEJCDGUN.71A8PS9L" - 
        "l.SY52SW9O.PO0OEWK6" - 
        "l.SY52SW9O.VL4BWQOQ" - 
        "l.SY52SW9O.ZTU474JM" - 
        "l.SY52SW9O.YDR5O4BZ" - 
        "l.SY52SW9O.EGETWB94" - 
        "l.FY60N5WI.6N5AIIEP" - 
        "l.FY60N5WI.someid" - 
        "l.FY60N5WI.someid2" - 
        "l.FY60N5WI.V5B13CEJ" - 
        "l.817R158N.UAYSVLNT" - 
        "l.817R158N.R8PD7R8X" - 
        "l.817R158N.G75G49CV" - 
        "l.817R158N.D78ODN7Y" - 
        "l.817R158N.JWT48DVE" - 
        "l.817R158N.T17S6YE2" - 
        "l.817R158N.I4PK3ADG" - 
        "l.817R158N.4BVVU2U5" - 
        "l.817R158N.2Q5QNFUF" - 
        "l.817R158N.XSFNZTWP" - 
        "l.817R158N.P8K3Q80V" - 
        "l.817R158N.HOPJ11SX" - 
        "l.817R158N.PAJAHVBN" - 
        "l.817R158N.D2Y4ILDL" - 
        "l.817R158N.FIG6J2NL" - 
        "l.817R158N.FLXZ36H9" - 
        "l.817R158N.SYSHIR8L" - 
        "l.817R158N.CWPMKB5T" - 
        "l.817R158N.EDDYVBC8" - 
        "l.817R158N.CT6H2WZH" - 
        "l.SUXDU7CR.F8ED956J" - 
        "l.SUXDU7CR.TG2KSW6X" - 
        "l.SUXDU7CR.F92JTDCS" - 
        "l.SUXDU7CR.IZROWYBR" - 
        "l.SUXDU7CR.DL96XGL1" - 
        "l.QYR27W3C.XYDW0VAS" - 
        "l.QYR27W3C.J5WZLA97" - 
        "l.QYR27W3C.AIYR6H5F" - 
        "l.QYR27W3C.JU7HQ9XL" - 
        "l.QYR27W3C.A073IWVI" - 
        "l.4GVUK4G2.Z0FKZRMQ" - 
        "l.4GVUK4G2.P0H87IPT" - 
        "l.4GVUK4G2.HXBAH90N" - 
        "l.4GVUK4G2.3UATJ7SI" - 
        "l.4GVUK4G2.SYSSJADU" - 
        "l.RUOJBUN4.09HRE3C8" - 
        "l.RUOJBUN4.XIAM7N96" - 
        "l.RUOJBUN4.4YVHIQ8S" - 
        "l.RUOJBUN4.FBXI0X8C" - 
        "l.RUOJBUN4.QAVO7LUP" - 
        "l.UTFH9D1Q.QSTZA5V4" - 
        "l.UTFH9D1Q.0BVW1W8Z" - 
        "l.UTFH9D1Q.GG0VC7Q1" - 
        "l.UTFH9D1Q.KHG2TTX4" - 
        "l.UTFH9D1Q.IE67LXHU" - 
        "l.4JRSOXJV.W88TJMOF" - 
        "l.4JRSOXJV.TFN2JEWI" - 
        "l.4JRSOXJV.YWP32A94" - 
        "l.4JRSOXJV.URR301IG" - 
        "l.4JRSOXJV.X7191SJG" - 
        "l.NYTQWDNK.RQ0IICXH" - 
        "l.NYTQWDNK.1W2ASL5L" - 
        "l.NYTQWDNK.4MU3NG9T" - 
        "l.NYTQWDNK.DH8V0RVE" - 
        "l.NYTQWDNK.37RDZ3F9" - 
        "l.NQV67GAK.IY60ML3O" - 
        "l.NQV67GAK.UYR1ULBJ" - 
        "l.NQV67GAK.KUCXVEX5" - 
        "l.NQV67GAK.RII1A0WL" - 
        "l.NQV67GAK.DP940KC3" - 
        "l.2TKBJRZA.3S79PGAT" - 
        "l.2TKBJRZA.HHOZIESQ" - 
        "l.2TKBJRZA.AJGCEZBT" - 
        "l.2TKBJRZA.5JCK9WK4" - 
        "l.2TKBJRZA.QNFPBWIP" - 
        "l.2TKBJRZA.S4H60IWV" - 
        "l.2TKBJRZA.PGSJNCAK" - 
        "l.2TKBJRZA.8NG9NV1X" - 
        "l.2TKBJRZA.VKDV7CMP" - 
        "l.DSRKZWY1.703J2K3E" - 
        "l.DSRKZWY1.P6ZF6TSV" - 
        "l.DSRKZWY1.2SHR03C6" - 
        "l.DSRKZWY1.HCHXVCRK" - 
        "l.DSRKZWY1.SKFB1V2G" - 
        "l.DSRKZWY1.QCF4GQQG" - 
        "l.DSRKZWY1.R5B9MGRZ" - 
        "l.DSRKZWY1.V504CME5" - 
        "l.DSRKZWY1.KSPGTOA2" - 
        "l.DSRKZWY1.532KF35E" - 
        "l.DSRKZWY1.I5QNI44G" - 
        "l.DSRKZWY1.EOQAVGZD" - 
        "l.UGBN1NUG.2067RIMW" - 
        "l.UGBN1NUG.A0FY43BF" - 
        "l.UGBN1NUG.SL1FKTEG" - 
        "l.UGBN1NUG.FTFAQWNW" - 
        "l.UGBN1NUG.CN72ARYD" - 
        "l.UGBN1NUG.ES87JMS0" - 
        "l.UGBN1NUG.U5QWRKLK" - 
        "l.UGBN1NUG.DRJ7Q27I" - 
        "l.UGBN1NUG.A9UVC6B9" - 
        "l.B2RJ56CA.73W7P1G7" - 
        "l.B2RJ56CA.4NIE5C2E" - 
        "l.B2RJ56CA.5BR74SQK" - 
        "l.B2RJ56CA.L4QR4BQ4" - 
        "l.B2RJ56CA.YVJ9NOC8" - 
        "l.QA54EXG8.DICPAZRM" - 
        "l.QA54EXG8.Y8QW9JKA" - 
        "l.QA54EXG8.9A4NCVEP" - 
        "l.QA54EXG8.LQLIYWLV" - 
        "l.QA54EXG8.UTO16474" - 
        "l.QA54EXG8.QDU7E72K" - 
        "l.QA54EXG8.6EHU886B" - 
        "l.QA54EXG8.OTU5W6SF" - 
        "l.OCWYRYBR.JU8LRTW8" - 
        "l.OCWYRYBR.17UGQZLD" - 
        "l.OCWYRYBR.ZR6BJ9WM" - 
        "l.OCWYRYBR.CC0H3ZAD" - 
        "l.OCWYRYBR.IM7TDYOS" - 
        "l.OCWYRYBR.S7HY6T15" - 

    .Decorators
        "l.LVWHWCRA.Y6X17I9U" - 
        "l.LVWHWCRA.0UJ53XA4" - 
        "l.LVWHWCRA.2AZS7GN6" - 
        "l.LVWHWCRA.0M7YTDER" - 
        "l.LVWHWCRA.GJLBS73G" - 
        "l.HBXDGN4P.VJXRDTV9" - 
        "l.HBXDGN4P.4G3FA1DD" - 
        "l.HBXDGN4P.SGRGP6DW" - 
        "l.HBXDGN4P.N6UYYTUR" - 
        "l.HBXDGN4P.71TD2UFP" - 
        "l.8WUDZBQM.W4R79R8G" - 
        "l.8WUDZBQM.Z8UBWTE7" - 
        "l.8WUDZBQM.ZW6HBOE1" - 
        "l.8WUDZBQM.37MOSTM4" - 
        "l.8WUDZBQM.XH85TXZY" - 
        "l.LJV1Q4MY.LUMPHR49" - 
        "l.LJV1Q4MY.SK54JBB0" - 
        "l.LJV1Q4MY.1R2S8958" - 
        "l.LJV1Q4MY.9E0Y938M" - 
        "l.LJV1Q4MY.M5RDZWG0" - 
        "l.ICW61ZPG.WJ76C7TO" - 
        "l.ICW61ZPG.DOC6Y7J2" - 
        "l.ICW61ZPG.BKWZ8N2Y" - 
        "l.ICW61ZPG.YM472NXC" - 
        "l.ICW61ZPG.GS53LW2Z" - 
        "l.GWXJ9EU0.HS0X0D3N" - 
        "l.GWXJ9EU0.EY5AEUZ6" - 
        "l.GWXJ9EU0.WJ4O8KTD" - 
        "l.GWXJ9EU0.G8X5LN18" - 
        "l.GWXJ9EU0.XEQFHLYB" - 
        "l.WAZBDHJW.NA44IY0I" - 
        "l.WAZBDHJW.NKMUUNZ7" - 
        "l.WAZBDHJW.BBDPHSZA" - 
        "l.WAZBDHJW.0A7MGNZ8" - 
        "l.WAZBDHJW.BGDHGENA" - 
        "l.I6L3CYB8.UT7Y2A7Z" - 
        "l.I6L3CYB8.UHI99WVR" - 
        "l.I6L3CYB8.SYNGKOEI" - 
        "l.I6L3CYB8.4HN0MWBK" - 
        "l.I6L3CYB8.KMKPLEQG" - 
        "l.XEJCDGUN.FM5DP46U" - 
        "l.XEJCDGUN.5L5P14F1" - 
        "l.XEJCDGUN.UINBHO9N" - 
        "l.XEJCDGUN.GDARNFE6" - 
        "l.XEJCDGUN.71A8PS9L" - 
        "l.SY52SW9O.PO0OEWK6" - 
        "l.SY52SW9O.VL4BWQOQ" - 
        "l.SY52SW9O.ZTU474JM" - 
        "l.SY52SW9O.YDR5O4BZ" - 
        "l.SY52SW9O.EGETWB94" - 
        "l.FY60N5WI.6N5AIIEP" - 
        "l.FY60N5WI.someid" - 
        "l.FY60N5WI.someid2" - 
        "l.FY60N5WI.V5B13CEJ" - 
        "l.817R158N.UAYSVLNT" - 
        "l.817R158N.R8PD7R8X" - 
        "l.817R158N.G75G49CV" - 
        "l.817R158N.D78ODN7Y" - 
        "l.817R158N.JWT48DVE" - 
        "l.817R158N.T17S6YE2" - 
        "l.817R158N.I4PK3ADG" - 
        "l.817R158N.4BVVU2U5" - 
        "l.817R158N.2Q5QNFUF" - 
        "l.817R158N.XSFNZTWP" - 
        "l.817R158N.P8K3Q80V" - 
        "l.817R158N.HOPJ11SX" - 
        "l.817R158N.PAJAHVBN" - 
        "l.817R158N.D2Y4ILDL" - 
        "l.817R158N.FIG6J2NL" - 
        "l.817R158N.FLXZ36H9" - 
        "l.817R158N.SYSHIR8L" - 
        "l.817R158N.CWPMKB5T" - 
        "l.817R158N.EDDYVBC8" - 
        "l.817R158N.CT6H2WZH" - 
        "l.SUXDU7CR.F8ED956J" - 
        "l.SUXDU7CR.TG2KSW6X" - 
        "l.SUXDU7CR.F92JTDCS" - 
        "l.SUXDU7CR.IZROWYBR" - 
        "l.SUXDU7CR.DL96XGL1" - 
        "l.QYR27W3C.XYDW0VAS" - 
        "l.QYR27W3C.J5WZLA97" - 
        "l.QYR27W3C.AIYR6H5F" - 
        "l.QYR27W3C.JU7HQ9XL" - 
        "l.QYR27W3C.A073IWVI" - 
        "l.4GVUK4G2.Z0FKZRMQ" - 
        "l.4GVUK4G2.P0H87IPT" - 
        "l.4GVUK4G2.HXBAH90N" - 
        "l.4GVUK4G2.3UATJ7SI" - 
        "l.4GVUK4G2.SYSSJADU" - 
        "l.RUOJBUN4.09HRE3C8" - 
        "l.RUOJBUN4.XIAM7N96" - 
        "l.RUOJBUN4.4YVHIQ8S" - 
        "l.RUOJBUN4.FBXI0X8C" - 
        "l.RUOJBUN4.QAVO7LUP" - 
        "l.UTFH9D1Q.QSTZA5V4" - 
        "l.UTFH9D1Q.0BVW1W8Z" - 
        "l.UTFH9D1Q.GG0VC7Q1" - 
        "l.UTFH9D1Q.KHG2TTX4" - 
        "l.UTFH9D1Q.IE67LXHU" - 
        "l.4JRSOXJV.W88TJMOF" - 
        "l.4JRSOXJV.TFN2JEWI" - 
        "l.4JRSOXJV.YWP32A94" - 
        "l.4JRSOXJV.URR301IG" - 
        "l.4JRSOXJV.X7191SJG" - 
        "l.NYTQWDNK.RQ0IICXH" - 
        "l.NYTQWDNK.1W2ASL5L" - 
        "l.NYTQWDNK.4MU3NG9T" - 
        "l.NYTQWDNK.DH8V0RVE" - 
        "l.NYTQWDNK.37RDZ3F9" - 
        "l.NQV67GAK.IY60ML3O" - 
        "l.NQV67GAK.UYR1ULBJ" - 
        "l.NQV67GAK.KUCXVEX5" - 
        "l.NQV67GAK.RII1A0WL" - 
        "l.NQV67GAK.DP940KC3" - 
        "l.2TKBJRZA.3S79PGAT" - 
        "l.2TKBJRZA.HHOZIESQ" - 
        "l.2TKBJRZA.AJGCEZBT" - 
        "l.2TKBJRZA.5JCK9WK4" - 
        "l.2TKBJRZA.QNFPBWIP" - 
        "l.2TKBJRZA.S4H60IWV" - 
        "l.2TKBJRZA.PGSJNCAK" - 
        "l.2TKBJRZA.8NG9NV1X" - 
        "l.2TKBJRZA.VKDV7CMP" - 
        "l.DSRKZWY1.703J2K3E" - 
        "l.DSRKZWY1.P6ZF6TSV" - 
        "l.DSRKZWY1.2SHR03C6" - 
        "l.DSRKZWY1.HCHXVCRK" - 
        "l.DSRKZWY1.SKFB1V2G" - 
        "l.DSRKZWY1.QCF4GQQG" - 
        "l.DSRKZWY1.R5B9MGRZ" - 
        "l.DSRKZWY1.V504CME5" - 
        "l.DSRKZWY1.KSPGTOA2" - 
        "l.DSRKZWY1.532KF35E" - 
        "l.DSRKZWY1.I5QNI44G" - 
        "l.DSRKZWY1.EOQAVGZD" - 
        "l.UGBN1NUG.2067RIMW" - 
        "l.UGBN1NUG.A0FY43BF" - 
        "l.UGBN1NUG.SL1FKTEG" - 
        "l.UGBN1NUG.FTFAQWNW" - 
        "l.UGBN1NUG.CN72ARYD" - 
        "l.UGBN1NUG.ES87JMS0" - 
        "l.UGBN1NUG.U5QWRKLK" - 
        "l.UGBN1NUG.DRJ7Q27I" - 
        "l.UGBN1NUG.A9UVC6B9" - 
        "l.B2RJ56CA.73W7P1G7" - 
        "l.B2RJ56CA.4NIE5C2E" - 
        "l.B2RJ56CA.5BR74SQK" - 
        "l.B2RJ56CA.L4QR4BQ4" - 
        "l.B2RJ56CA.YVJ9NOC8" - 
        "l.QA54EXG8.DICPAZRM" - 
        "l.QA54EXG8.Y8QW9JKA" - 
        "l.QA54EXG8.9A4NCVEP" - 
        "l.QA54EXG8.LQLIYWLV" - 
        "l.QA54EXG8.UTO16474" - 
        "l.QA54EXG8.QDU7E72K" - 
        "l.QA54EXG8.6EHU886B" - 
        "l.QA54EXG8.OTU5W6SF" - 
        "l.OCWYRYBR.JU8LRTW8" - 
        "l.OCWYRYBR.17UGQZLD" - 
        "l.OCWYRYBR.ZR6BJ9WM" - 
        "l.OCWYRYBR.CC0H3ZAD" - 
        "l.OCWYRYBR.IM7TDYOS" - 
        "l.OCWYRYBR.S7HY6T15" - 

    .Tildes
        "l.LVWHWCRA.Y6X17I9U" -> 
        "l.HBXDGN4P.VJXRDTV9" -> 
        "l.8WUDZBQM.W4R79R8G" -> 
        "l.LJV1Q4MY.LUMPHR49" -> 
        "l.ICW61ZPG.WJ76C7TO" -> 
        "l.GWXJ9EU0.HS0X0D3N" -> 
        "l.WAZBDHJW.NA44IY0I" -> 
        "l.I6L3CYB8.UT7Y2A7Z" -> 
        "l.XEJCDGUN.FM5DP46U" -> 
        "l.SY52SW9O.PO0OEWK6" -> 
        "l.FY60N5WI.6N5AIIEP" -> "l.FY60N5WI.someid", "l.FY60N5WI.someid2";
        "l.817R158N.UAYSVLNT" -> 
        "l.SUXDU7CR.F8ED956J" -> 
        "l.QYR27W3C.XYDW0VAS" -> 
        "l.4GVUK4G2.Z0FKZRMQ" -> 
        "l.RUOJBUN4.09HRE3C8" -> 
        "l.UTFH9D1Q.QSTZA5V4" -> 
        "l.4JRSOXJV.W88TJMOF" -> 
        "l.NYTQWDNK.RQ0IICXH" -> 
        "l.NQV67GAK.IY60ML3O" -> 
        "l.2TKBJRZA.3S79PGAT" -> 
        "l.DSRKZWY1.703J2K3E" -> 
        "l.DSRKZWY1.HCHXVCRK" -> 
        "l.DSRKZWY1.R5B9MGRZ" -> 
        "l.DSRKZWY1.532KF35E" -> 
        "l.UGBN1NUG.2067RIMW" -> 
        "l.UGBN1NUG.SL1FKTEG" -> 
        "l.UGBN1NUG.CN72ARYD" -> 
        "l.UGBN1NUG.U5QWRKLK" -> 
        "l.B2RJ56CA.73W7P1G7" -> 
        "l.QA54EXG8.DICPAZRM" -> 
        "l.QA54EXG8.9A4NCVEP" -> 
        "l.QA54EXG8.UTO16474" -> 
        "l.QA54EXG8.6EHU886B" -> 
        "l.OCWYRYBR.CC0H3ZAD" -> 
        "l.OCWYRYBR.ZR6BJ9WM" -> 
        "l.OCWYRYBR.17UGQZLD" -> 
        "l.OCWYRYBR.JU8LRTW8" -> 


    .ProdidFile
        "l.LVWHWCRA.Y6X17I9U" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.HBXDGN4P.VJXRDTV9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.8WUDZBQM.W4R79R8G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.LJV1Q4MY.LUMPHR49" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.ICW61ZPG.WJ76C7TO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.GWXJ9EU0.HS0X0D3N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.WAZBDHJW.NA44IY0I" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.I6L3CYB8.UT7Y2A7Z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.XEJCDGUN.FM5DP46U" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.SY52SW9O.PO0OEWK6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.FY60N5WI.6N5AIIEP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "l.817R158N.UAYSVLNT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.SUXDU7CR.F8ED956J" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.QYR27W3C.XYDW0VAS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.4GVUK4G2.Z0FKZRMQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.RUOJBUN4.09HRE3C8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.UTFH9D1Q.QSTZA5V4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.4JRSOXJV.W88TJMOF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.NYTQWDNK.RQ0IICXH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NQV67GAK.IY60ML3O" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.2TKBJRZA.3S79PGAT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.DSRKZWY1.703J2K3E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.HCHXVCRK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.R5B9MGRZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.532KF35E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.UGBN1NUG.2067RIMW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.SL1FKTEG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.CN72ARYD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.U5QWRKLK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.B2RJ56CA.73W7P1G7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.QA54EXG8.DICPAZRM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.9A4NCVEP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.UTO16474" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.6EHU886B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.OCWYRYBR.CC0H3ZAD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.ZR6BJ9WM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.17UGQZLD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.JU8LRTW8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"

    .ItemidFile
        "l.LVWHWCRA.Y6X17I9U" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.LVWHWCRA.0UJ53XA4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.LVWHWCRA.2AZS7GN6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.LVWHWCRA.0M7YTDER" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.LVWHWCRA.GJLBS73G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_control.ds"
        "l.HBXDGN4P.VJXRDTV9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.HBXDGN4P.4G3FA1DD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.HBXDGN4P.SGRGP6DW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.HBXDGN4P.N6UYYTUR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.HBXDGN4P.71TD2UFP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas1.ds"
        "l.8WUDZBQM.W4R79R8G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.8WUDZBQM.Z8UBWTE7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.8WUDZBQM.ZW6HBOE1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.8WUDZBQM.37MOSTM4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.8WUDZBQM.XH85TXZY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas2.ds"
        "l.LJV1Q4MY.LUMPHR49" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.LJV1Q4MY.SK54JBB0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.LJV1Q4MY.1R2S8958" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.LJV1Q4MY.9E0Y938M" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.LJV1Q4MY.M5RDZWG0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_inner_commas3.ds"
        "l.ICW61ZPG.WJ76C7TO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.ICW61ZPG.DOC6Y7J2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.ICW61ZPG.BKWZ8N2Y" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.ICW61ZPG.YM472NXC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.ICW61ZPG.GS53LW2Z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers1.ds"
        "l.GWXJ9EU0.HS0X0D3N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.GWXJ9EU0.EY5AEUZ6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.GWXJ9EU0.WJ4O8KTD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.GWXJ9EU0.G8X5LN18" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.GWXJ9EU0.XEQFHLYB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers2.ds"
        "l.WAZBDHJW.NA44IY0I" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.WAZBDHJW.NKMUUNZ7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.WAZBDHJW.BBDPHSZA" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.WAZBDHJW.0A7MGNZ8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.WAZBDHJW.BGDHGENA" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_producers3.ds"
        "l.I6L3CYB8.UT7Y2A7Z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.I6L3CYB8.UHI99WVR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.I6L3CYB8.SYNGKOEI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.I6L3CYB8.4HN0MWBK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.I6L3CYB8.KMKPLEQG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons1.ds"
        "l.XEJCDGUN.FM5DP46U" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.XEJCDGUN.5L5P14F1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.XEJCDGUN.UINBHO9N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.XEJCDGUN.GDARNFE6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.XEJCDGUN.71A8PS9L" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons2.ds"
        "l.SY52SW9O.PO0OEWK6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.SY52SW9O.VL4BWQOQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.SY52SW9O.ZTU474JM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.SY52SW9O.YDR5O4BZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.SY52SW9O.EGETWB94" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_semicolons3.ds"
        "l.FY60N5WI.6N5AIIEP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "l.FY60N5WI.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
            "l.FY60N5WI.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "l.FY60N5WI.someid2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "l.FY60N5WI.V5B13CEJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "l.817R158N.UAYSVLNT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.R8PD7R8X" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.G75G49CV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.D78ODN7Y" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.JWT48DVE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.T17S6YE2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.I4PK3ADG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.4BVVU2U5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.2Q5QNFUF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.XSFNZTWP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.P8K3Q80V" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.HOPJ11SX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.PAJAHVBN" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.D2Y4ILDL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.FIG6J2NL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.FLXZ36H9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.SYSHIR8L" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.CWPMKB5T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.EDDYVBC8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.817R158N.CT6H2WZH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_exotic_spaces.ds"
        "l.SUXDU7CR.F8ED956J" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.SUXDU7CR.TG2KSW6X" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.SUXDU7CR.F92JTDCS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.SUXDU7CR.IZROWYBR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.SUXDU7CR.DL96XGL1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_spaces.ds"
        "l.QYR27W3C.XYDW0VAS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.QYR27W3C.J5WZLA97" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.QYR27W3C.AIYR6H5F" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.QYR27W3C.JU7HQ9XL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.QYR27W3C.A073IWVI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.B_tabs.ds"
        "l.4GVUK4G2.Z0FKZRMQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.4GVUK4G2.P0H87IPT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.4GVUK4G2.HXBAH90N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.4GVUK4G2.3UATJ7SI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.4GVUK4G2.SYSSJADU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "l.RUOJBUN4.09HRE3C8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.RUOJBUN4.XIAM7N96" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.RUOJBUN4.4YVHIQ8S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.RUOJBUN4.FBXI0X8C" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.RUOJBUN4.QAVO7LUP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "l.UTFH9D1Q.QSTZA5V4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.UTFH9D1Q.0BVW1W8Z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.UTFH9D1Q.GG0VC7Q1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.UTFH9D1Q.KHG2TTX4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.UTFH9D1Q.IE67LXHU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_line_comment.ds"
        "l.4JRSOXJV.W88TJMOF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.4JRSOXJV.TFN2JEWI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.4JRSOXJV.YWP32A94" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.4JRSOXJV.URR301IG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.4JRSOXJV.X7191SJG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "l.NYTQWDNK.RQ0IICXH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NYTQWDNK.1W2ASL5L" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NYTQWDNK.4MU3NG9T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NYTQWDNK.DH8V0RVE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NYTQWDNK.37RDZ3F9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_line_comments.ds"
        "l.NQV67GAK.IY60ML3O" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.NQV67GAK.UYR1ULBJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.NQV67GAK.KUCXVEX5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.NQV67GAK.RII1A0WL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.NQV67GAK.DP940KC3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "l.2TKBJRZA.3S79PGAT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.HHOZIESQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.AJGCEZBT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.5JCK9WK4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.QNFPBWIP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.S4H60IWV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.PGSJNCAK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.8NG9NV1X" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.2TKBJRZA.VKDV7CMP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_commas.ds"
        "l.DSRKZWY1.703J2K3E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.P6ZF6TSV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.2SHR03C6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.HCHXVCRK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.SKFB1V2G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.QCF4GQQG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.R5B9MGRZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.V504CME5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.KSPGTOA2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.532KF35E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.I5QNI44G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.DSRKZWY1.EOQAVGZD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_producers.ds"
        "l.UGBN1NUG.2067RIMW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.A0FY43BF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.SL1FKTEG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.FTFAQWNW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.CN72ARYD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.ES87JMS0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.U5QWRKLK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.DRJ7Q27I" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.UGBN1NUG.A9UVC6B9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.D_semicolons.ds"
        "l.B2RJ56CA.73W7P1G7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.B2RJ56CA.4NIE5C2E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.B2RJ56CA.5BR74SQK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.B2RJ56CA.L4QR4BQ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.B2RJ56CA.YVJ9NOC8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_commas.ds"
        "l.QA54EXG8.DICPAZRM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.Y8QW9JKA" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.9A4NCVEP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.LQLIYWLV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.UTO16474" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.QDU7E72K" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.6EHU886B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.QA54EXG8.OTU5W6SF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "l.OCWYRYBR.JU8LRTW8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.17UGQZLD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.ZR6BJ9WM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.CC0H3ZAD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.IM7TDYOS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "l.OCWYRYBR.S7HY6T15" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"

