========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Decorators - v0.9
Describe Transpiler initialized.
Starting a 'String[] -> Unfold' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
Preprocessed source code - 363 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://en.test.org/wiki/List_of_fabrics] ') T(TAG|'<QpeudYXy> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'http') T(PROTO_SLASHES|'://') T(DATA|'fabrics.com wool ') T(LINK|'[https://en.test.org/wiki/Wool] ') T(DECORATOR|'{}') T(TAG|'<54vHCQwI>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(LINK|'[https://en.test.org/wiki/Cotton]') T(DECORATOR|'{} ') T(TAG|'<Ll0bDtIQ>') T(SEPARATOR|',\r\n\t') T(DATA|'silk http') T(PROTO_SLASHES|'://') T(DATA|'fabrics.com') T(FORWARD_SLASH|'/') T(DATA|'index.html fabrics ') T(DECORATOR|'{}') T(LINK|'[https://en.test.org/wiki/Silk]') T(TAG|'<6huM44Hm>') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(DECORATOR|'{} ') T(LINK|'[https://en.test.org/wiki/Synthetic]') T(TAG|'<oAgVUPi0>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 363 characters, into 32 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic2.ds"
Preprocessed source code - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\t\r\n\t') T(DATA|'synthetic fabrics https') T(PROTO_SLASHES|'://') T(DATA|'some') T(HYPHEN|'-') T(DATA|'link') T(FORWARD_SLASH|'/\r\n\t') T(TAG|'<i1NLckN6> \r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\r\n\t') T(DECORATOR|'{\r\n\t\tinfo | more info here\r\n\t}\r\n\t') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 193 characters, into 15 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic3.ds"
Preprocessed source code - 108 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(DECORATOR|'{color | red}') T(TAG|'<zAfn39Kh>') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'synthetic fabrics ') T(TAG|'<hOy5oL3B> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 108 characters, into 10 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
Preprocessed source code - 432 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<wIcCuax5>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TAG|'<C92Mf6yV>') T(SEPARATOR|',\r\n\t\r\n    ') T(DATA|'cotton fabrics') T(TAG|'<TxW3Yetp> ') T(DECORATOR|'{color | green}\r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n\r\n    ') T(DATA|'silk fabrics (https') T(PROTO_SLASHES|'://') T(DATA|'www.notube.com') T(FORWARD_SLASH|'/') T(DATA|'watch?v=hTui12lKus) ') T(TAG|'<08yGbnMX>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics (ftp') T(PROTO_SLASHES|'://') T(DATA|'www.notube.com') T(FORWARD_SLASH|'/') T(DATA|'watch?v=hTui12lKus)') T(TAG|'<7MZTHLMY>') T(TERMINATOR|';\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 432 characters, into 30 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
Preprocessed source code - 332 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<Zcm0y9mS> \r\n') T(DECORATOR|'{icon | nutrients.png}\r\n') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<ZxMvmqeZ> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'water ') T(TAG|'<xePTheNI> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';\r\n\r\n') T(DATA|'micronutrients ') T(LINK|'[] ') T(DECORATOR|'{icon | micronutrients.png} ') T(TAG|'<l7qy3zi2>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'vitamins (ABCDEK) ') T(TAG|'<6Nq8AWj7>') T(SEPARATOR|',\r\n    ') T(DATA|'minerals (micronutrients) ') T(TAG|'<jG4U9bwg>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 332 characters, into 26 tokens.
Those were translated to 2 productions, containing 6 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
Preprocessed source code - 336 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<KvtgGtnv>') T(LINK|'[] ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<rUEqmXfk>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(DECORATOR|'{decorator}') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(DECORATOR|'{decorator}') T(TAG|'<wpra8mUV>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<VFoIEr0T>') T(LINK|'[]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<oI5DOuPh>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 336 characters, into 23 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
Preprocessed source code - 275 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<aXLBEer9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'cotton fabrics ') T(TAG|'<evhAIQx4>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<h0e5wwEY> ') T(LINK|'[]') T(DECORATOR|'{}') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<WryZrSIJ>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 275 characters, into 16 tokens.
Those were translated to 1 productions, containing 4 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds"
Preprocessed source code - 245 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<QuvD4gqX> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>        ') T(DATA|'wool fabrics ') T(TAG|'<VBsu8OpW>') T(SEPARATOR|', ') T(DATA|'cotton fabrics ') T(TAG|'<0RdNAvNs> ') T(DECORATOR|'{dec} ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 245 characters, into 13 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
Preprocessed source code - 400 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<qJobcYNC> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<WmtITd8B>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(DECORATOR|'{decorator}') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<KGkvDUZH>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(DECORATOR|'{ de c   or a \t\ttor}') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<BbiZz4Ie>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<gCWv1P46>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';\r\n\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 400 characters, into 23 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
Preprocessed source code - 365 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<xpXWehDW> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<TcD3LcoW>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(TAG|'<thZBzyNc>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<dOlQGMJ4>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<Ln7Y7Dme>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 365 characters, into 21 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"
Preprocessed source code - 274 characters long

Parsing sequence: T(DATA|'платове ') T(TAG|'<ФЛГмссД> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'вълнени платове ') T(TAG|'<ПеП0ТхЗй>') T(LINK|'[https://www.домейн.com/watch?v=hTui12lKus] ') T(DECORATOR|'{декоратор}') T(SEPARATOR|',\r\n\t') T(DATA|'памучни платове ') T(TAG|'<ПТъЗАфЪа>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(DECORATOR|'{декоратори}') T(DECORATOR|'{деко ратор-иййй}') T(SEPARATOR|',\r\n\t') T(DATA|'копринени платове ') T(TAG|'<5Суак3ИЙ>') T(SEPARATOR|',\r\n\t') T(DATA|'синтетични платове ') T(TAG|'<ЛКтрт5КН>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 274 characters, into 22 tokens.
Those were translated to 1 productions, containing 5 entries.
All Files: 11, Succeeded: 11, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "l.S7B4BQAB.QpeudYXy" 

    .Productions
        "l.S7B4BQAB.QpeudYXy" -> "l.S7B4BQAB.54vHCQwI", "l.S7B4BQAB.Ll0bDtIQ", "l.S7B4BQAB.6huM44Hm", "l.S7B4BQAB.oAgVUPi0";
        "l.J8WYPBST.4HK6D16N" -> "l.J8WYPBST.i1NLckN6";
        "l.QHSGKLXZ.zAfn39Kh" -> "l.QHSGKLXZ.hOy5oL3B";
        "l.XVJ8N3Z0.wIcCuax5" -> "l.XVJ8N3Z0.C92Mf6yV", "l.XVJ8N3Z0.TxW3Yetp", "l.XVJ8N3Z0.08yGbnMX", "l.XVJ8N3Z0.7MZTHLMY";
        "l.V7KZKJQ9.Zcm0y9mS" -> "l.V7KZKJQ9.ZxMvmqeZ", "l.V7KZKJQ9.xePTheNI";
        "l.V7KZKJQ9.l7qy3zi2" -> "l.V7KZKJQ9.6Nq8AWj7", "l.V7KZKJQ9.jG4U9bwg";
        "l.C0VMFFU7.KvtgGtnv" -> "l.C0VMFFU7.rUEqmXfk", "l.C0VMFFU7.wpra8mUV", "l.C0VMFFU7.VFoIEr0T", "l.C0VMFFU7.oI5DOuPh";
        "l.5R1N0HS6.aXLBEer9" -> "l.5R1N0HS6.evhAIQx4", "l.5R1N0HS6.h0e5wwEY", "l.5R1N0HS6.WryZrSIJ";
        "l.0EPGEW2I.QuvD4gqX" -> "l.0EPGEW2I.VBsu8OpW", "l.0EPGEW2I.0RdNAvNs";
        "l.D7AO2HCD.qJobcYNC" -> "l.D7AO2HCD.WmtITd8B", "l.D7AO2HCD.KGkvDUZH", "l.D7AO2HCD.BbiZz4Ie", "l.D7AO2HCD.gCWv1P46";
        "l.N08NEZVT.xpXWehDW" -> "l.N08NEZVT.TcD3LcoW", "l.N08NEZVT.thZBzyNc", "l.N08NEZVT.dOlQGMJ4", "l.N08NEZVT.Ln7Y7Dme";
        "l.5XBLVQ4X.ФЛГмссД" -> "l.5XBLVQ4X.ПеП0ТхЗй", "l.5XBLVQ4X.ПТъЗАфЪа", "l.5XBLVQ4X.5Суак3ИЙ", "l.5XBLVQ4X.ЛКтрт5КН";

    .Translations
        "l.S7B4BQAB.QpeudYXy" - "fabrics"
        "l.S7B4BQAB.54vHCQwI" - "http://fabrics.com wool"
        "l.S7B4BQAB.Ll0bDtIQ" - "cotton fabrics"
        "l.S7B4BQAB.6huM44Hm" - "silk http://fabrics.com/index.html fabrics"
        "l.S7B4BQAB.oAgVUPi0" - "synthetic fabrics"
        "l.J8WYPBST.4HK6D16N" - "fabrics"
        "l.J8WYPBST.i1NLckN6" - "synthetic fabrics https://some-link/"
        "l.QHSGKLXZ.zAfn39Kh" - "fabrics"
        "l.QHSGKLXZ.hOy5oL3B" - "synthetic fabrics"
        "l.XVJ8N3Z0.wIcCuax5" - "fabrics"
        "l.XVJ8N3Z0.C92Mf6yV" - "wool fabrics"
        "l.XVJ8N3Z0.TxW3Yetp" - "cotton fabrics"
        "l.XVJ8N3Z0.08yGbnMX" - "silk fabrics (https://www.notube.com/watch?v=hTui12lKus)"
        "l.XVJ8N3Z0.7MZTHLMY" - "synthetic fabrics (ftp://www.notube.com/watch?v=hTui12lKus)"
        "l.V7KZKJQ9.Zcm0y9mS" - "macronutrients"
        "l.V7KZKJQ9.ZxMvmqeZ" - "fiber"
        "l.V7KZKJQ9.xePTheNI" - "water"
        "l.V7KZKJQ9.l7qy3zi2" - "micronutrients"
        "l.V7KZKJQ9.6Nq8AWj7" - "vitamins (ABCDEK)"
        "l.V7KZKJQ9.jG4U9bwg" - "minerals (micronutrients)"
        "l.C0VMFFU7.KvtgGtnv" - "fabrics"
        "l.C0VMFFU7.rUEqmXfk" - "wool fabrics"
        "l.C0VMFFU7.wpra8mUV" - "cotton fabrics"
        "l.C0VMFFU7.VFoIEr0T" - "silk fabrics"
        "l.C0VMFFU7.oI5DOuPh" - "synthetic fabrics"
        "l.5R1N0HS6.aXLBEer9" - "fabrics"
        "l.5R1N0HS6.evhAIQx4" - "cotton fabrics"
        "l.5R1N0HS6.h0e5wwEY" - "silk fabrics"
        "l.5R1N0HS6.WryZrSIJ" - "synthetic fabrics"
        "l.0EPGEW2I.QuvD4gqX" - "fabrics"
        "l.0EPGEW2I.VBsu8OpW" - "wool fabrics"
        "l.0EPGEW2I.0RdNAvNs" - "cotton fabrics"
        "l.D7AO2HCD.qJobcYNC" - "fabrics"
        "l.D7AO2HCD.WmtITd8B" - "wool fabrics"
        "l.D7AO2HCD.KGkvDUZH" - "cotton fabrics"
        "l.D7AO2HCD.BbiZz4Ie" - "silk fabrics"
        "l.D7AO2HCD.gCWv1P46" - "synthetic fabrics"
        "l.N08NEZVT.xpXWehDW" - "fabrics"
        "l.N08NEZVT.TcD3LcoW" - "wool fabrics"
        "l.N08NEZVT.thZBzyNc" - "cotton fabrics"
        "l.N08NEZVT.dOlQGMJ4" - "silk fabrics"
        "l.N08NEZVT.Ln7Y7Dme" - "synthetic fabrics"
        "l.5XBLVQ4X.ФЛГмссД" - "платове"
        "l.5XBLVQ4X.ПеП0ТхЗй" - "вълнени платове"
        "l.5XBLVQ4X.ПТъЗАфЪа" - "памучни платове"
        "l.5XBLVQ4X.5Суак3ИЙ" - "копринени платове"
        "l.5XBLVQ4X.ЛКтрт5КН" - "синтетични платове"

    .Links
        "l.S7B4BQAB.QpeudYXy" - "https://en.test.org/wiki/List_of_fabrics"
        "l.S7B4BQAB.54vHCQwI" - "https://en.test.org/wiki/Wool"
        "l.S7B4BQAB.Ll0bDtIQ" - "https://en.test.org/wiki/Cotton"
        "l.S7B4BQAB.6huM44Hm" - "https://en.test.org/wiki/Silk"
        "l.S7B4BQAB.oAgVUPi0" - "https://en.test.org/wiki/Synthetic"
        "l.J8WYPBST.4HK6D16N" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.J8WYPBST.i1NLckN6" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.QHSGKLXZ.zAfn39Kh" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.QHSGKLXZ.hOy5oL3B" - 
        "l.XVJ8N3Z0.wIcCuax5" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.XVJ8N3Z0.C92Mf6yV" - "https://www.notube.com/watch?v=hTui12lKus"

        "l.XVJ8N3Z0.TxW3Yetp" -
            "https://www.notube.com/watch?v=hTui12lKus"
            "https://www.notube.com/watch?v=hTui12lKus"

        "l.XVJ8N3Z0.08yGbnMX" - 
        "l.XVJ8N3Z0.7MZTHLMY" - 
        "l.V7KZKJQ9.Zcm0y9mS" - 
        "l.V7KZKJQ9.ZxMvmqeZ" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.V7KZKJQ9.xePTheNI" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.V7KZKJQ9.l7qy3zi2" - 
        "l.V7KZKJQ9.6Nq8AWj7" - 
        "l.V7KZKJQ9.jG4U9bwg" - 
        "l.C0VMFFU7.KvtgGtnv" - 
        "l.C0VMFFU7.rUEqmXfk" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.C0VMFFU7.wpra8mUV" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.C0VMFFU7.VFoIEr0T" - 
        "l.C0VMFFU7.oI5DOuPh" - 
        "l.5R1N0HS6.aXLBEer9" - 
        "l.5R1N0HS6.evhAIQx4" - 
        "l.5R1N0HS6.h0e5wwEY" - 
        "l.5R1N0HS6.WryZrSIJ" - 
        "l.0EPGEW2I.QuvD4gqX" - 
        "l.0EPGEW2I.VBsu8OpW" - 
        "l.0EPGEW2I.0RdNAvNs" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.D7AO2HCD.qJobcYNC" - 
        "l.D7AO2HCD.WmtITd8B" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.D7AO2HCD.KGkvDUZH" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.D7AO2HCD.BbiZz4Ie" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.D7AO2HCD.gCWv1P46" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.N08NEZVT.xpXWehDW" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.N08NEZVT.TcD3LcoW" - 
        "l.N08NEZVT.thZBzyNc" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.N08NEZVT.dOlQGMJ4" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.N08NEZVT.Ln7Y7Dme" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.5XBLVQ4X.ФЛГмссД" - 
        "l.5XBLVQ4X.ПеП0ТхЗй" - "https://www.домейн.com/watch?v=hTui12lKus"
        "l.5XBLVQ4X.ПТъЗАфЪа" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.5XBLVQ4X.5Суак3ИЙ" - 
        "l.5XBLVQ4X.ЛКтрт5КН" - 

    .Decorators
        "l.S7B4BQAB.QpeudYXy" - 
        "l.S7B4BQAB.54vHCQwI" - 
        "l.S7B4BQAB.Ll0bDtIQ" - 
        "l.S7B4BQAB.6huM44Hm" - 
        "l.S7B4BQAB.oAgVUPi0" - 
        "l.J8WYPBST.4HK6D16N" - 
        "l.J8WYPBST.i1NLckN6" -  | "more info here"
        "l.QHSGKLXZ.zAfn39Kh" -  | "red"
        "l.QHSGKLXZ.hOy5oL3B" - 
        "l.XVJ8N3Z0.wIcCuax5" - 
        "l.XVJ8N3Z0.C92Mf6yV" - 
        "l.XVJ8N3Z0.TxW3Yetp" -  | "green"
        "l.XVJ8N3Z0.08yGbnMX" - 
        "l.XVJ8N3Z0.7MZTHLMY" - 
        "l.V7KZKJQ9.Zcm0y9mS" -  | "nutrients.png"
        "l.V7KZKJQ9.ZxMvmqeZ" - 
        "l.V7KZKJQ9.xePTheNI" - 
        "l.V7KZKJQ9.l7qy3zi2" -  | "micronutrients.png"
        "l.V7KZKJQ9.6Nq8AWj7" - 
        "l.V7KZKJQ9.jG4U9bwg" - 
        "l.C0VMFFU7.KvtgGtnv" - 
        "l.C0VMFFU7.rUEqmXfk" - "decorator"
        "l.C0VMFFU7.wpra8mUV" - "decorator"
        "l.C0VMFFU7.VFoIEr0T" - 
        "l.C0VMFFU7.oI5DOuPh" - 
        "l.5R1N0HS6.aXLBEer9" - 
        "l.5R1N0HS6.evhAIQx4" - 
        "l.5R1N0HS6.h0e5wwEY" - 
        "l.5R1N0HS6.WryZrSIJ" - 
        "l.0EPGEW2I.QuvD4gqX" - 
        "l.0EPGEW2I.VBsu8OpW" - 
        "l.0EPGEW2I.0RdNAvNs" - "dec"
        "l.D7AO2HCD.qJobcYNC" - 
        "l.D7AO2HCD.WmtITd8B" - "decorator"
        "l.D7AO2HCD.KGkvDUZH" - "de c   or a 		tor"
        "l.D7AO2HCD.BbiZz4Ie" - 
        "l.D7AO2HCD.gCWv1P46" - 
        "l.N08NEZVT.xpXWehDW" - 
        "l.N08NEZVT.TcD3LcoW" - 
        "l.N08NEZVT.thZBzyNc" - 
        "l.N08NEZVT.dOlQGMJ4" - 
        "l.N08NEZVT.Ln7Y7Dme" - 
        "l.5XBLVQ4X.ФЛГмссД" - 
        "l.5XBLVQ4X.ПеП0ТхЗй" - "декоратор"

        "l.5XBLVQ4X.ПТъЗАфЪа" -
            "декоратори"
            "декоратори"

        "l.5XBLVQ4X.5Суак3ИЙ" - 
        "l.5XBLVQ4X.ЛКтрт5КН" - 

    .Tildes

    .ProdidFile
        "l.S7B4BQAB.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.J8WYPBST.4HK6D16N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic2.ds"
        "l.QHSGKLXZ.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic3.ds"
        "l.XVJ8N3Z0.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.V7KZKJQ9.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.C0VMFFU7.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.5R1N0HS6.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
        "l.0EPGEW2I.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds"
        "l.D7AO2HCD.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.N08NEZVT.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.5XBLVQ4X.ФЛГмссД" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"

    .ItemidFile
        "l.S7B4BQAB.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.S7B4BQAB.54vHCQwI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.S7B4BQAB.Ll0bDtIQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.S7B4BQAB.6huM44Hm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.S7B4BQAB.oAgVUPi0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "l.J8WYPBST.4HK6D16N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic2.ds"
        "l.J8WYPBST.i1NLckN6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic2.ds"
        "l.QHSGKLXZ.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic3.ds"
        "l.QHSGKLXZ.hOy5oL3B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic3.ds"
        "l.XVJ8N3Z0.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.XVJ8N3Z0.C92Mf6yV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.XVJ8N3Z0.TxW3Yetp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.XVJ8N3Z0.08yGbnMX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.XVJ8N3Z0.7MZTHLMY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic4.ds"
        "l.V7KZKJQ9.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.ZxMvmqeZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.xePTheNI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.6Nq8AWj7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.V7KZKJQ9.jG4U9bwg" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_twoRoots.ds"
        "l.C0VMFFU7.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.C0VMFFU7.rUEqmXfk" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.C0VMFFU7.wpra8mUV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.C0VMFFU7.VFoIEr0T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.C0VMFFU7.oI5DOuPh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments1.ds"
        "l.5R1N0HS6.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
        "l.5R1N0HS6.evhAIQx4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
        "l.5R1N0HS6.h0e5wwEY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
        "l.5R1N0HS6.WryZrSIJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments2.ds"
        "l.0EPGEW2I.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds"
        "l.0EPGEW2I.VBsu8OpW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds"
        "l.0EPGEW2I.0RdNAvNs" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments3.ds"
        "l.D7AO2HCD.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.D7AO2HCD.WmtITd8B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.D7AO2HCD.KGkvDUZH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.D7AO2HCD.BbiZz4Ie" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.D7AO2HCD.gCWv1P46" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments4.ds"
        "l.N08NEZVT.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.N08NEZVT.TcD3LcoW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.N08NEZVT.thZBzyNc" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.N08NEZVT.dOlQGMJ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.N08NEZVT.Ln7Y7Dme" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.B_comments5.ds"
        "l.5XBLVQ4X.ФЛГмссД" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"
        "l.5XBLVQ4X.ПеП0ТхЗй" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"
        "l.5XBLVQ4X.ПТъЗАфЪа" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"
        "l.5XBLVQ4X.5Суак3ИЙ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"
        "l.5XBLVQ4X.ЛКтрт5КН" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.C_cyrillic.ds"

