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
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
Preprocessed source code - 159 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_SQUARE|'[') T(DATA|'fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(RIGHT_SQUARE|']') T(LEFT_SQUARE|'[ ') T(DATA|'fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_SQUARE|'[') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
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
        "PSPRN4D5" 

    .Productions
        "PSPRN4D5" -> "MU6HU0HJ", "MZIQV8ZV", "INSQBEF2", "C5135R17";

    .Translations
        "PSPRN4D5" - "fabrics"
        "MU6HU0HJ" - "wool [fabrics"
        "MZIQV8ZV" - "cotton ] fabrics"
        "INSQBEF2" - "silk ][ fabrics"
        "C5135R17" - "synthetic [] fabrics"

    .Links
        "PSPRN4D5" - 
        "MU6HU0HJ" - "http://someurl.net"
        "MZIQV8ZV" - 
        "INSQBEF2" - "http://otherurl.net"
        "C5135R17" - "http://url.net"

    .Decorators
        "PSPRN4D5" - 
        "MU6HU0HJ" - 
        "MZIQV8ZV" - 
        "INSQBEF2" - 
        "C5135R17" - 

    .Tildes
        "PSPRN4D5" -> 


    .ProdidFile
        "PSPRN4D5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"

    .ItemidFile
        "PSPRN4D5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "MU6HU0HJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "MZIQV8ZV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "INSQBEF2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "C5135R17" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"

