========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	~ wool fabrics <someid>,
	~ cotton fabrics <someid2> ,

	silk fabrics<someid> ,
	synthetic fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
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
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "F2O3BFMG" 

    .Productions
        "F2O3BFMG" -> "someid", "3UG6LK3D";

    .Translations
        "F2O3BFMG" - "fabrics"
        "someid" - "silk fabrics"
        "someid2" - "cotton fabrics"
        "3UG6LK3D" - "synthetic fabrics"

    .Links
        "F2O3BFMG" - 
        "someid" - 
        "someid2" - 
        "3UG6LK3D" - 

    .Decorators
        "F2O3BFMG" - 
        "someid" - 
        "someid2" - 
        "3UG6LK3D" - 

    .Tildes
        "F2O3BFMG" -> "someid", "someid2";


    .ProdidFile
        "F2O3BFMG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"

    .ItemidFile
        "F2O3BFMG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "someid2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"
        "3UG6LK3D" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.A_tilde.ds"

