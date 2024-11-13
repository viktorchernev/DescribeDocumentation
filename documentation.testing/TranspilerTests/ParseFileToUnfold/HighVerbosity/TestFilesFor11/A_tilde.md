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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
Fetched file contents - 124 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<<someid2>> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "EJBKQUOD" 

    .Productions
        "EJBKQUOD" -> "someid", "J46MJYG7";

    .Translations
        "EJBKQUOD" - "fabrics"
        "someid" - "silk fabrics"
        "someid2" - "cotton fabrics"
        "J46MJYG7" - "synthetic fabrics"

    .Links
        "EJBKQUOD" - 
        "someid" - 
        "someid2" - 
        "J46MJYG7" - 

    .Decorators
        "EJBKQUOD" - 
        "someid" - 
        "someid2" - 
        "J46MJYG7" - 

    .Tildes
        "EJBKQUOD" -> "someid", "someid2";


    .ProdidFile
        "EJBKQUOD" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"

    .ItemidFile
        "EJBKQUOD" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "someid2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "J46MJYG7" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"

