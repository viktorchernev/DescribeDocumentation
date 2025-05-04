========================================
Source Code File Names (between the arrows)
========================================

🡆C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'Directory -> Unfold' operation...
"C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11"
STOP_ON_ERROR - False
PARSE_DS_ONLY - True
PARSE_TOP_DIRECTORY_ONLY - False
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
All Files: 7, Succeeded: 7, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "l.P0A3BKFB.5JXAGCU3" 

    .Productions
        "l.P0A3BKFB.5JXAGCU3" -> "l.P0A3BKFB.PGQQUEWK", "l.P0A3BKFB.KAINQQW0", "l.P0A3BKFB.VGM4IHQN", "l.P0A3BKFB.GCU8SX91";
        "l.ZW23TJDP.HBW180RW" -> "l.ZW23TJDP.R7C342CU", "l.ZW23TJDP.MUDNFJ3V", "l.ZW23TJDP.GQAKJ6GI", "l.ZW23TJDP.I5MIIQGC";
        "l.WP70F8ZR.A53GE5PC" -> "l.WP70F8ZR.4RBXPDND", "l.WP70F8ZR.XNF8YP5C", "l.WP70F8ZR.BGAJ5MCQ", "l.WP70F8ZR.L0O2R76E";
        "l.EZSFEMS1.KT4QMTF5" -> "l.EZSFEMS1.EJBC3O5V", "l.EZSFEMS1.BEVUREBI", "l.EZSFEMS1.Q7TNQ208", "l.EZSFEMS1.BZC5IOB1";
        "l.P56AEQ2X.65HIPJBY" -> "l.P56AEQ2X.someid", "l.P56AEQ2X.someid", "l.P56AEQ2X.someid", "l.P56AEQ2X.438RIQWV";
        "l.ZXMGYU19.K25OPCS9" -> "l.ZXMGYU19.someid", "l.ZXMGYU19.someid", "l.ZXMGYU19.someid", "l.ZXMGYU19.5VU0ECC4";
        "l.4F1LR8HA.BUOILXB2" -> "l.4F1LR8HA.someid", "l.4F1LR8HA.ODIOVZ8P";

    .Translations
        "l.P0A3BKFB.5JXAGCU3" - "fabrics"
        "l.P0A3BKFB.PGQQUEWK" - "wool fabrics"
        "l.P0A3BKFB.KAINQQW0" - "cotton fabrics"
        "l.P0A3BKFB.VGM4IHQN" - "silk fabrics"
        "l.P0A3BKFB.GCU8SX91" - "synthetic fabrics"
        "l.ZW23TJDP.HBW180RW" - "fabrics"
        "l.ZW23TJDP.R7C342CU" - "wool {fabrics"
        "l.ZW23TJDP.MUDNFJ3V" - "cotton } fabrics"
        "l.ZW23TJDP.GQAKJ6GI" - "silk fabrics"
        "l.ZW23TJDP.I5MIIQGC" - "synthetic {}{}fabrics"
        "l.WP70F8ZR.A53GE5PC" - "fabrics"
        "l.WP70F8ZR.4RBXPDND" - "wool fabrics"
        "l.WP70F8ZR.XNF8YP5C" - "cotton fabrics"
        "l.WP70F8ZR.BGAJ5MCQ" - "silk fabrics"
        "l.WP70F8ZR.L0O2R76E" - "synthetic fabrics"
        "l.EZSFEMS1.KT4QMTF5" - "fabrics"
        "l.EZSFEMS1.EJBC3O5V" - "wool [fabrics"
        "l.EZSFEMS1.BEVUREBI" - "cotton ] fabrics"
        "l.EZSFEMS1.Q7TNQ208" - "silk ][ fabrics"
        "l.EZSFEMS1.BZC5IOB1" - "synthetic [] fabrics"
        "l.P56AEQ2X.65HIPJBY" - "fabrics"
        "l.P56AEQ2X.someid" - "silk fabrics"
        "l.P56AEQ2X.438RIQWV" - "synthetic fabrics"
        "l.ZXMGYU19.K25OPCS9" - "fabrics"
        "l.ZXMGYU19.someid" - "silk fabrics"
        "l.ZXMGYU19.5VU0ECC4" - "synthetic<>fabrics"
        "l.4F1LR8HA.BUOILXB2" - "fabrics"
        "l.4F1LR8HA.someid" - "silk fabrics"
        "l.4F1LR8HA.someid2" - "cotton fabrics"
        "l.4F1LR8HA.ODIOVZ8P" - "synthetic fabrics"

    .Links
        "l.P0A3BKFB.5JXAGCU3" - 
        "l.P0A3BKFB.PGQQUEWK" - 
        "l.P0A3BKFB.KAINQQW0" - 
        "l.P0A3BKFB.VGM4IHQN" - 
        "l.P0A3BKFB.GCU8SX91" - 
        "l.ZW23TJDP.HBW180RW" - 
        "l.ZW23TJDP.R7C342CU" - 
        "l.ZW23TJDP.MUDNFJ3V" - 
        "l.ZW23TJDP.GQAKJ6GI" - 
        "l.ZW23TJDP.I5MIIQGC" - 
        "l.WP70F8ZR.A53GE5PC" - 
        "l.WP70F8ZR.4RBXPDND" - "http://someurl.net"
        "l.WP70F8ZR.XNF8YP5C" - 
        "l.WP70F8ZR.BGAJ5MCQ" - "http://otherurl.net"
        "l.WP70F8ZR.L0O2R76E" - "http://url.net"
        "l.EZSFEMS1.KT4QMTF5" - 
        "l.EZSFEMS1.EJBC3O5V" - "http://someurl.net"
        "l.EZSFEMS1.BEVUREBI" - 
        "l.EZSFEMS1.Q7TNQ208" - "http://otherurl.net"
        "l.EZSFEMS1.BZC5IOB1" - "http://url.net"
        "l.P56AEQ2X.65HIPJBY" - 
        "l.P56AEQ2X.someid" - 
        "l.P56AEQ2X.438RIQWV" - 
        "l.ZXMGYU19.K25OPCS9" - 
        "l.ZXMGYU19.someid" - 
        "l.ZXMGYU19.5VU0ECC4" - 
        "l.4F1LR8HA.BUOILXB2" - 
        "l.4F1LR8HA.someid" - 
        "l.4F1LR8HA.someid2" - 
        "l.4F1LR8HA.ODIOVZ8P" - 

    .Decorators
        "l.P0A3BKFB.5JXAGCU3" - 
        "l.P0A3BKFB.PGQQUEWK" -  | "red"
        "l.P0A3BKFB.KAINQQW0" - 
        "l.P0A3BKFB.VGM4IHQN" - "decorator"
        "l.P0A3BKFB.GCU8SX91" - "some text"
        "l.ZW23TJDP.HBW180RW" - 
        "l.ZW23TJDP.R7C342CU" -  | "red"
        "l.ZW23TJDP.MUDNFJ3V" - 
        "l.ZW23TJDP.GQAKJ6GI" - "decorator"
        "l.ZW23TJDP.I5MIIQGC" - "some text"
        "l.WP70F8ZR.A53GE5PC" - 
        "l.WP70F8ZR.4RBXPDND" - 
        "l.WP70F8ZR.XNF8YP5C" - 
        "l.WP70F8ZR.BGAJ5MCQ" - 
        "l.WP70F8ZR.L0O2R76E" - 
        "l.EZSFEMS1.KT4QMTF5" - 
        "l.EZSFEMS1.EJBC3O5V" - 
        "l.EZSFEMS1.BEVUREBI" - 
        "l.EZSFEMS1.Q7TNQ208" - 
        "l.EZSFEMS1.BZC5IOB1" - 
        "l.P56AEQ2X.65HIPJBY" - 
        "l.P56AEQ2X.someid" - 
        "l.P56AEQ2X.438RIQWV" - 
        "l.ZXMGYU19.K25OPCS9" - 
        "l.ZXMGYU19.someid" - 
        "l.ZXMGYU19.5VU0ECC4" - 
        "l.4F1LR8HA.BUOILXB2" - 
        "l.4F1LR8HA.someid" - 
        "l.4F1LR8HA.someid2" - 
        "l.4F1LR8HA.ODIOVZ8P" - 

    .Tildes
        "l.P0A3BKFB.5JXAGCU3" -> 
        "l.ZW23TJDP.HBW180RW" -> 
        "l.WP70F8ZR.A53GE5PC" -> 
        "l.EZSFEMS1.KT4QMTF5" -> 
        "l.P56AEQ2X.65HIPJBY" -> 
        "l.ZXMGYU19.K25OPCS9" -> 
        "l.4F1LR8HA.BUOILXB2" -> "l.4F1LR8HA.someid", "l.4F1LR8HA.someid2";


    .ProdidFile
        "l.P0A3BKFB.5JXAGCU3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.ZW23TJDP.HBW180RW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.WP70F8ZR.A53GE5PC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.EZSFEMS1.KT4QMTF5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.P56AEQ2X.65HIPJBY" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "l.ZXMGYU19.K25OPCS9" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "l.4F1LR8HA.BUOILXB2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"

    .ItemidFile
        "l.P0A3BKFB.5JXAGCU3" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.P0A3BKFB.PGQQUEWK" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.P0A3BKFB.KAINQQW0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.P0A3BKFB.VGM4IHQN" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.P0A3BKFB.GCU8SX91" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators.ds"
        "l.ZW23TJDP.HBW180RW" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.ZW23TJDP.R7C342CU" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.ZW23TJDP.MUDNFJ3V" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.ZW23TJDP.GQAKJ6GI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.ZW23TJDP.I5MIIQGC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_decorators2.ds"
        "l.WP70F8ZR.A53GE5PC" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.WP70F8ZR.4RBXPDND" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.WP70F8ZR.XNF8YP5C" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.WP70F8ZR.BGAJ5MCQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.WP70F8ZR.L0O2R76E" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links.ds"
        "l.EZSFEMS1.KT4QMTF5" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.EZSFEMS1.EJBC3O5V" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.EZSFEMS1.BEVUREBI" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.EZSFEMS1.Q7TNQ208" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.EZSFEMS1.BZC5IOB1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_links2.ds"
        "l.P56AEQ2X.65HIPJBY" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "l.P56AEQ2X.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
            "l.P56AEQ2X.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
            "l.P56AEQ2X.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "l.P56AEQ2X.438RIQWV" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags.ds"
        "l.ZXMGYU19.K25OPCS9" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "l.ZXMGYU19.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
            "l.ZXMGYU19.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
            "l.ZXMGYU19.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "l.ZXMGYU19.5VU0ECC4" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
        "l.4F1LR8HA.BUOILXB2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "l.4F1LR8HA.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
            "l.4F1LR8HA.someid" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "l.4F1LR8HA.someid2" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"
        "l.4F1LR8HA.ODIOVZ8P" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tilde.ds"

