========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool fabrics {{color| red}},
	cotton fabrics,
	silk fabrics{{decorator}} ,
	synthetic fabrics {{some text}} ;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
Preprocessed source code - 127 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 127 characters, into 15 tokens.
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
        "3X2VSYXR" 

    .Productions
        "3X2VSYXR" -> "XCO1YZMV", "HFLKHXTJ", "IOJ292X2", "G0CWIYJC";

    .Translations
        "3X2VSYXR" - "fabrics"
        "XCO1YZMV" - "wool fabrics"
        "HFLKHXTJ" - "cotton fabrics"
        "IOJ292X2" - "silk fabrics"
        "G0CWIYJC" - "synthetic fabrics"

    .Links
        "3X2VSYXR" - 
        "XCO1YZMV" - 
        "HFLKHXTJ" - 
        "IOJ292X2" - 
        "G0CWIYJC" - 

    .Decorators
        "3X2VSYXR" - 
        "XCO1YZMV" -  | "red"
        "HFLKHXTJ" - 
        "IOJ292X2" - "decorator"
        "G0CWIYJC" - "some text"

    .Tildes
        "3X2VSYXR" -> 


    .ProdidFile
        "3X2VSYXR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"

    .ItemidFile
        "3X2VSYXR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "XCO1YZMV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "HFLKHXTJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "IOJ292X2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "G0CWIYJC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"

