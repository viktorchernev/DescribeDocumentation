========================================
Source Code File Names (between the arrows)
========================================

🡆C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'Directory -> Unfold' operation...
"C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10"
STOP_ON_ERROR - False
PARSE_DS_ONLY - True
PARSE_TOP_DIRECTORY_ONLY - False
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
Fetched file contents - 83 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 83 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
Fetched file contents - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 84 characters, into 14 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
Fetched file contents - 88 characters long

Parsing sequence: T(DATA|'fabrics') T(COMMA|', ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(COMMA|', ') T(DATA|'fa') T(COMMA|',') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(COMMA|',') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 88 characters, into 20 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
Fetched file contents - 87 characters long

Parsing sequence: T(COMMA|',') T(DATA|'fabrics ') T(COMMA|',') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',,\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(COMMA|',') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 87 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
Fetched file contents - 85 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 85 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
Fetched file contents - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'fa') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 91 characters, into 23 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
Fetched file contents - 89 characters long

Parsing sequence: T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 89 characters, into 18 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
Fetched file contents - 84 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 84 characters, into 14 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
Fetched file contents - 87 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEMICOLON|'; ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEMICOLON|'; ') T(DATA|'fa') T(SEMICOLON|';') T(DATA|'brics') T(SEPARATOR|',\r\n\t') T(SEMICOLON|';') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 87 characters, into 19 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
Fetched file contents - 86 characters long

Parsing sequence: T(SEMICOLON|';') T(DATA|'fabrics ') T(SEMICOLON|';') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics') T(SEMICOLON|';') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 86 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
Fetched file contents - 118 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<someid>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<someid2> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<someid> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 118 characters, into 17 tokens.
Those were translated to 1 productions, containing 4 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
Fetched file contents - 736 characters long

Parsing sequence: T(DATA|'A vertical tab character (ASCII 11) ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'A form feed character (ASCII 12)') T(SEPARATOR|',\r\n\t') T(DATA|'A next line (NEL) character (Unicode character U+0085)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A non') T(HYPHEN|'-') T(DATA|'breaking space (Unicode character U+00A0)') T(SEPARATOR|', \r\n\t') T(DATA|'An ogham space mark (Unicode character U+1680)') T(SEPARATOR|', \r\n\t') T(DATA|'En Quad (U+2000)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Quad (U+2001)') T(SEPARATOR|', \r\n\t') T(DATA|'En Space (U+2002)') T(SEPARATOR|', \r\n\t') T(DATA|'Em Space (U+2003)') T(SEPARATOR|', \r\n\t') T(DATA|'Three') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2004)') T(SEPARATOR|', \r\n\t') T(DATA|'Four') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2005)') T(SEPARATOR|', \r\n\t') T(DATA|'Six') T(HYPHEN|'-') T(DATA|'Per') T(HYPHEN|'-') T(DATA|'Em Space (U+2006)') T(SEPARATOR|', \r\n\t') T(DATA|'Punctuation Space (U+2008)') T(SEPARATOR|', \r\n\t') T(DATA|'Thin Space (U+2009)') T(SEPARATOR|', \r\n\t') T(DATA|'Hair Space (U+200A)') T(SEPARATOR|', \r\n\t') T(DATA|'A paragraph separator (Unicode character U+2029)') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'A narrow no') T(HYPHEN|'-') T(DATA|'break space (Unicode character U+202F)') T(SEPARATOR|', \r\n\t') T(DATA|'A medium mathematical space (Unicode character U+205F)') T(SEPARATOR|', \r\n\t') T(DATA|'An ideographic space (Unicode character U+3000)') T(SEPARATOR|',　\r\n\t') T(DATA|'Figure Space') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 736 characters, into 58 tokens.
Those were translated to 1 productions, containing 20 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
Fetched file contents - 89 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> \r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',  \r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|', \r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; ') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 89 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
Fetched file contents - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\t\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t\t\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\t\t\t\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\t') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 91 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
Fetched file contents - 138 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /* comment *//* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment */') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 138 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
Fetched file contents - 184 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t  // comment\r\n ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';  /* comment */ /* comment */\t\r\n\t') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 184 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
Fetched file contents - 116 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 116 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
Fetched file contents - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment *//* comment */\r\n/* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /*comment*/\r\n\t/* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment *//* comment */') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 180 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
Fetched file contents - 156 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> // comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', // comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; // comment\r\n\t') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 156 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
Fetched file contents - 175 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>// comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';/* comment *//* comment */\r\n\t') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 175 characters, into 12 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
Fetched file contents - 91 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(SEPARATOR|',, ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(SEPARATOR|',,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 91 characters, into 20 tokens.
Those were translated to 1 productions, containing 9 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
Fetched file contents - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>>') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 180 characters, into 29 tokens.
Those were translated to 4 productions, containing 12 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
Fetched file contents - 100 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(TERMINATOR|';; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(TERMINATOR|';;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(TERMINATOR|';;') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 100 characters, into 23 tokens.
Those were translated to 4 productions, containing 9 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
Fetched file contents - 95 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_SEPARATOR|'\,') T(COMMA|',') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\,') T(COMMA|', ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\,') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(COMMA|',') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 95 characters, into 24 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
Fetched file contents - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(ESCAPE_HYPHEN|'\-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(ESCAPE_RIGHT_ARROW|'\> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(RIGHT_ARROW|'>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 193 characters, into 36 tokens.
Those were translated to 4 productions, containing 8 entries.
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
Fetched file contents - 112 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(SEMICOLON|'; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(SEMICOLON|';') T(ESCAPE_TERMINATOR|'\; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(ESCAPE_TERMINATOR|'\;') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "l.K2Z1W0S6.MSP2BNVL" 

    .Productions
        "l.K2Z1W0S6.MSP2BNVL" -> "l.K2Z1W0S6.I0R5BJCP", "l.K2Z1W0S6.W2J9NVMY", "l.K2Z1W0S6.6A927ZOQ", "l.K2Z1W0S6.EVY3NPME";
        "l.C9O28WW0.QODWC91L" -> "l.C9O28WW0.VYK9P43F", "l.C9O28WW0.3BWIBLFV", "l.C9O28WW0.YOG80CYN", "l.C9O28WW0.2B0NAKE5";
        "l.W6718SWF.JAHXOYLI" -> "l.W6718SWF.JB04Q29R", "l.W6718SWF.CBRBANCA", "l.W6718SWF.2QJ54B96", "l.W6718SWF.BVE1BY3H";
        "l.XM9LF5OZ.7QRXEBUE" -> "l.XM9LF5OZ.CJ42W4I1", "l.XM9LF5OZ.WLU78U6O", "l.XM9LF5OZ.4HT1T9FA", "l.XM9LF5OZ.9E45I711";
        "l.OLZ69I47.COHMBW34" -> "l.OLZ69I47.N5SXCE0Z", "l.OLZ69I47.7AZ4DCMS", "l.OLZ69I47.KEKHLSLV", "l.OLZ69I47.O49F21L3";
        "l.WZU8I23U.VHHZEYSV" -> "l.WZU8I23U.4SXPZGCX", "l.WZU8I23U.J07ZD4N1", "l.WZU8I23U.AZRHUANA", "l.WZU8I23U.F6X97IJX";
        "l.S6NGIB7S.BRM29X3W" -> "l.S6NGIB7S.A0E5DW2G", "l.S6NGIB7S.S0ZO8DN2", "l.S6NGIB7S.6WYG9GQL", "l.S6NGIB7S.8WJ383SC";
        "l.SJQA67JS.5YT27EKA" -> "l.SJQA67JS.ARX0A4HV", "l.SJQA67JS.R750F52P", "l.SJQA67JS.CW8JYV1Q", "l.SJQA67JS.G31L2K3L";
        "l.RO91YUUY.51WUHCW4" -> "l.RO91YUUY.3IR6QSDK", "l.RO91YUUY.OWO24GSX", "l.RO91YUUY.BPTEH9A2", "l.RO91YUUY.MTARCS4V";
        "l.2S4KA4AS.7ND38JYO" -> "l.2S4KA4AS.ZSA38TJJ", "l.2S4KA4AS.AZHVTHXK", "l.2S4KA4AS.2PZSYZSZ", "l.2S4KA4AS.GGMAH00E";
        "l.2SMBP6DQ.KAYW4LH0" -> "l.2SMBP6DQ.someid", "l.2SMBP6DQ.2DAVCMFP";
        "l.PKSPYSKP.HE4T17P2" -> 
            "l.PKSPYSKP.BWDIVFD1", "l.PKSPYSKP.MQHMLAIC", "l.PKSPYSKP.YSZHN0US", "l.PKSPYSKP.YWYGLMI1", "l.PKSPYSKP.EP6I36DV", "l.PKSPYSKP.KGVYH0HK", "l.PKSPYSKP.IKXM5J13", "l.PKSPYSKP.I364F40M", "l.PKSPYSKP.OOIB4UDI", "l.PKSPYSKP.XR59J084", 
            "l.PKSPYSKP.5PHL1PAS", "l.PKSPYSKP.8BGW5FHX", "l.PKSPYSKP.67EIQLPM", "l.PKSPYSKP.HND2JP9A", "l.PKSPYSKP.111YC4WO", "l.PKSPYSKP.7D00ZSKW", "l.PKSPYSKP.BK1H5FMD", "l.PKSPYSKP.IVPWS181", "l.PKSPYSKP.Y3IQ73VG";
        "l.6W50Y2S5.UAOENPXT" -> "l.6W50Y2S5.WQ3K25RR", "l.6W50Y2S5.SHTYCNDI", "l.6W50Y2S5.EQ2WE23S", "l.6W50Y2S5.W1VTVDIO";
        "l.IMLKL2V7.UPJDC7LS" -> "l.IMLKL2V7.ZWJK400L", "l.IMLKL2V7.0D0R9LXP", "l.IMLKL2V7.PSE3520M", "l.IMLKL2V7.EWB18B4A";
        "l.M0RADSR4.5LMDNH9E" -> "l.M0RADSR4.6TVTYIN1", "l.M0RADSR4.FX2H4SK8", "l.M0RADSR4.62YJK5N2", "l.M0RADSR4.NJY7S8Z5";
        "l.SMRXIU41.KR4MGCGR" -> "l.SMRXIU41.8XQ31W10", "l.SMRXIU41.5P1XF1CC", "l.SMRXIU41.KZBCN1TS", "l.SMRXIU41.MOFE3A6J";
        "l.W32YQORJ.EJUWS8XH" -> "l.W32YQORJ.O24UPG9S", "l.W32YQORJ.9T5QM6Y3", "l.W32YQORJ.TDNATKKT", "l.W32YQORJ.YSXDV3IZ";
        "l.FRVYRJCR.ZH08JERH" -> "l.FRVYRJCR.C93CJODW", "l.FRVYRJCR.E01PYT3F", "l.FRVYRJCR.5EJJ1S9L", "l.FRVYRJCR.XZW2M09Z";
        "l.AD5SSEWG.0RZQFNHQ" -> "l.AD5SSEWG.BLKMBIUJ", "l.AD5SSEWG.FENQT46C", "l.AD5SSEWG.D1TGO75K", "l.AD5SSEWG.MF5M2RTB";
        "l.IYPX75VY.PI2T4XTV" -> "l.IYPX75VY.FOOAS0OW", "l.IYPX75VY.ZJO9M2ZB", "l.IYPX75VY.WE3LGBRQ", "l.IYPX75VY.U8RJIFAY";
        "l.TRMN7BLP.3JC7WCL8" -> "l.TRMN7BLP.C6611GLP", "l.TRMN7BLP.LPHG3F98", "l.TRMN7BLP.MTX6T5V1", "l.TRMN7BLP.MGR11SW0", "l.TRMN7BLP.UOMWACI1", "l.TRMN7BLP.Z0K9BROB", "l.TRMN7BLP.FKSQTYI6", "l.TRMN7BLP.T9G4LZW7";
        "l.VTIZYN15.V2K0JF1L" -> "l.VTIZYN15.PJV28DVJ", "l.VTIZYN15.VEJH74XI";
        "l.VTIZYN15.DD64ZI86" -> "l.VTIZYN15.1D8EWNJB", "l.VTIZYN15.SI368JR1";
        "l.VTIZYN15.FIHL7CO1" -> "l.VTIZYN15.HNPIPMMT", "l.VTIZYN15.AM8GJ70F";
        "l.VTIZYN15.896JKIQR" -> "l.VTIZYN15.830JOU1U", "l.VTIZYN15.QVX0LFCP";
        "l.4NB5BK5S.J716TBCN" -> ".4NB5BK5S.E5842OGA";
        "l.4NB5BK5S.NUXVA6OO" -> ".4NB5BK5S.TUJPYVS3";
        "l.4NB5BK5S.PNCUJF7O" -> ".4NB5BK5S.7XIATXGR";
        "l.4NB5BK5S.88R66REU" -> "l.4NB5BK5S.I8UOTPUA", "l.4NB5BK5S.C9CX8ZAK";
        "l.YZLJYNKC.VT2JWK3D" -> "l.YZLJYNKC.URDC2K04", "l.YZLJYNKC.NW62SO6P", "l.YZLJYNKC.SMAY4FEZ", "l.YZLJYNKC.WWTH1F54";
        "l.RVL469SF.06EE48RC" -> ".RVL469SF.BWLQMT22";
        "l.RVL469SF.D3QQRNEN" -> ".RVL469SF.X5NJC4AQ";
        "l.RVL469SF.BMHXY8K6" -> ".RVL469SF.VU0JMFLE";
        "l.RVL469SF.B0TP8149" -> ".RVL469SF.PJBNZQBW";
        "l.2MI0R23I.9DTVWU9A" -> "l.2MI0R23I.VQCQ3CXI", "l.2MI0R23I.M4JTPG5A";
        "l.2MI0R23I.TKX2KHY7" -> "l.2MI0R23I.9DTVWU9A";
        "l.2MI0R23I.2CTB79GG" -> "l.2MI0R23I.TKX2KHY7";
        "l.2MI0R23I.H0N48QFF" -> "l.2MI0R23I.2CTB79GG";

    .Translations
        "l.K2Z1W0S6.MSP2BNVL" - "fabrics"
        "l.K2Z1W0S6.I0R5BJCP" - "wool fabrics"
        "l.K2Z1W0S6.W2J9NVMY" - "cotton fabrics"
        "l.K2Z1W0S6.6A927ZOQ" - "silk fabrics"
        "l.K2Z1W0S6.EVY3NPME" - "synthetic fabrics"
        "l.C9O28WW0.QODWC91L" - "fabrics"
        "l.C9O28WW0.VYK9P43F" - "wool, fabrics"
        "l.C9O28WW0.3BWIBLFV" - "cotton fabrics"
        "l.C9O28WW0.YOG80CYN" - "silk fabrics"
        "l.C9O28WW0.2B0NAKE5" - "synthetic fabrics"
        "l.W6718SWF.JAHXOYLI" - "fabrics,"
        "l.W6718SWF.JB04Q29R" - "wool, fabrics"
        "l.W6718SWF.CBRBANCA" - "cotton, fa,brics"
        "l.W6718SWF.2QJ54B96" - ",silk fabrics"
        "l.W6718SWF.BVE1BY3H" - "synthetic fabrics"
        "l.XM9LF5OZ.7QRXEBUE" - ",fabrics ,"
        "l.XM9LF5OZ.CJ42W4I1" - "wool fabrics"
        "l.XM9LF5OZ.WLU78U6O" - "cotton fabrics"
        "l.XM9LF5OZ.4HT1T9FA" - "silk fabrics"
        "l.XM9LF5OZ.9E45I711" - "synthetic fabrics,"
        "l.OLZ69I47.COHMBW34" - "fabrics"
        "l.OLZ69I47.N5SXCE0Z" - "wool-> fabrics"
        "l.OLZ69I47.7AZ4DCMS" - "cotton fabrics"
        "l.OLZ69I47.KEKHLSLV" - "silk fabrics"
        "l.OLZ69I47.O49F21L3" - "synthetic fabrics"
        "l.WZU8I23U.VHHZEYSV" - "fabrics"
        "l.WZU8I23U.4SXPZGCX" - "wool-> fabrics"
        "l.WZU8I23U.J07ZD4N1" - "cotton-> fa->brics"
        "l.WZU8I23U.AZRHUANA" - "->silk fabrics"
        "l.WZU8I23U.F6X97IJX" - "synthetic fabrics"
        "l.S6NGIB7S.BRM29X3W" - "->fabrics ->"
        "l.S6NGIB7S.A0E5DW2G" - "wool fabrics->"
        "l.S6NGIB7S.S0ZO8DN2" - "cotton fabrics"
        "l.S6NGIB7S.6WYG9GQL" - "silk fabrics"
        "l.S6NGIB7S.8WJ383SC" - "synthetic fabrics"
        "l.SJQA67JS.5YT27EKA" - "fabrics"
        "l.SJQA67JS.ARX0A4HV" - "wool; fabrics"
        "l.SJQA67JS.R750F52P" - "cotton fabrics"
        "l.SJQA67JS.CW8JYV1Q" - "silk fabrics"
        "l.SJQA67JS.G31L2K3L" - "synthetic fabrics"
        "l.RO91YUUY.51WUHCW4" - "fabrics"
        "l.RO91YUUY.3IR6QSDK" - "wool; fabrics"
        "l.RO91YUUY.OWO24GSX" - "cotton; fa;brics"
        "l.RO91YUUY.BPTEH9A2" - ";silk fabrics"
        "l.RO91YUUY.MTARCS4V" - "synthetic fabrics"
        "l.2S4KA4AS.7ND38JYO" - ";fabrics ;"
        "l.2S4KA4AS.ZSA38TJJ" - "wool fabrics;"
        "l.2S4KA4AS.AZHVTHXK" - "cotton fabrics"
        "l.2S4KA4AS.2PZSYZSZ" - "silk fabrics"
        "l.2S4KA4AS.GGMAH00E" - "synthetic fabrics"
        "l.2SMBP6DQ.KAYW4LH0" - "fabrics"
        "l.2SMBP6DQ.someid" - "silk fabrics"
        "l.2SMBP6DQ.someid2" - "cotton fabrics"
        "l.2SMBP6DQ.2DAVCMFP" - "synthetic fabrics"
        "l.PKSPYSKP.HE4T17P2" - "A vertical tab character (ASCII 11)"
        "l.PKSPYSKP.BWDIVFD1" - "A form feed character (ASCII 12)"
        "l.PKSPYSKP.MQHMLAIC" - "A next line (NEL) character (Unicode character U+0085)"
        "l.PKSPYSKP.YSZHN0US" - "A non-breaking space (Unicode character U+00A0)"
        "l.PKSPYSKP.YWYGLMI1" - "An ogham space mark (Unicode character U+1680)"
        "l.PKSPYSKP.EP6I36DV" - "En Quad (U+2000)"
        "l.PKSPYSKP.KGVYH0HK" - "Em Quad (U+2001)"
        "l.PKSPYSKP.IKXM5J13" - "En Space (U+2002)"
        "l.PKSPYSKP.I364F40M" - "Em Space (U+2003)"
        "l.PKSPYSKP.OOIB4UDI" - "Three-Per-Em Space (U+2004)"
        "l.PKSPYSKP.XR59J084" - "Four-Per-Em Space (U+2005)"
        "l.PKSPYSKP.5PHL1PAS" - "Six-Per-Em Space (U+2006)"
        "l.PKSPYSKP.8BGW5FHX" - "Punctuation Space (U+2008)"
        "l.PKSPYSKP.67EIQLPM" - "Thin Space (U+2009)"
        "l.PKSPYSKP.HND2JP9A" - "Hair Space (U+200A)"
        "l.PKSPYSKP.111YC4WO" - "A paragraph separator (Unicode character U+2029)"
        "l.PKSPYSKP.7D00ZSKW" - "A narrow no-break space (Unicode character U+202F)"
        "l.PKSPYSKP.BK1H5FMD" - "A medium mathematical space (Unicode character U+205F)"
        "l.PKSPYSKP.IVPWS181" - "An ideographic space (Unicode character U+3000)"
        "l.PKSPYSKP.Y3IQ73VG" - "Figure Space"
        "l.6W50Y2S5.UAOENPXT" - "fabrics"
        "l.6W50Y2S5.WQ3K25RR" - "wool fabrics"
        "l.6W50Y2S5.SHTYCNDI" - "cotton fabrics"
        "l.6W50Y2S5.EQ2WE23S" - "silk fabrics"
        "l.6W50Y2S5.W1VTVDIO" - "synthetic fabrics"
        "l.IMLKL2V7.UPJDC7LS" - "fabrics"
        "l.IMLKL2V7.ZWJK400L" - "wool fabrics"
        "l.IMLKL2V7.0D0R9LXP" - "cotton fabrics"
        "l.IMLKL2V7.PSE3520M" - "silk fabrics"
        "l.IMLKL2V7.EWB18B4A" - "synthetic fabrics"
        "l.M0RADSR4.5LMDNH9E" - "fabrics"
        "l.M0RADSR4.6TVTYIN1" - "wool fabrics"
        "l.M0RADSR4.FX2H4SK8" - "cotton fabrics"
        "l.M0RADSR4.62YJK5N2" - "silk fabrics"
        "l.M0RADSR4.NJY7S8Z5" - "synthetic fabrics"
        "l.SMRXIU41.KR4MGCGR" - "fabrics"
        "l.SMRXIU41.8XQ31W10" - "wool fabrics"
        "l.SMRXIU41.5P1XF1CC" - "cotton fabrics"
        "l.SMRXIU41.KZBCN1TS" - "silk fabrics"
        "l.SMRXIU41.MOFE3A6J" - "synthetic fabrics"
        "l.W32YQORJ.EJUWS8XH" - "fabrics"
        "l.W32YQORJ.O24UPG9S" - "wool fabrics"
        "l.W32YQORJ.9T5QM6Y3" - "cotton fabrics"
        "l.W32YQORJ.TDNATKKT" - "silk fabrics"
        "l.W32YQORJ.YSXDV3IZ" - "synthetic fabrics"
        "l.FRVYRJCR.ZH08JERH" - "fabrics"
        "l.FRVYRJCR.C93CJODW" - "wool fabrics"
        "l.FRVYRJCR.E01PYT3F" - "cotton fabrics"
        "l.FRVYRJCR.5EJJ1S9L" - "silk fabrics"
        "l.FRVYRJCR.XZW2M09Z" - "synthetic fabrics"
        "l.AD5SSEWG.0RZQFNHQ" - "fabrics"
        "l.AD5SSEWG.BLKMBIUJ" - "wool fabrics"
        "l.AD5SSEWG.FENQT46C" - "cotton fabrics"
        "l.AD5SSEWG.D1TGO75K" - "silk fabrics"
        "l.AD5SSEWG.MF5M2RTB" - "synthetic fabrics"
        "l.IYPX75VY.PI2T4XTV" - "fabrics"
        "l.IYPX75VY.FOOAS0OW" - "wool fabrics"
        "l.IYPX75VY.ZJO9M2ZB" - "cotton fabrics"
        "l.IYPX75VY.WE3LGBRQ" - "silk fabrics"
        "l.IYPX75VY.U8RJIFAY" - "synthetic fabrics"
        "l.TRMN7BLP.3JC7WCL8" - "fabrics"
        "l.TRMN7BLP.C6611GLP" - "wool"
        "l.TRMN7BLP.LPHG3F98" - "fabrics"
        "l.TRMN7BLP.MTX6T5V1" - "cotton"
        "l.TRMN7BLP.MGR11SW0" - "fabrics"
        "l.TRMN7BLP.UOMWACI1" - "silk"
        "l.TRMN7BLP.Z0K9BROB" - "fabrics"
        "l.TRMN7BLP.FKSQTYI6" - "synthetic"
        "l.TRMN7BLP.T9G4LZW7" - "fabrics"
        "l.VTIZYN15.V2K0JF1L" - "fabrics"
        "l.VTIZYN15.PJV28DVJ" - "wool fabrics"
        "l.VTIZYN15.VEJH74XI" - "synthetic fabrics"
        "l.VTIZYN15.DD64ZI86" - "fabrics"
        "l.VTIZYN15.1D8EWNJB" - "wool fabrics"
        "l.VTIZYN15.SI368JR1" - "cotton fabrics"
        "l.VTIZYN15.FIHL7CO1" - "fabrics"
        "l.VTIZYN15.HNPIPMMT" - "wool fabrics"
        "l.VTIZYN15.AM8GJ70F" - "silk fabrics"
        "l.VTIZYN15.896JKIQR" - "fabrics"
        "l.VTIZYN15.830JOU1U" - "wool fabrics"
        "l.VTIZYN15.QVX0LFCP" - "other fabrics"
        "l.4NB5BK5S.J716TBCN" - "fabrics"
        "l.4NB5BK5S.E5842OGA" - "wool"
        "l.4NB5BK5S.NUXVA6OO" - "fabrics"
        "l.4NB5BK5S.TUJPYVS3" - "cotton"
        "l.4NB5BK5S.PNCUJF7O" - "fabrics"
        "l.4NB5BK5S.7XIATXGR" - "silk"
        "l.4NB5BK5S.88R66REU" - "fabrics"
        "l.4NB5BK5S.I8UOTPUA" - "synthetic"
        "l.4NB5BK5S.C9CX8ZAK" - "fabrics"
        "l.YZLJYNKC.VT2JWK3D" - "fabrics"
        "l.YZLJYNKC.URDC2K04" - "wool\,,fabrics"
        "l.YZLJYNKC.NW62SO6P" - "cotton\,, fabrics"
        "l.YZLJYNKC.SMAY4FEZ" - "silk ,\,fabrics"
        "l.YZLJYNKC.WWTH1F54" - "synthetic ,\, fabrics"
        "l.RVL469SF.06EE48RC" - "fabrics \->> wool fabrics"
        "l.RVL469SF.BWLQMT22" - "synthetic fabrics"
        "l.RVL469SF.D3QQRNEN" - "fabrics->\> wool fabrics"
        "l.RVL469SF.X5NJC4AQ" - "cotton fabrics"
        "l.RVL469SF.BMHXY8K6" - "fabrics -\>>wool fabrics"
        "l.RVL469SF.VU0JMFLE" - "silk fabrics"
        "l.RVL469SF.B0TP8149" - "fabrics-\>\>wool fabrics"
        "l.RVL469SF.PJBNZQBW" - "other fabrics"
        "l.2MI0R23I.H0N48QFF" - "fabrics"
        "l.2MI0R23I.2CTB79GG" - "wool\;; fabrics"
        "l.2MI0R23I.TKX2KHY7" - "cotton ;\; fabrics"
        "l.2MI0R23I.9DTVWU9A" - "silk \;\;fabrics"
        "l.2MI0R23I.VQCQ3CXI" - "synthetic"
        "l.2MI0R23I.M4JTPG5A" - "fabrics\;"

    .Links
        "l.K2Z1W0S6.MSP2BNVL" - 
        "l.K2Z1W0S6.I0R5BJCP" - 
        "l.K2Z1W0S6.W2J9NVMY" - 
        "l.K2Z1W0S6.6A927ZOQ" - 
        "l.K2Z1W0S6.EVY3NPME" - 
        "l.C9O28WW0.QODWC91L" - 
        "l.C9O28WW0.VYK9P43F" - 
        "l.C9O28WW0.3BWIBLFV" - 
        "l.C9O28WW0.YOG80CYN" - 
        "l.C9O28WW0.2B0NAKE5" - 
        "l.W6718SWF.JAHXOYLI" - 
        "l.W6718SWF.JB04Q29R" - 
        "l.W6718SWF.CBRBANCA" - 
        "l.W6718SWF.2QJ54B96" - 
        "l.W6718SWF.BVE1BY3H" - 
        "l.XM9LF5OZ.7QRXEBUE" - 
        "l.XM9LF5OZ.CJ42W4I1" - 
        "l.XM9LF5OZ.WLU78U6O" - 
        "l.XM9LF5OZ.4HT1T9FA" - 
        "l.XM9LF5OZ.9E45I711" - 
        "l.OLZ69I47.COHMBW34" - 
        "l.OLZ69I47.N5SXCE0Z" - 
        "l.OLZ69I47.7AZ4DCMS" - 
        "l.OLZ69I47.KEKHLSLV" - 
        "l.OLZ69I47.O49F21L3" - 
        "l.WZU8I23U.VHHZEYSV" - 
        "l.WZU8I23U.4SXPZGCX" - 
        "l.WZU8I23U.J07ZD4N1" - 
        "l.WZU8I23U.AZRHUANA" - 
        "l.WZU8I23U.F6X97IJX" - 
        "l.S6NGIB7S.BRM29X3W" - 
        "l.S6NGIB7S.A0E5DW2G" - 
        "l.S6NGIB7S.S0ZO8DN2" - 
        "l.S6NGIB7S.6WYG9GQL" - 
        "l.S6NGIB7S.8WJ383SC" - 
        "l.SJQA67JS.5YT27EKA" - 
        "l.SJQA67JS.ARX0A4HV" - 
        "l.SJQA67JS.R750F52P" - 
        "l.SJQA67JS.CW8JYV1Q" - 
        "l.SJQA67JS.G31L2K3L" - 
        "l.RO91YUUY.51WUHCW4" - 
        "l.RO91YUUY.3IR6QSDK" - 
        "l.RO91YUUY.OWO24GSX" - 
        "l.RO91YUUY.BPTEH9A2" - 
        "l.RO91YUUY.MTARCS4V" - 
        "l.2S4KA4AS.7ND38JYO" - 
        "l.2S4KA4AS.ZSA38TJJ" - 
        "l.2S4KA4AS.AZHVTHXK" - 
        "l.2S4KA4AS.2PZSYZSZ" - 
        "l.2S4KA4AS.GGMAH00E" - 
        "l.2SMBP6DQ.KAYW4LH0" - 
        "l.2SMBP6DQ.someid" - 
        "l.2SMBP6DQ.someid2" - 
        "l.2SMBP6DQ.2DAVCMFP" - 
        "l.PKSPYSKP.HE4T17P2" - 
        "l.PKSPYSKP.BWDIVFD1" - 
        "l.PKSPYSKP.MQHMLAIC" - 
        "l.PKSPYSKP.YSZHN0US" - 
        "l.PKSPYSKP.YWYGLMI1" - 
        "l.PKSPYSKP.EP6I36DV" - 
        "l.PKSPYSKP.KGVYH0HK" - 
        "l.PKSPYSKP.IKXM5J13" - 
        "l.PKSPYSKP.I364F40M" - 
        "l.PKSPYSKP.OOIB4UDI" - 
        "l.PKSPYSKP.XR59J084" - 
        "l.PKSPYSKP.5PHL1PAS" - 
        "l.PKSPYSKP.8BGW5FHX" - 
        "l.PKSPYSKP.67EIQLPM" - 
        "l.PKSPYSKP.HND2JP9A" - 
        "l.PKSPYSKP.111YC4WO" - 
        "l.PKSPYSKP.7D00ZSKW" - 
        "l.PKSPYSKP.BK1H5FMD" - 
        "l.PKSPYSKP.IVPWS181" - 
        "l.PKSPYSKP.Y3IQ73VG" - 
        "l.6W50Y2S5.UAOENPXT" - 
        "l.6W50Y2S5.WQ3K25RR" - 
        "l.6W50Y2S5.SHTYCNDI" - 
        "l.6W50Y2S5.EQ2WE23S" - 
        "l.6W50Y2S5.W1VTVDIO" - 
        "l.IMLKL2V7.UPJDC7LS" - 
        "l.IMLKL2V7.ZWJK400L" - 
        "l.IMLKL2V7.0D0R9LXP" - 
        "l.IMLKL2V7.PSE3520M" - 
        "l.IMLKL2V7.EWB18B4A" - 
        "l.M0RADSR4.5LMDNH9E" - 
        "l.M0RADSR4.6TVTYIN1" - 
        "l.M0RADSR4.FX2H4SK8" - 
        "l.M0RADSR4.62YJK5N2" - 
        "l.M0RADSR4.NJY7S8Z5" - 
        "l.SMRXIU41.KR4MGCGR" - 
        "l.SMRXIU41.8XQ31W10" - 
        "l.SMRXIU41.5P1XF1CC" - 
        "l.SMRXIU41.KZBCN1TS" - 
        "l.SMRXIU41.MOFE3A6J" - 
        "l.W32YQORJ.EJUWS8XH" - 
        "l.W32YQORJ.O24UPG9S" - 
        "l.W32YQORJ.9T5QM6Y3" - 
        "l.W32YQORJ.TDNATKKT" - 
        "l.W32YQORJ.YSXDV3IZ" - 
        "l.FRVYRJCR.ZH08JERH" - 
        "l.FRVYRJCR.C93CJODW" - 
        "l.FRVYRJCR.E01PYT3F" - 
        "l.FRVYRJCR.5EJJ1S9L" - 
        "l.FRVYRJCR.XZW2M09Z" - 
        "l.AD5SSEWG.0RZQFNHQ" - 
        "l.AD5SSEWG.BLKMBIUJ" - 
        "l.AD5SSEWG.FENQT46C" - 
        "l.AD5SSEWG.D1TGO75K" - 
        "l.AD5SSEWG.MF5M2RTB" - 
        "l.IYPX75VY.PI2T4XTV" - 
        "l.IYPX75VY.FOOAS0OW" - 
        "l.IYPX75VY.ZJO9M2ZB" - 
        "l.IYPX75VY.WE3LGBRQ" - 
        "l.IYPX75VY.U8RJIFAY" - 
        "l.TRMN7BLP.3JC7WCL8" - 
        "l.TRMN7BLP.C6611GLP" - 
        "l.TRMN7BLP.LPHG3F98" - 
        "l.TRMN7BLP.MTX6T5V1" - 
        "l.TRMN7BLP.MGR11SW0" - 
        "l.TRMN7BLP.UOMWACI1" - 
        "l.TRMN7BLP.Z0K9BROB" - 
        "l.TRMN7BLP.FKSQTYI6" - 
        "l.TRMN7BLP.T9G4LZW7" - 
        "l.VTIZYN15.V2K0JF1L" - 
        "l.VTIZYN15.PJV28DVJ" - 
        "l.VTIZYN15.VEJH74XI" - 
        "l.VTIZYN15.DD64ZI86" - 
        "l.VTIZYN15.1D8EWNJB" - 
        "l.VTIZYN15.SI368JR1" - 
        "l.VTIZYN15.FIHL7CO1" - 
        "l.VTIZYN15.HNPIPMMT" - 
        "l.VTIZYN15.AM8GJ70F" - 
        "l.VTIZYN15.896JKIQR" - 
        "l.VTIZYN15.830JOU1U" - 
        "l.VTIZYN15.QVX0LFCP" - 
        "l.4NB5BK5S.J716TBCN" - 
        "l.4NB5BK5S.E5842OGA" - 
        "l.4NB5BK5S.NUXVA6OO" - 
        "l.4NB5BK5S.TUJPYVS3" - 
        "l.4NB5BK5S.PNCUJF7O" - 
        "l.4NB5BK5S.7XIATXGR" - 
        "l.4NB5BK5S.88R66REU" - 
        "l.4NB5BK5S.I8UOTPUA" - 
        "l.4NB5BK5S.C9CX8ZAK" - 
        "l.YZLJYNKC.VT2JWK3D" - 
        "l.YZLJYNKC.URDC2K04" - 
        "l.YZLJYNKC.NW62SO6P" - 
        "l.YZLJYNKC.SMAY4FEZ" - 
        "l.YZLJYNKC.WWTH1F54" - 
        "l.RVL469SF.06EE48RC" - 
        "l.RVL469SF.BWLQMT22" - 
        "l.RVL469SF.D3QQRNEN" - 
        "l.RVL469SF.X5NJC4AQ" - 
        "l.RVL469SF.BMHXY8K6" - 
        "l.RVL469SF.VU0JMFLE" - 
        "l.RVL469SF.B0TP8149" - 
        "l.RVL469SF.PJBNZQBW" - 
        "l.2MI0R23I.H0N48QFF" - 
        "l.2MI0R23I.2CTB79GG" - 
        "l.2MI0R23I.TKX2KHY7" - 
        "l.2MI0R23I.9DTVWU9A" - 
        "l.2MI0R23I.VQCQ3CXI" - 
        "l.2MI0R23I.M4JTPG5A" - 

    .Decorators
        "l.K2Z1W0S6.MSP2BNVL" - 
        "l.K2Z1W0S6.I0R5BJCP" - 
        "l.K2Z1W0S6.W2J9NVMY" - 
        "l.K2Z1W0S6.6A927ZOQ" - 
        "l.K2Z1W0S6.EVY3NPME" - 
        "l.C9O28WW0.QODWC91L" - 
        "l.C9O28WW0.VYK9P43F" - 
        "l.C9O28WW0.3BWIBLFV" - 
        "l.C9O28WW0.YOG80CYN" - 
        "l.C9O28WW0.2B0NAKE5" - 
        "l.W6718SWF.JAHXOYLI" - 
        "l.W6718SWF.JB04Q29R" - 
        "l.W6718SWF.CBRBANCA" - 
        "l.W6718SWF.2QJ54B96" - 
        "l.W6718SWF.BVE1BY3H" - 
        "l.XM9LF5OZ.7QRXEBUE" - 
        "l.XM9LF5OZ.CJ42W4I1" - 
        "l.XM9LF5OZ.WLU78U6O" - 
        "l.XM9LF5OZ.4HT1T9FA" - 
        "l.XM9LF5OZ.9E45I711" - 
        "l.OLZ69I47.COHMBW34" - 
        "l.OLZ69I47.N5SXCE0Z" - 
        "l.OLZ69I47.7AZ4DCMS" - 
        "l.OLZ69I47.KEKHLSLV" - 
        "l.OLZ69I47.O49F21L3" - 
        "l.WZU8I23U.VHHZEYSV" - 
        "l.WZU8I23U.4SXPZGCX" - 
        "l.WZU8I23U.J07ZD4N1" - 
        "l.WZU8I23U.AZRHUANA" - 
        "l.WZU8I23U.F6X97IJX" - 
        "l.S6NGIB7S.BRM29X3W" - 
        "l.S6NGIB7S.A0E5DW2G" - 
        "l.S6NGIB7S.S0ZO8DN2" - 
        "l.S6NGIB7S.6WYG9GQL" - 
        "l.S6NGIB7S.8WJ383SC" - 
        "l.SJQA67JS.5YT27EKA" - 
        "l.SJQA67JS.ARX0A4HV" - 
        "l.SJQA67JS.R750F52P" - 
        "l.SJQA67JS.CW8JYV1Q" - 
        "l.SJQA67JS.G31L2K3L" - 
        "l.RO91YUUY.51WUHCW4" - 
        "l.RO91YUUY.3IR6QSDK" - 
        "l.RO91YUUY.OWO24GSX" - 
        "l.RO91YUUY.BPTEH9A2" - 
        "l.RO91YUUY.MTARCS4V" - 
        "l.2S4KA4AS.7ND38JYO" - 
        "l.2S4KA4AS.ZSA38TJJ" - 
        "l.2S4KA4AS.AZHVTHXK" - 
        "l.2S4KA4AS.2PZSYZSZ" - 
        "l.2S4KA4AS.GGMAH00E" - 
        "l.2SMBP6DQ.KAYW4LH0" - 
        "l.2SMBP6DQ.someid" - 
        "l.2SMBP6DQ.someid2" - 
        "l.2SMBP6DQ.2DAVCMFP" - 
        "l.PKSPYSKP.HE4T17P2" - 
        "l.PKSPYSKP.BWDIVFD1" - 
        "l.PKSPYSKP.MQHMLAIC" - 
        "l.PKSPYSKP.YSZHN0US" - 
        "l.PKSPYSKP.YWYGLMI1" - 
        "l.PKSPYSKP.EP6I36DV" - 
        "l.PKSPYSKP.KGVYH0HK" - 
        "l.PKSPYSKP.IKXM5J13" - 
        "l.PKSPYSKP.I364F40M" - 
        "l.PKSPYSKP.OOIB4UDI" - 
        "l.PKSPYSKP.XR59J084" - 
        "l.PKSPYSKP.5PHL1PAS" - 
        "l.PKSPYSKP.8BGW5FHX" - 
        "l.PKSPYSKP.67EIQLPM" - 
        "l.PKSPYSKP.HND2JP9A" - 
        "l.PKSPYSKP.111YC4WO" - 
        "l.PKSPYSKP.7D00ZSKW" - 
        "l.PKSPYSKP.BK1H5FMD" - 
        "l.PKSPYSKP.IVPWS181" - 
        "l.PKSPYSKP.Y3IQ73VG" - 
        "l.6W50Y2S5.UAOENPXT" - 
        "l.6W50Y2S5.WQ3K25RR" - 
        "l.6W50Y2S5.SHTYCNDI" - 
        "l.6W50Y2S5.EQ2WE23S" - 
        "l.6W50Y2S5.W1VTVDIO" - 
        "l.IMLKL2V7.UPJDC7LS" - 
        "l.IMLKL2V7.ZWJK400L" - 
        "l.IMLKL2V7.0D0R9LXP" - 
        "l.IMLKL2V7.PSE3520M" - 
        "l.IMLKL2V7.EWB18B4A" - 
        "l.M0RADSR4.5LMDNH9E" - 
        "l.M0RADSR4.6TVTYIN1" - 
        "l.M0RADSR4.FX2H4SK8" - 
        "l.M0RADSR4.62YJK5N2" - 
        "l.M0RADSR4.NJY7S8Z5" - 
        "l.SMRXIU41.KR4MGCGR" - 
        "l.SMRXIU41.8XQ31W10" - 
        "l.SMRXIU41.5P1XF1CC" - 
        "l.SMRXIU41.KZBCN1TS" - 
        "l.SMRXIU41.MOFE3A6J" - 
        "l.W32YQORJ.EJUWS8XH" - 
        "l.W32YQORJ.O24UPG9S" - 
        "l.W32YQORJ.9T5QM6Y3" - 
        "l.W32YQORJ.TDNATKKT" - 
        "l.W32YQORJ.YSXDV3IZ" - 
        "l.FRVYRJCR.ZH08JERH" - 
        "l.FRVYRJCR.C93CJODW" - 
        "l.FRVYRJCR.E01PYT3F" - 
        "l.FRVYRJCR.5EJJ1S9L" - 
        "l.FRVYRJCR.XZW2M09Z" - 
        "l.AD5SSEWG.0RZQFNHQ" - 
        "l.AD5SSEWG.BLKMBIUJ" - 
        "l.AD5SSEWG.FENQT46C" - 
        "l.AD5SSEWG.D1TGO75K" - 
        "l.AD5SSEWG.MF5M2RTB" - 
        "l.IYPX75VY.PI2T4XTV" - 
        "l.IYPX75VY.FOOAS0OW" - 
        "l.IYPX75VY.ZJO9M2ZB" - 
        "l.IYPX75VY.WE3LGBRQ" - 
        "l.IYPX75VY.U8RJIFAY" - 
        "l.TRMN7BLP.3JC7WCL8" - 
        "l.TRMN7BLP.C6611GLP" - 
        "l.TRMN7BLP.LPHG3F98" - 
        "l.TRMN7BLP.MTX6T5V1" - 
        "l.TRMN7BLP.MGR11SW0" - 
        "l.TRMN7BLP.UOMWACI1" - 
        "l.TRMN7BLP.Z0K9BROB" - 
        "l.TRMN7BLP.FKSQTYI6" - 
        "l.TRMN7BLP.T9G4LZW7" - 
        "l.VTIZYN15.V2K0JF1L" - 
        "l.VTIZYN15.PJV28DVJ" - 
        "l.VTIZYN15.VEJH74XI" - 
        "l.VTIZYN15.DD64ZI86" - 
        "l.VTIZYN15.1D8EWNJB" - 
        "l.VTIZYN15.SI368JR1" - 
        "l.VTIZYN15.FIHL7CO1" - 
        "l.VTIZYN15.HNPIPMMT" - 
        "l.VTIZYN15.AM8GJ70F" - 
        "l.VTIZYN15.896JKIQR" - 
        "l.VTIZYN15.830JOU1U" - 
        "l.VTIZYN15.QVX0LFCP" - 
        "l.4NB5BK5S.J716TBCN" - 
        "l.4NB5BK5S.E5842OGA" - 
        "l.4NB5BK5S.NUXVA6OO" - 
        "l.4NB5BK5S.TUJPYVS3" - 
        "l.4NB5BK5S.PNCUJF7O" - 
        "l.4NB5BK5S.7XIATXGR" - 
        "l.4NB5BK5S.88R66REU" - 
        "l.4NB5BK5S.I8UOTPUA" - 
        "l.4NB5BK5S.C9CX8ZAK" - 
        "l.YZLJYNKC.VT2JWK3D" - 
        "l.YZLJYNKC.URDC2K04" - 
        "l.YZLJYNKC.NW62SO6P" - 
        "l.YZLJYNKC.SMAY4FEZ" - 
        "l.YZLJYNKC.WWTH1F54" - 
        "l.RVL469SF.06EE48RC" - 
        "l.RVL469SF.BWLQMT22" - 
        "l.RVL469SF.D3QQRNEN" - 
        "l.RVL469SF.X5NJC4AQ" - 
        "l.RVL469SF.BMHXY8K6" - 
        "l.RVL469SF.VU0JMFLE" - 
        "l.RVL469SF.B0TP8149" - 
        "l.RVL469SF.PJBNZQBW" - 
        "l.2MI0R23I.H0N48QFF" - 
        "l.2MI0R23I.2CTB79GG" - 
        "l.2MI0R23I.TKX2KHY7" - 
        "l.2MI0R23I.9DTVWU9A" - 
        "l.2MI0R23I.VQCQ3CXI" - 
        "l.2MI0R23I.M4JTPG5A" - 

    .Tildes
        "l.K2Z1W0S6.MSP2BNVL" -> 
        "l.C9O28WW0.QODWC91L" -> 
        "l.W6718SWF.JAHXOYLI" -> 
        "l.XM9LF5OZ.7QRXEBUE" -> 
        "l.OLZ69I47.COHMBW34" -> 
        "l.WZU8I23U.VHHZEYSV" -> 
        "l.S6NGIB7S.BRM29X3W" -> 
        "l.SJQA67JS.5YT27EKA" -> 
        "l.RO91YUUY.51WUHCW4" -> 
        "l.2S4KA4AS.7ND38JYO" -> 
        "l.2SMBP6DQ.KAYW4LH0" -> "l.2SMBP6DQ.someid", "l.2SMBP6DQ.someid2";
        "l.PKSPYSKP.HE4T17P2" -> 
        "l.6W50Y2S5.UAOENPXT" -> 
        "l.IMLKL2V7.UPJDC7LS" -> 
        "l.M0RADSR4.5LMDNH9E" -> 
        "l.SMRXIU41.KR4MGCGR" -> 
        "l.W32YQORJ.EJUWS8XH" -> 
        "l.FRVYRJCR.ZH08JERH" -> 
        "l.AD5SSEWG.0RZQFNHQ" -> 
        "l.IYPX75VY.PI2T4XTV" -> 
        "l.TRMN7BLP.3JC7WCL8" -> 
        "l.VTIZYN15.V2K0JF1L" -> 
        "l.VTIZYN15.DD64ZI86" -> 
        "l.VTIZYN15.FIHL7CO1" -> 
        "l.VTIZYN15.896JKIQR" -> 
        "l.4NB5BK5S.J716TBCN" -> 
        "l.4NB5BK5S.NUXVA6OO" -> 
        "l.4NB5BK5S.PNCUJF7O" -> 
        "l.4NB5BK5S.88R66REU" -> 
        "l.YZLJYNKC.VT2JWK3D" -> 
        "l.RVL469SF.06EE48RC" -> 
        "l.RVL469SF.D3QQRNEN" -> 
        "l.RVL469SF.BMHXY8K6" -> 
        "l.RVL469SF.B0TP8149" -> 
        "l.2MI0R23I.9DTVWU9A" -> 
        "l.2MI0R23I.TKX2KHY7" -> 
        "l.2MI0R23I.2CTB79GG" -> 
        "l.2MI0R23I.H0N48QFF" -> 


    .ProdidFile
        "l.K2Z1W0S6.MSP2BNVL" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.C9O28WW0.QODWC91L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.W6718SWF.JAHXOYLI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.XM9LF5OZ.7QRXEBUE" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.OLZ69I47.COHMBW34" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.WZU8I23U.VHHZEYSV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.S6NGIB7S.BRM29X3W" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.SJQA67JS.5YT27EKA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.RO91YUUY.51WUHCW4" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.2S4KA4AS.7ND38JYO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2SMBP6DQ.KAYW4LH0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "l.PKSPYSKP.HE4T17P2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.6W50Y2S5.UAOENPXT" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.IMLKL2V7.UPJDC7LS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.M0RADSR4.5LMDNH9E" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.SMRXIU41.KR4MGCGR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.W32YQORJ.EJUWS8XH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.FRVYRJCR.ZH08JERH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.AD5SSEWG.0RZQFNHQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.IYPX75VY.PI2T4XTV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.TRMN7BLP.3JC7WCL8" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.VTIZYN15.V2K0JF1L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.DD64ZI86" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.FIHL7CO1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.896JKIQR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.4NB5BK5S.J716TBCN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.NUXVA6OO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.PNCUJF7O" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.88R66REU" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.YZLJYNKC.VT2JWK3D" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.RVL469SF.06EE48RC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.D3QQRNEN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.BMHXY8K6" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.B0TP8149" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.2MI0R23I.9DTVWU9A" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.TKX2KHY7" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.2CTB79GG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.H0N48QFF" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"

    .ItemidFile
        "l.K2Z1W0S6.MSP2BNVL" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.K2Z1W0S6.I0R5BJCP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.K2Z1W0S6.W2J9NVMY" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.K2Z1W0S6.6A927ZOQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.K2Z1W0S6.EVY3NPME" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_control.ds"
        "l.C9O28WW0.QODWC91L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.C9O28WW0.VYK9P43F" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.C9O28WW0.3BWIBLFV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.C9O28WW0.YOG80CYN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.C9O28WW0.2B0NAKE5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas1.ds"
        "l.W6718SWF.JAHXOYLI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.W6718SWF.JB04Q29R" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.W6718SWF.CBRBANCA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.W6718SWF.2QJ54B96" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.W6718SWF.BVE1BY3H" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas2.ds"
        "l.XM9LF5OZ.7QRXEBUE" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.XM9LF5OZ.CJ42W4I1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.XM9LF5OZ.WLU78U6O" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.XM9LF5OZ.4HT1T9FA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.XM9LF5OZ.9E45I711" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_inner_commas3.ds"
        "l.OLZ69I47.COHMBW34" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.OLZ69I47.N5SXCE0Z" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.OLZ69I47.7AZ4DCMS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.OLZ69I47.KEKHLSLV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.OLZ69I47.O49F21L3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers1.ds"
        "l.WZU8I23U.VHHZEYSV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.WZU8I23U.4SXPZGCX" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.WZU8I23U.J07ZD4N1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.WZU8I23U.AZRHUANA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.WZU8I23U.F6X97IJX" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers2.ds"
        "l.S6NGIB7S.BRM29X3W" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.S6NGIB7S.A0E5DW2G" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.S6NGIB7S.S0ZO8DN2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.S6NGIB7S.6WYG9GQL" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.S6NGIB7S.8WJ383SC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_producers3.ds"
        "l.SJQA67JS.5YT27EKA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.SJQA67JS.ARX0A4HV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.SJQA67JS.R750F52P" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.SJQA67JS.CW8JYV1Q" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.SJQA67JS.G31L2K3L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons1.ds"
        "l.RO91YUUY.51WUHCW4" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.RO91YUUY.3IR6QSDK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.RO91YUUY.OWO24GSX" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.RO91YUUY.BPTEH9A2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.RO91YUUY.MTARCS4V" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons2.ds"
        "l.2S4KA4AS.7ND38JYO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2S4KA4AS.ZSA38TJJ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2S4KA4AS.AZHVTHXK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2S4KA4AS.2PZSYZSZ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2S4KA4AS.GGMAH00E" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_semicolons3.ds"
        "l.2SMBP6DQ.KAYW4LH0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "l.2SMBP6DQ.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
            "l.2SMBP6DQ.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "l.2SMBP6DQ.someid2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "l.2SMBP6DQ.2DAVCMFP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "l.PKSPYSKP.HE4T17P2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.BWDIVFD1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.MQHMLAIC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.YSZHN0US" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.YWYGLMI1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.EP6I36DV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.KGVYH0HK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.IKXM5J13" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.I364F40M" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.OOIB4UDI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.XR59J084" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.5PHL1PAS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.8BGW5FHX" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.67EIQLPM" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.HND2JP9A" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.111YC4WO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.7D00ZSKW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.BK1H5FMD" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.IVPWS181" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.PKSPYSKP.Y3IQ73VG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_exotic_spaces.ds"
        "l.6W50Y2S5.UAOENPXT" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.6W50Y2S5.WQ3K25RR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.6W50Y2S5.SHTYCNDI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.6W50Y2S5.EQ2WE23S" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.6W50Y2S5.W1VTVDIO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_spaces.ds"
        "l.IMLKL2V7.UPJDC7LS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.IMLKL2V7.ZWJK400L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.IMLKL2V7.0D0R9LXP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.IMLKL2V7.PSE3520M" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.IMLKL2V7.EWB18B4A" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\B_tabs.ds"
        "l.M0RADSR4.5LMDNH9E" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.M0RADSR4.6TVTYIN1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.M0RADSR4.FX2H4SK8" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.M0RADSR4.62YJK5N2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.M0RADSR4.NJY7S8Z5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_block_comment.ds"
        "l.SMRXIU41.KR4MGCGR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.SMRXIU41.8XQ31W10" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.SMRXIU41.5P1XF1CC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.SMRXIU41.KZBCN1TS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.SMRXIU41.MOFE3A6J" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds"
        "l.W32YQORJ.EJUWS8XH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.W32YQORJ.O24UPG9S" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.W32YQORJ.9T5QM6Y3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.W32YQORJ.TDNATKKT" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.W32YQORJ.YSXDV3IZ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_line_comment.ds"
        "l.FRVYRJCR.ZH08JERH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.FRVYRJCR.C93CJODW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.FRVYRJCR.E01PYT3F" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.FRVYRJCR.5EJJ1S9L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.FRVYRJCR.XZW2M09Z" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "l.AD5SSEWG.0RZQFNHQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.AD5SSEWG.BLKMBIUJ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.AD5SSEWG.FENQT46C" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.AD5SSEWG.D1TGO75K" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.AD5SSEWG.MF5M2RTB" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_line_comments.ds"
        "l.IYPX75VY.PI2T4XTV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.IYPX75VY.FOOAS0OW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.IYPX75VY.ZJO9M2ZB" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.IYPX75VY.WE3LGBRQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.IYPX75VY.U8RJIFAY" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_mixed_comments.ds"
        "l.TRMN7BLP.3JC7WCL8" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.C6611GLP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.LPHG3F98" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.MTX6T5V1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.MGR11SW0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.UOMWACI1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.Z0K9BROB" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.FKSQTYI6" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.TRMN7BLP.T9G4LZW7" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_commas.ds"
        "l.VTIZYN15.V2K0JF1L" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.PJV28DVJ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.VEJH74XI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.DD64ZI86" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.1D8EWNJB" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.SI368JR1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.FIHL7CO1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.HNPIPMMT" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.AM8GJ70F" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.896JKIQR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.830JOU1U" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.VTIZYN15.QVX0LFCP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_producers.ds"
        "l.4NB5BK5S.J716TBCN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.E5842OGA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.NUXVA6OO" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.TUJPYVS3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.PNCUJF7O" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.7XIATXGR" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.88R66REU" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.I8UOTPUA" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.4NB5BK5S.C9CX8ZAK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\D_semicolons.ds"
        "l.YZLJYNKC.VT2JWK3D" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.YZLJYNKC.URDC2K04" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.YZLJYNKC.NW62SO6P" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.YZLJYNKC.SMAY4FEZ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.YZLJYNKC.WWTH1F54" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_commas.ds"
        "l.RVL469SF.06EE48RC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.BWLQMT22" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.D3QQRNEN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.X5NJC4AQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.BMHXY8K6" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.VU0JMFLE" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.B0TP8149" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.RVL469SF.PJBNZQBW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "l.2MI0R23I.H0N48QFF" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.2CTB79GG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.TKX2KHY7" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.9DTVWU9A" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.VQCQ3CXI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "l.2MI0R23I.M4JTPG5A" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"

