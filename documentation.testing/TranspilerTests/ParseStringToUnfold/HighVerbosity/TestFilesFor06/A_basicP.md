========================================
Source Code (between the arrows)
========================================

🡆fabric*s ->

	wool http://abc.de fabrics,
	cotton fabrics,
	silk fabrics,
	synthetic fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
Preprocessed source code - 98 characters long

Parsing sequence: T(DATA|'fabric') T(STAR|'*') T(DATA|'s ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool http') T(PROTO_SLASHES|'://') T(DATA|'abc.de fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 98 characters, into 16 tokens.
Those were translated to 1 productions, containing 5 entries.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "WOSI0VTV" 

    .Productions
        "WOSI0VTV" -> "VD1CDJ64", "7TZ8DGY9", "OAJ3WK8P", "WXKDKNR9";

    .Translations
        "WOSI0VTV" - "fabric*s"
        "VD1CDJ64" - "wool http://abc.de fabrics"
        "7TZ8DGY9" - "cotton fabrics"
        "OAJ3WK8P" - "silk fabrics"
        "WXKDKNR9" - "synthetic fabrics"

    .Links
        "WOSI0VTV" - 
        "VD1CDJ64" - 
        "7TZ8DGY9" - 
        "OAJ3WK8P" - 
        "WXKDKNR9" - 

    .Decorators
        "WOSI0VTV" - 
        "VD1CDJ64" - 
        "7TZ8DGY9" - 
        "OAJ3WK8P" - 
        "WXKDKNR9" - 

    .Tildes

    .ProdidFile
        "WOSI0VTV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"

    .ItemidFile
        "WOSI0VTV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
        "VD1CDJ64" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
        "7TZ8DGY9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
        "OAJ3WK8P" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"
        "WXKDKNR9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basicP.ds"

