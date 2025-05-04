========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	~ wool fabrics <<someid>>,
	~ cotton fabrics <<someid2>> ,

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
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
Preprocessed source code - 124 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<<someid2>> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 124 characters, into 17 tokens.
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
        "5IBD3S14" 

    .Productions
        "5IBD3S14" -> "someid", "3THRTQPX";

    .Translations
        "5IBD3S14" - "fabrics"
        "someid" - "silk fabrics"
        "someid2" - "cotton fabrics"
        "3THRTQPX" - "synthetic fabrics"

    .Links
        "5IBD3S14" - 
        "someid" - 
        "someid2" - 
        "3THRTQPX" - 

    .Decorators
        "5IBD3S14" - 
        "someid" - 
        "someid2" - 
        "3THRTQPX" - 

    .Tildes
        "5IBD3S14" -> "someid", "someid2";


    .ProdidFile
        "5IBD3S14" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"

    .ItemidFile
        "5IBD3S14" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
            "someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "someid2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "3THRTQPX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"

