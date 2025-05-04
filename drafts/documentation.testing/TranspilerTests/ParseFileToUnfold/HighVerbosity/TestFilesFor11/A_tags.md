========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool fabrics <<someid>>,
	cotton fabrics <<someid>> ,
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
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
Fetched file contents - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 117 characters, into 15 tokens.
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
        "UQVHIIWP" 

    .Productions
        "UQVHIIWP" -> "someid", "someid", "someid", "6PED4P5Y";

    .Translations
        "UQVHIIWP" - "fabrics"
        "someid" - "silk fabrics"
        "6PED4P5Y" - "synthetic fabrics"

    .Links
        "UQVHIIWP" - 
        "someid" - 
        "6PED4P5Y" - 

    .Decorators
        "UQVHIIWP" - 
        "someid" - 
        "6PED4P5Y" - 

    .Tildes
        "UQVHIIWP" -> 


    .ProdidFile
        "UQVHIIWP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"

    .ItemidFile
        "UQVHIIWP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
            "someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "6PED4P5Y" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"

