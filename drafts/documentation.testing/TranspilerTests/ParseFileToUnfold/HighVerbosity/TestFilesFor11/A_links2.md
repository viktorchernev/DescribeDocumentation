========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool [fabrics [[http://someurl.net]],
	cotton ] fabrics,
	silk ][ fabrics[[http://otherurl.net]] ,
	synthetic [] fabrics [[http://url.net]] ;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
Fetched file contents - 159 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_SQUARE|'[') T(DATA|'fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(RIGHT_SQUARE|']') T(LEFT_SQUARE|'[ ') T(DATA|'fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_SQUARE|'[') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 159 characters, into 25 tokens.
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
        "HLJO811Y" 

    .Productions
        "HLJO811Y" -> "2FE0Y5PW", "G893B8D4", "I5YUKXN9", "15QS1SH0";

    .Translations
        "HLJO811Y" - "fabrics"
        "2FE0Y5PW" - "wool [fabrics"
        "G893B8D4" - "cotton ] fabrics"
        "I5YUKXN9" - "silk ][ fabrics"
        "15QS1SH0" - "synthetic [] fabrics"

    .Links
        "HLJO811Y" - 
        "2FE0Y5PW" - "http://someurl.net"
        "G893B8D4" - 
        "I5YUKXN9" - "http://otherurl.net"
        "15QS1SH0" - "http://url.net"

    .Decorators
        "HLJO811Y" - 
        "2FE0Y5PW" - 
        "G893B8D4" - 
        "I5YUKXN9" - 
        "15QS1SH0" - 

    .Tildes
        "HLJO811Y" -> 


    .ProdidFile
        "HLJO811Y" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"

    .ItemidFile
        "HLJO811Y" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "2FE0Y5PW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "G893B8D4" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "I5YUKXN9" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "15QS1SH0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"

