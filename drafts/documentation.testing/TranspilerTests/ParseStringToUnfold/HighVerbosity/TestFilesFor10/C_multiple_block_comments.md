========================================
Source Code (between the arrows)
========================================

🡆fabrics -> /* comment *//* comment */
/* comment */

	wool fabrics,
	cotton fabrics, /*comment*/
	/* comment */
	silk fabrics,
	synthetic fabrics; /* comment *//* comment */🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
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
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "QYI7IJ8S" 

    .Productions
        "QYI7IJ8S" -> "XGYR5Q7T", "2F5AL7MD", "OTFITQMZ", "PREL8D6E";

    .Translations
        "QYI7IJ8S" - "fabrics"
        "XGYR5Q7T" - "wool fabrics"
        "2F5AL7MD" - "cotton fabrics"
        "OTFITQMZ" - "silk fabrics"
        "PREL8D6E" - "synthetic fabrics"

    .Links
        "QYI7IJ8S" - 
        "XGYR5Q7T" - 
        "2F5AL7MD" - 
        "OTFITQMZ" - 
        "PREL8D6E" - 

    .Decorators
        "QYI7IJ8S" - 
        "XGYR5Q7T" - 
        "2F5AL7MD" - 
        "OTFITQMZ" - 
        "PREL8D6E" - 

    .Tildes
        "QYI7IJ8S" -> 


    .ProdidFile
        "QYI7IJ8S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"

    .ItemidFile
        "QYI7IJ8S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "XGYR5Q7T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "2F5AL7MD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "OTFITQMZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"
        "PREL8D6E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_block_comments.ds"

