========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String[] -> Unfold' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
Preprocessed source code - 127 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 127 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
Preprocessed source code - 134 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_CURL|'{') T(DATA|'fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_CURL|'} ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(DATA|'fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 134 characters, into 24 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
Preprocessed source code - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 150 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
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
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
Preprocessed source code - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 117 characters, into 15 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
Preprocessed source code - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 121 characters, into 22 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
Preprocessed source code - 124 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(TILDE|'~') T(DATA|' wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(TILDE|'~') T(DATA|' cotton fabrics ') T(TAG|'<<someid2>> ') T(SEPARATOR|',\r\n\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
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
        "l.Q27P3FSX.K4D4K06V" 

    .Productions
        "l.Q27P3FSX.K4D4K06V" -> "l.Q27P3FSX.1OPW64RF", "l.Q27P3FSX.7JIVFL4H", "l.Q27P3FSX.NV8AXJOL", "l.Q27P3FSX.KY3ZA0RJ";
        "l.1RZ3R6TP.RLF5T9HD" -> "l.1RZ3R6TP.OF7QY26X", "l.1RZ3R6TP.5C5N7F0P", "l.1RZ3R6TP.HHHIX9L1", "l.1RZ3R6TP.B97IE25J";
        "l.EUKH2BI8.ZV59FG4S" -> "l.EUKH2BI8.1JX3HCEP", "l.EUKH2BI8.FS5LHLEZ", "l.EUKH2BI8.IO5QMQAK", "l.EUKH2BI8.RQC34EG9";
        "l.PFHRTI8O.VVK2XVNH" -> "l.PFHRTI8O.5UL8LDQ7", "l.PFHRTI8O.XTL2Y8TA", "l.PFHRTI8O.8VG8IFIC", "l.PFHRTI8O.H4HVHS9N";
        "l.YQAFKUTR.6AP3GJAE" -> "l.YQAFKUTR.someid", "l.YQAFKUTR.someid", "l.YQAFKUTR.someid", "l.YQAFKUTR.RQMAEORJ";
        "l.0GEGAY75.C4FWEHN3" -> "l.0GEGAY75.someid", "l.0GEGAY75.someid", "l.0GEGAY75.someid", "l.0GEGAY75.DB8W22F3";
        "l.HAQXO2TF.1C8HWGZG" -> "l.HAQXO2TF.someid", "l.HAQXO2TF.Q1FJGFWQ";

    .Translations
        "l.Q27P3FSX.K4D4K06V" - "fabrics"
        "l.Q27P3FSX.1OPW64RF" - "wool fabrics"
        "l.Q27P3FSX.7JIVFL4H" - "cotton fabrics"
        "l.Q27P3FSX.NV8AXJOL" - "silk fabrics"
        "l.Q27P3FSX.KY3ZA0RJ" - "synthetic fabrics"
        "l.1RZ3R6TP.RLF5T9HD" - "fabrics"
        "l.1RZ3R6TP.OF7QY26X" - "wool {fabrics"
        "l.1RZ3R6TP.5C5N7F0P" - "cotton } fabrics"
        "l.1RZ3R6TP.HHHIX9L1" - "silk fabrics"
        "l.1RZ3R6TP.B97IE25J" - "synthetic {}{}fabrics"
        "l.EUKH2BI8.ZV59FG4S" - "fabrics"
        "l.EUKH2BI8.1JX3HCEP" - "wool fabrics"
        "l.EUKH2BI8.FS5LHLEZ" - "cotton fabrics"
        "l.EUKH2BI8.IO5QMQAK" - "silk fabrics"
        "l.EUKH2BI8.RQC34EG9" - "synthetic fabrics"
        "l.PFHRTI8O.VVK2XVNH" - "fabrics"
        "l.PFHRTI8O.5UL8LDQ7" - "wool [fabrics"
        "l.PFHRTI8O.XTL2Y8TA" - "cotton ] fabrics"
        "l.PFHRTI8O.8VG8IFIC" - "silk ][ fabrics"
        "l.PFHRTI8O.H4HVHS9N" - "synthetic [] fabrics"
        "l.YQAFKUTR.6AP3GJAE" - "fabrics"
        "l.YQAFKUTR.someid" - "silk fabrics"
        "l.YQAFKUTR.RQMAEORJ" - "synthetic fabrics"
        "l.0GEGAY75.C4FWEHN3" - "fabrics"
        "l.0GEGAY75.someid" - "silk fabrics"
        "l.0GEGAY75.DB8W22F3" - "synthetic<>fabrics"
        "l.HAQXO2TF.1C8HWGZG" - "fabrics"
        "l.HAQXO2TF.someid" - "silk fabrics"
        "l.HAQXO2TF.someid2" - "cotton fabrics"
        "l.HAQXO2TF.Q1FJGFWQ" - "synthetic fabrics"

    .Links
        "l.Q27P3FSX.K4D4K06V" - 
        "l.Q27P3FSX.1OPW64RF" - 
        "l.Q27P3FSX.7JIVFL4H" - 
        "l.Q27P3FSX.NV8AXJOL" - 
        "l.Q27P3FSX.KY3ZA0RJ" - 
        "l.1RZ3R6TP.RLF5T9HD" - 
        "l.1RZ3R6TP.OF7QY26X" - 
        "l.1RZ3R6TP.5C5N7F0P" - 
        "l.1RZ3R6TP.HHHIX9L1" - 
        "l.1RZ3R6TP.B97IE25J" - 
        "l.EUKH2BI8.ZV59FG4S" - 
        "l.EUKH2BI8.1JX3HCEP" - "http://someurl.net"
        "l.EUKH2BI8.FS5LHLEZ" - 
        "l.EUKH2BI8.IO5QMQAK" - "http://otherurl.net"
        "l.EUKH2BI8.RQC34EG9" - "http://url.net"
        "l.PFHRTI8O.VVK2XVNH" - 
        "l.PFHRTI8O.5UL8LDQ7" - "http://someurl.net"
        "l.PFHRTI8O.XTL2Y8TA" - 
        "l.PFHRTI8O.8VG8IFIC" - "http://otherurl.net"
        "l.PFHRTI8O.H4HVHS9N" - "http://url.net"
        "l.YQAFKUTR.6AP3GJAE" - 
        "l.YQAFKUTR.someid" - 
        "l.YQAFKUTR.RQMAEORJ" - 
        "l.0GEGAY75.C4FWEHN3" - 
        "l.0GEGAY75.someid" - 
        "l.0GEGAY75.DB8W22F3" - 
        "l.HAQXO2TF.1C8HWGZG" - 
        "l.HAQXO2TF.someid" - 
        "l.HAQXO2TF.someid2" - 
        "l.HAQXO2TF.Q1FJGFWQ" - 

    .Decorators
        "l.Q27P3FSX.K4D4K06V" - 
        "l.Q27P3FSX.1OPW64RF" -  | "red"
        "l.Q27P3FSX.7JIVFL4H" - 
        "l.Q27P3FSX.NV8AXJOL" - "decorator"
        "l.Q27P3FSX.KY3ZA0RJ" - "some text"
        "l.1RZ3R6TP.RLF5T9HD" - 
        "l.1RZ3R6TP.OF7QY26X" -  | "red"
        "l.1RZ3R6TP.5C5N7F0P" - 
        "l.1RZ3R6TP.HHHIX9L1" - "decorator"
        "l.1RZ3R6TP.B97IE25J" - "some text"
        "l.EUKH2BI8.ZV59FG4S" - 
        "l.EUKH2BI8.1JX3HCEP" - 
        "l.EUKH2BI8.FS5LHLEZ" - 
        "l.EUKH2BI8.IO5QMQAK" - 
        "l.EUKH2BI8.RQC34EG9" - 
        "l.PFHRTI8O.VVK2XVNH" - 
        "l.PFHRTI8O.5UL8LDQ7" - 
        "l.PFHRTI8O.XTL2Y8TA" - 
        "l.PFHRTI8O.8VG8IFIC" - 
        "l.PFHRTI8O.H4HVHS9N" - 
        "l.YQAFKUTR.6AP3GJAE" - 
        "l.YQAFKUTR.someid" - 
        "l.YQAFKUTR.RQMAEORJ" - 
        "l.0GEGAY75.C4FWEHN3" - 
        "l.0GEGAY75.someid" - 
        "l.0GEGAY75.DB8W22F3" - 
        "l.HAQXO2TF.1C8HWGZG" - 
        "l.HAQXO2TF.someid" - 
        "l.HAQXO2TF.someid2" - 
        "l.HAQXO2TF.Q1FJGFWQ" - 

    .Tildes
        "l.Q27P3FSX.K4D4K06V" -> 
        "l.1RZ3R6TP.RLF5T9HD" -> 
        "l.EUKH2BI8.ZV59FG4S" -> 
        "l.PFHRTI8O.VVK2XVNH" -> 
        "l.YQAFKUTR.6AP3GJAE" -> 
        "l.0GEGAY75.C4FWEHN3" -> 
        "l.HAQXO2TF.1C8HWGZG" -> "l.HAQXO2TF.someid", "l.HAQXO2TF.someid2";


    .ProdidFile
        "l.Q27P3FSX.K4D4K06V" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.1RZ3R6TP.RLF5T9HD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.EUKH2BI8.ZV59FG4S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.PFHRTI8O.VVK2XVNH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.YQAFKUTR.6AP3GJAE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "l.0GEGAY75.C4FWEHN3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "l.HAQXO2TF.1C8HWGZG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"

    .ItemidFile
        "l.Q27P3FSX.K4D4K06V" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.Q27P3FSX.1OPW64RF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.Q27P3FSX.7JIVFL4H" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.Q27P3FSX.NV8AXJOL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.Q27P3FSX.KY3ZA0RJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators.ds"
        "l.1RZ3R6TP.RLF5T9HD" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.1RZ3R6TP.OF7QY26X" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.1RZ3R6TP.5C5N7F0P" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.1RZ3R6TP.HHHIX9L1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.1RZ3R6TP.B97IE25J" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_decorators2.ds"
        "l.EUKH2BI8.ZV59FG4S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.EUKH2BI8.1JX3HCEP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.EUKH2BI8.FS5LHLEZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.EUKH2BI8.IO5QMQAK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.EUKH2BI8.RQC34EG9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "l.PFHRTI8O.VVK2XVNH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.PFHRTI8O.5UL8LDQ7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.PFHRTI8O.XTL2Y8TA" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.PFHRTI8O.8VG8IFIC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.PFHRTI8O.H4HVHS9N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links2.ds"
        "l.YQAFKUTR.6AP3GJAE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "l.YQAFKUTR.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
            "l.YQAFKUTR.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
            "l.YQAFKUTR.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "l.YQAFKUTR.RQMAEORJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags.ds"
        "l.0GEGAY75.C4FWEHN3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "l.0GEGAY75.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
            "l.0GEGAY75.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
            "l.0GEGAY75.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "l.0GEGAY75.DB8W22F3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tags2.ds"
        "l.HAQXO2TF.1C8HWGZG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "l.HAQXO2TF.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
            "l.HAQXO2TF.someid" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "l.HAQXO2TF.someid2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"
        "l.HAQXO2TF.Q1FJGFWQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_tilde.ds"

