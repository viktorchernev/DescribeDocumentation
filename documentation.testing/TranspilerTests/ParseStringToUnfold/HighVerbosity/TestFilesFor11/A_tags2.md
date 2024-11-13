========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool < fabrics <<someid>>,
	cotton >fabrics <<someid>> ,
	silk fabrics<<someid>> ,
	synthetic<>fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
Preprocessed source code - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 121 characters, into 22 tokens.
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
        "NF2O5C01" 

    .Productions
        "NF2O5C01" -> "someid", "someid", "someid", "HLJ9M3YU";

    .Translations
        "NF2O5C01" - "fabrics"
        "someid" - "silk fabrics"
        "HLJ9M3YU" - "synthetic<>fabrics"

    .Links
        "NF2O5C01" - 
        "someid" - 
        "HLJ9M3YU" - 

    .Decorators
        "NF2O5C01" - 
        "someid" - 
        "HLJ9M3YU" - 

    .Tildes
        "NF2O5C01" -> 


    .ProdidFile
        "NF2O5C01" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"

    .ItemidFile
        "NF2O5C01" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "HLJ9M3YU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"

