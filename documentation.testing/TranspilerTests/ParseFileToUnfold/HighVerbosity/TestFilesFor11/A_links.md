========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool fabrics [[http://someurl.net]],
	cotton fabrics,
	silk fabrics[[http://otherurl.net]] ,
	synthetic fabrics [[http://url.net]] ;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
Fetched file contents - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 150 characters, into 15 tokens.
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
        "07ZCB84R" 

    .Productions
        "07ZCB84R" -> "NSSN9YGH", "WYLUY19F", "22D4RZA5", "6JQRNM74";

    .Translations
        "07ZCB84R" - "fabrics"
        "NSSN9YGH" - "wool fabrics"
        "WYLUY19F" - "cotton fabrics"
        "22D4RZA5" - "silk fabrics"
        "6JQRNM74" - "synthetic fabrics"

    .Links
        "07ZCB84R" - 
        "NSSN9YGH" - "http://someurl.net"
        "WYLUY19F" - 
        "22D4RZA5" - "http://otherurl.net"
        "6JQRNM74" - "http://url.net"

    .Decorators
        "07ZCB84R" - 
        "NSSN9YGH" - 
        "WYLUY19F" - 
        "22D4RZA5" - 
        "6JQRNM74" - 

    .Tildes
        "07ZCB84R" -> 


    .ProdidFile
        "07ZCB84R" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"

    .ItemidFile
        "07ZCB84R" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "NSSN9YGH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "WYLUY19F" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "22D4RZA5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "6JQRNM74" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"

