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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
Fetched file contents - 127 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "LYP0FHPH" 

    .Productions
        "LYP0FHPH" -> "T6EUF93Y", "D3FTJ7Z2", "9HRMHGDI", "1ACHZ2E3";

    .Translations
        "LYP0FHPH" - "fabrics"
        "T6EUF93Y" - "wool fabrics"
        "D3FTJ7Z2" - "cotton fabrics"
        "9HRMHGDI" - "silk fabrics"
        "1ACHZ2E3" - "synthetic fabrics"

    .Links
        "LYP0FHPH" - 
        "T6EUF93Y" - 
        "D3FTJ7Z2" - 
        "9HRMHGDI" - 
        "1ACHZ2E3" - 

    .Decorators
        "LYP0FHPH" - 
        "T6EUF93Y" -  | "red"
        "D3FTJ7Z2" - 
        "9HRMHGDI" - "decorator"
        "1ACHZ2E3" - "some text"

    .Tildes
        "LYP0FHPH" -> 


    .ProdidFile
        "LYP0FHPH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"

    .ItemidFile
        "LYP0FHPH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "T6EUF93Y" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "D3FTJ7Z2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "9HRMHGDI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "1ACHZ2E3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"

