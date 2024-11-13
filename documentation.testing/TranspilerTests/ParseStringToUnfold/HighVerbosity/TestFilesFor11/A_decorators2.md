========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool {fabrics {{color| red}},
	cotton } fabrics,
	silk fabrics{{decorator}} ,
	synthetic {}{}fabrics {{some text}} ;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
Preprocessed source code - 134 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_CURL|'{') T(DATA|'fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_CURL|'} ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(DATA|'fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 134 characters, into 24 tokens.
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
        "8TXIJ2OL" 

    .Productions
        "8TXIJ2OL" -> "ZFLKOL6A", "EYDZ1AUD", "LT20E72Y", "NBZZ43DI";

    .Translations
        "8TXIJ2OL" - "fabrics"
        "ZFLKOL6A" - "wool {fabrics"
        "EYDZ1AUD" - "cotton } fabrics"
        "LT20E72Y" - "silk fabrics"
        "NBZZ43DI" - "synthetic {}{}fabrics"

    .Links
        "8TXIJ2OL" - 
        "ZFLKOL6A" - 
        "EYDZ1AUD" - 
        "LT20E72Y" - 
        "NBZZ43DI" - 

    .Decorators
        "8TXIJ2OL" - 
        "ZFLKOL6A" -  | "red"
        "EYDZ1AUD" - 
        "LT20E72Y" - "decorator"
        "NBZZ43DI" - "some text"

    .Tildes
        "8TXIJ2OL" -> 


    .ProdidFile
        "8TXIJ2OL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"

    .ItemidFile
        "8TXIJ2OL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "ZFLKOL6A" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "EYDZ1AUD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "LT20E72Y" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "NBZZ43DI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"

