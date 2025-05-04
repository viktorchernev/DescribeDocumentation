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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
Fetched file contents - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "2B0NNSYC" 

    .Productions
        "2B0NNSYC" -> "someid", "someid", "someid", "JCDM3Q07";

    .Translations
        "2B0NNSYC" - "fabrics"
        "someid" - "silk fabrics"
        "JCDM3Q07" - "synthetic<>fabrics"

    .Links
        "2B0NNSYC" - 
        "someid" - 
        "JCDM3Q07" - 

    .Decorators
        "2B0NNSYC" - 
        "someid" - 
        "JCDM3Q07" - 

    .Tildes
        "2B0NNSYC" -> 


    .ProdidFile
        "2B0NNSYC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"

    .ItemidFile
        "2B0NNSYC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "JCDM3Q07" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"

