========================================
Source Code File Names (between the arrows)
========================================

🡆1FEF9E96A656B64A
94FBA398666DD74B
C154A264875CACDB
5BDB282AEE449C73
3BB37235E6B67275
6CF410FD9ECE4303
4D0851249141039F🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String[] -> Unfold' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "1FEF9E96A656B64A"
Preprocessed source code - 127 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 127 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "94FBA398666DD74B"
Preprocessed source code - 134 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_CURL|'{') T(DATA|'fabrics ') T(DECORATOR|'{{color| red}}') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_CURL|'} ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(DECORATOR|'{{decorator}} ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(LEFT_CURL|'{') T(RIGHT_CURL|'}') T(DATA|'fabrics ') T(DECORATOR|'{{some text}} ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 134 characters, into 24 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "C154A264875CACDB"
Preprocessed source code - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 150 characters, into 15 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "5BDB282AEE449C73"
Preprocessed source code - 159 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_SQUARE|'[') T(DATA|'fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk ') T(RIGHT_SQUARE|']') T(LEFT_SQUARE|'[ ') T(DATA|'fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic ') T(LEFT_SQUARE|'[') T(RIGHT_SQUARE|'] ') T(DATA|'fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 159 characters, into 25 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "3BB37235E6B67275"
Preprocessed source code - 117 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 117 characters, into 15 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "6CF410FD9ECE4303"
Preprocessed source code - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 121 characters, into 22 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "4D0851249141039F"
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
        "l.V8V7X7HL.YJGKBC57" 

    .Productions
        "l.V8V7X7HL.YJGKBC57" -> "l.V8V7X7HL.B3PWPERS", "l.V8V7X7HL.18JNEPAE", "l.V8V7X7HL.K3ZBCYCT", "l.V8V7X7HL.5QJISPJL";
        "l.QTRURF3Z.VFWAYAQD" -> "l.QTRURF3Z.5FE9VYIH", "l.QTRURF3Z.BJJI5MOK", "l.QTRURF3Z.NRQZWEDW", "l.QTRURF3Z.XNZZHDAZ";
        "l.869CZP6U.J1TTBGJV" -> "l.869CZP6U.KHETEDSS", "l.869CZP6U.2MCFUB8I", "l.869CZP6U.AYTF97XX", "l.869CZP6U.MS9PNH46";
        "l.F1WU32KV.MZGRFP0C" -> "l.F1WU32KV.7LN0DJHF", "l.F1WU32KV.J76W8EWF", "l.F1WU32KV.D8E1MMIQ", "l.F1WU32KV.Z8FYHE0P";
        "l.46XQJKWV.642IAWI6" -> "l.46XQJKWV.someid", "l.46XQJKWV.someid", "l.46XQJKWV.someid", "l.46XQJKWV.JW49LT18";
        "l.X7FC01BZ.GUJ5KLAQ" -> "l.X7FC01BZ.someid", "l.X7FC01BZ.someid", "l.X7FC01BZ.someid", "l.X7FC01BZ.5QLJ1VTF";
        "l.BZPAL52J.BJVE4R3D" -> "l.BZPAL52J.someid", "l.BZPAL52J.CLPXINWZ";

    .Translations
        "l.V8V7X7HL.YJGKBC57" - "fabrics"
        "l.V8V7X7HL.B3PWPERS" - "wool fabrics"
        "l.V8V7X7HL.18JNEPAE" - "cotton fabrics"
        "l.V8V7X7HL.K3ZBCYCT" - "silk fabrics"
        "l.V8V7X7HL.5QJISPJL" - "synthetic fabrics"
        "l.QTRURF3Z.VFWAYAQD" - "fabrics"
        "l.QTRURF3Z.5FE9VYIH" - "wool {fabrics"
        "l.QTRURF3Z.BJJI5MOK" - "cotton } fabrics"
        "l.QTRURF3Z.NRQZWEDW" - "silk fabrics"
        "l.QTRURF3Z.XNZZHDAZ" - "synthetic {}{}fabrics"
        "l.869CZP6U.J1TTBGJV" - "fabrics"
        "l.869CZP6U.KHETEDSS" - "wool fabrics"
        "l.869CZP6U.2MCFUB8I" - "cotton fabrics"
        "l.869CZP6U.AYTF97XX" - "silk fabrics"
        "l.869CZP6U.MS9PNH46" - "synthetic fabrics"
        "l.F1WU32KV.MZGRFP0C" - "fabrics"
        "l.F1WU32KV.7LN0DJHF" - "wool [fabrics"
        "l.F1WU32KV.J76W8EWF" - "cotton ] fabrics"
        "l.F1WU32KV.D8E1MMIQ" - "silk ][ fabrics"
        "l.F1WU32KV.Z8FYHE0P" - "synthetic [] fabrics"
        "l.46XQJKWV.642IAWI6" - "fabrics"
        "l.46XQJKWV.someid" - "silk fabrics"
        "l.46XQJKWV.JW49LT18" - "synthetic fabrics"
        "l.X7FC01BZ.GUJ5KLAQ" - "fabrics"
        "l.X7FC01BZ.someid" - "silk fabrics"
        "l.X7FC01BZ.5QLJ1VTF" - "synthetic<>fabrics"
        "l.BZPAL52J.BJVE4R3D" - "fabrics"
        "l.BZPAL52J.someid" - "silk fabrics"
        "l.BZPAL52J.someid2" - "cotton fabrics"
        "l.BZPAL52J.CLPXINWZ" - "synthetic fabrics"

    .Links
        "l.V8V7X7HL.YJGKBC57" - 
        "l.V8V7X7HL.B3PWPERS" - 
        "l.V8V7X7HL.18JNEPAE" - 
        "l.V8V7X7HL.K3ZBCYCT" - 
        "l.V8V7X7HL.5QJISPJL" - 
        "l.QTRURF3Z.VFWAYAQD" - 
        "l.QTRURF3Z.5FE9VYIH" - 
        "l.QTRURF3Z.BJJI5MOK" - 
        "l.QTRURF3Z.NRQZWEDW" - 
        "l.QTRURF3Z.XNZZHDAZ" - 
        "l.869CZP6U.J1TTBGJV" - 
        "l.869CZP6U.KHETEDSS" - "http://someurl.net"
        "l.869CZP6U.2MCFUB8I" - 
        "l.869CZP6U.AYTF97XX" - "http://otherurl.net"
        "l.869CZP6U.MS9PNH46" - "http://url.net"
        "l.F1WU32KV.MZGRFP0C" - 
        "l.F1WU32KV.7LN0DJHF" - "http://someurl.net"
        "l.F1WU32KV.J76W8EWF" - 
        "l.F1WU32KV.D8E1MMIQ" - "http://otherurl.net"
        "l.F1WU32KV.Z8FYHE0P" - "http://url.net"
        "l.46XQJKWV.642IAWI6" - 
        "l.46XQJKWV.someid" - 
        "l.46XQJKWV.JW49LT18" - 
        "l.X7FC01BZ.GUJ5KLAQ" - 
        "l.X7FC01BZ.someid" - 
        "l.X7FC01BZ.5QLJ1VTF" - 
        "l.BZPAL52J.BJVE4R3D" - 
        "l.BZPAL52J.someid" - 
        "l.BZPAL52J.someid2" - 
        "l.BZPAL52J.CLPXINWZ" - 

    .Decorators
        "l.V8V7X7HL.YJGKBC57" - 
        "l.V8V7X7HL.B3PWPERS" -  | "red"
        "l.V8V7X7HL.18JNEPAE" - 
        "l.V8V7X7HL.K3ZBCYCT" - "decorator"
        "l.V8V7X7HL.5QJISPJL" - "some text"
        "l.QTRURF3Z.VFWAYAQD" - 
        "l.QTRURF3Z.5FE9VYIH" -  | "red"
        "l.QTRURF3Z.BJJI5MOK" - 
        "l.QTRURF3Z.NRQZWEDW" - "decorator"
        "l.QTRURF3Z.XNZZHDAZ" - "some text"
        "l.869CZP6U.J1TTBGJV" - 
        "l.869CZP6U.KHETEDSS" - 
        "l.869CZP6U.2MCFUB8I" - 
        "l.869CZP6U.AYTF97XX" - 
        "l.869CZP6U.MS9PNH46" - 
        "l.F1WU32KV.MZGRFP0C" - 
        "l.F1WU32KV.7LN0DJHF" - 
        "l.F1WU32KV.J76W8EWF" - 
        "l.F1WU32KV.D8E1MMIQ" - 
        "l.F1WU32KV.Z8FYHE0P" - 
        "l.46XQJKWV.642IAWI6" - 
        "l.46XQJKWV.someid" - 
        "l.46XQJKWV.JW49LT18" - 
        "l.X7FC01BZ.GUJ5KLAQ" - 
        "l.X7FC01BZ.someid" - 
        "l.X7FC01BZ.5QLJ1VTF" - 
        "l.BZPAL52J.BJVE4R3D" - 
        "l.BZPAL52J.someid" - 
        "l.BZPAL52J.someid2" - 
        "l.BZPAL52J.CLPXINWZ" - 

    .Tildes
        "l.V8V7X7HL.YJGKBC57" -> 
        "l.QTRURF3Z.VFWAYAQD" -> 
        "l.869CZP6U.J1TTBGJV" -> 
        "l.F1WU32KV.MZGRFP0C" -> 
        "l.46XQJKWV.642IAWI6" -> 
        "l.X7FC01BZ.GUJ5KLAQ" -> 
        "l.BZPAL52J.BJVE4R3D" -> "l.BZPAL52J.someid", "l.BZPAL52J.someid2";


    .ProdidFile
        "l.V8V7X7HL.YJGKBC57" - "1FEF9E96A656B64A"
        "l.QTRURF3Z.VFWAYAQD" - "94FBA398666DD74B"
        "l.869CZP6U.J1TTBGJV" - "C154A264875CACDB"
        "l.F1WU32KV.MZGRFP0C" - "5BDB282AEE449C73"
        "l.46XQJKWV.642IAWI6" - "3BB37235E6B67275"
        "l.X7FC01BZ.GUJ5KLAQ" - "6CF410FD9ECE4303"
        "l.BZPAL52J.BJVE4R3D" - "4D0851249141039F"

    .ItemidFile
        "l.V8V7X7HL.YJGKBC57" - "1FEF9E96A656B64A"
        "l.V8V7X7HL.B3PWPERS" - "1FEF9E96A656B64A"
        "l.V8V7X7HL.18JNEPAE" - "1FEF9E96A656B64A"
        "l.V8V7X7HL.K3ZBCYCT" - "1FEF9E96A656B64A"
        "l.V8V7X7HL.5QJISPJL" - "1FEF9E96A656B64A"
        "l.QTRURF3Z.VFWAYAQD" - "94FBA398666DD74B"
        "l.QTRURF3Z.5FE9VYIH" - "94FBA398666DD74B"
        "l.QTRURF3Z.BJJI5MOK" - "94FBA398666DD74B"
        "l.QTRURF3Z.NRQZWEDW" - "94FBA398666DD74B"
        "l.QTRURF3Z.XNZZHDAZ" - "94FBA398666DD74B"
        "l.869CZP6U.J1TTBGJV" - "C154A264875CACDB"
        "l.869CZP6U.KHETEDSS" - "C154A264875CACDB"
        "l.869CZP6U.2MCFUB8I" - "C154A264875CACDB"
        "l.869CZP6U.AYTF97XX" - "C154A264875CACDB"
        "l.869CZP6U.MS9PNH46" - "C154A264875CACDB"
        "l.F1WU32KV.MZGRFP0C" - "5BDB282AEE449C73"
        "l.F1WU32KV.7LN0DJHF" - "5BDB282AEE449C73"
        "l.F1WU32KV.J76W8EWF" - "5BDB282AEE449C73"
        "l.F1WU32KV.D8E1MMIQ" - "5BDB282AEE449C73"
        "l.F1WU32KV.Z8FYHE0P" - "5BDB282AEE449C73"
        "l.46XQJKWV.642IAWI6" - "3BB37235E6B67275"
        "l.46XQJKWV.someid" - "3BB37235E6B67275"
            "l.46XQJKWV.someid" - "3BB37235E6B67275"
            "l.46XQJKWV.someid" - "3BB37235E6B67275"
        "l.46XQJKWV.JW49LT18" - "3BB37235E6B67275"
        "l.X7FC01BZ.GUJ5KLAQ" - "6CF410FD9ECE4303"
        "l.X7FC01BZ.someid" - "6CF410FD9ECE4303"
            "l.X7FC01BZ.someid" - "6CF410FD9ECE4303"
            "l.X7FC01BZ.someid" - "6CF410FD9ECE4303"
        "l.X7FC01BZ.5QLJ1VTF" - "6CF410FD9ECE4303"
        "l.BZPAL52J.BJVE4R3D" - "4D0851249141039F"
        "l.BZPAL52J.someid" - "4D0851249141039F"
            "l.BZPAL52J.someid" - "4D0851249141039F"
        "l.BZPAL52J.someid2" - "4D0851249141039F"
        "l.BZPAL52J.CLPXINWZ" - "4D0851249141039F"

