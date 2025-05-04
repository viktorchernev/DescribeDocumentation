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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
Fetched file contents - 118 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<someid>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<someid2> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<someid> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "LAIJ6441" 

    .Productions
        "LAIJ6441" -> "someid", "OF5HBYJS";

    .Translations
        "LAIJ6441" - "fabrics"
        "someid" - "silk fabrics"
        "someid2" - "cotton fabrics"
        "OF5HBYJS" - "synthetic fabrics"

    .Links
        "LAIJ6441" - 
        "someid" - 
        "someid2" - 
        "OF5HBYJS" - 

    .Decorators
        "LAIJ6441" - 
        "someid" - 
        "someid2" - 
        "OF5HBYJS" - 

    .Tildes
        "LAIJ6441" -> "someid", "someid2";


    .ProdidFile
        "LAIJ6441" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"

    .ItemidFile
        "LAIJ6441" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "someid2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"
        "OF5HBYJS" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\A_tilde.ds"

