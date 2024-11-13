========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool fabrics <<someid>>,
	cotton fabrics <<someid>> ,
	silk fabrics<<someid>> ,
	synthetic fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
Preprocessed source code - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 117 characters, into 15 tokens.
Those were translated to 1 productions, containing 3 entries.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "9MJSJG30" 

    .Productions
        "9MJSJG30" -> "someid", "someid", "someid", "AM91A8LZ";

    .Translations
        "9MJSJG30" - "fabrics"
        "someid" - "silk fabrics"
        "AM91A8LZ" - "synthetic fabrics"

    .Links
        "9MJSJG30" - 
        "someid" - 
        "AM91A8LZ" - 

    .Decorators
        "9MJSJG30" - 
        "someid" - 
        "AM91A8LZ" - 

    .Tildes
        "9MJSJG30" -> 


    .ProdidFile
        "9MJSJG30" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"

    .ItemidFile
        "9MJSJG30" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "AM91A8LZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"

