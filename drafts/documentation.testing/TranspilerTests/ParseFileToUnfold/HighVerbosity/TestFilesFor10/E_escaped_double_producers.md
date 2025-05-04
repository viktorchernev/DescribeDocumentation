========================================
Source Code (between the arrows)
========================================

🡆fabrics \->> wool fabrics ->
	synthetic fabrics;

fabrics->\> wool fabrics ->
	cotton fabrics;

fabrics -\>>wool fabrics ->
	silk fabrics;

fabrics-\>\>wool fabrics ->
	other fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'File -> Unfold' operation...
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
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "J37CNORW" "X1WX9WU1" "LJYMVPLS" "PSOMBIZP" 

    .Productions
        "J37CNORW" -> "VT4PJBJ";
        "X1WX9WU1" -> "EH3LEWK";
        "LJYMVPLS" -> "4SKJNKC";
        "PSOMBIZP" -> "J0RV8RC";

    .Translations
        "J37CNORW" - "fabrics \->> wool fabrics"
        "JVT4PJBJ" - "synthetic fabrics"
        "X1WX9WU1" - "fabrics->\> wool fabrics"
        "BEH3LEWK" - "cotton fabrics"
        "LJYMVPLS" - "fabrics -\>>wool fabrics"
        "C4SKJNKC" - "silk fabrics"
        "PSOMBIZP" - "fabrics-\>\>wool fabrics"
        "HJ0RV8RC" - "other fabrics"

    .Links
        "J37CNORW" - 
        "JVT4PJBJ" - 
        "X1WX9WU1" - 
        "BEH3LEWK" - 
        "LJYMVPLS" - 
        "C4SKJNKC" - 
        "PSOMBIZP" - 
        "HJ0RV8RC" - 

    .Decorators
        "J37CNORW" - 
        "JVT4PJBJ" - 
        "X1WX9WU1" - 
        "BEH3LEWK" - 
        "LJYMVPLS" - 
        "C4SKJNKC" - 
        "PSOMBIZP" - 
        "HJ0RV8RC" - 

    .Tildes
        "J37CNORW" -> 
        "X1WX9WU1" -> 
        "LJYMVPLS" -> 
        "PSOMBIZP" -> 


    .ProdidFile
        "J37CNORW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "X1WX9WU1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "LJYMVPLS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "PSOMBIZP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"

    .ItemidFile
        "J37CNORW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "JVT4PJBJ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "X1WX9WU1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "BEH3LEWK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "LJYMVPLS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "C4SKJNKC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "PSOMBIZP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"
        "HJ0RV8RC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_producers.ds"

