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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
Fetched file contents - 134 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_CURL|'{') T(DATA|'fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_CURL|'} ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(DATA|'fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "Y0CH96D5" 

    .Productions
        "Y0CH96D5" -> "HSO69ZGF", "6SEMDHW9", "5WMRBCRG", "OU7NMZM8";

    .Translations
        "Y0CH96D5" - "fabrics"
        "HSO69ZGF" - "wool {fabrics"
        "6SEMDHW9" - "cotton } fabrics"
        "5WMRBCRG" - "silk fabrics"
        "OU7NMZM8" - "synthetic {}{}fabrics"

    .Links
        "Y0CH96D5" - 
        "HSO69ZGF" - 
        "6SEMDHW9" - 
        "5WMRBCRG" - 
        "OU7NMZM8" - 

    .Decorators
        "Y0CH96D5" - 
        "HSO69ZGF" -  | "red"
        "6SEMDHW9" - 
        "5WMRBCRG" - "decorator"
        "OU7NMZM8" - "some text"

    .Tildes
        "Y0CH96D5" -> 


    .ProdidFile
        "Y0CH96D5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"

    .ItemidFile
        "Y0CH96D5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "HSO69ZGF" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "6SEMDHW9" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "5WMRBCRG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "OU7NMZM8" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"

