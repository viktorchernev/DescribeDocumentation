========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Links - v0.8
Describe Transpiler initialized.
Starting a 'String[] -> Unfold' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
Preprocessed source code - 337 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://en.test.org/wiki/List_of_fabrics] ') T(TAG|'<QpeudYXy> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[https://en.test.org/wiki/Wool | wikipedia] ') T(TAG|'<54vHCQwI>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(LINK|'[https://en.test.org/wiki/Cotton] ') T(TAG|'<Ll0bDtIQ>') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics ') T(LINK|'[https://en.test.org/wiki/Silk | test.org]') T(TAG|'<6huM44Hm>') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[https://en.test.org/wiki/Synthetic]') T(TAG|'<oAgVUPi0>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 337 characters, into 22 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic2.ds"
Preprocessed source code - 133 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\t\r\n\t') T(DATA|'synthetic fabrics ') T(TAG|'<i1NLckN6> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 133 characters, into 9 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic3.ds"
Preprocessed source code - 94 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TAG|'<zAfn39Kh>') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'synthetic fabrics ') T(TAG|'<hOy5oL3B> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 94 characters, into 9 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
Preprocessed source code - 348 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<wIcCuax5>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TAG|'<C92Mf6yV>') T(SEPARATOR|',\r\n\t\r\n    ') T(DATA|'cotton fabrics') T(TAG|'<TxW3Yetp>\r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus | notube]\r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus | yestube]') T(SEPARATOR|',\r\n\r\n    ') T(DATA|'silk fabrics') T(TAG|'<08yGbnMX>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TAG|'<7MZTHLMY>') T(TERMINATOR|';\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 348 characters, into 21 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
Preprocessed source code - 278 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<Zcm0y9mS> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<ZxMvmqeZ> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'water ') T(TAG|'<xePTheNI> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';\r\n\r\n') T(DATA|'micronutrients ') T(LINK|'[] ') T(TAG|'<l7qy3zi2>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'vitamins (ABCDEK) ') T(TAG|'<6Nq8AWj7>') T(SEPARATOR|',\r\n    ') T(DATA|'minerals (micronutrients) ') T(TAG|'<jG4U9bwg>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 278 characters, into 24 tokens.
Those were translated to 2 productions, containing 6 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
Preprocessed source code - 300 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<KvtgGtnv>') T(LINK|'[] ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<rUEqmXfk>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TAG|'<wpra8mUV>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<VFoIEr0T>') T(LINK|'[]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<oI5DOuPh>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 300 characters, into 21 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
Preprocessed source code - 265 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<aXLBEer9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'cotton fabrics ') T(TAG|'<evhAIQx4>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<h0e5wwEY> ') T(LINK|'[]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<WryZrSIJ>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 265 characters, into 15 tokens.
Those were translated to 1 productions, containing 4 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds"
Preprocessed source code - 226 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<QuvD4gqX> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>        ') T(DATA|'wool fabrics ') T(TAG|'<VBsu8OpW>') T(SEPARATOR|', ') T(DATA|'cotton fabrics ') T(TAG|'<0RdNAvNs> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 226 characters, into 12 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
Preprocessed source code - 357 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<qJobcYNC> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<WmtITd8B>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<KGkvDUZH>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<BbiZz4Ie>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<gCWv1P46>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';\r\n\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 357 characters, into 21 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
Preprocessed source code - 353 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<xpXWehDW> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<TcD3LcoW>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(TAG|'<thZBzyNc>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<dOlQGMJ4>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<Ln7Y7Dme>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 353 characters, into 21 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty1.ds"
Preprocessed source code - 64 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<c42Q6wPH>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 64 characters, into 7 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty2.ds"
Preprocessed source code - 65 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<YACUz3H9> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 65 characters, into 7 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty3.ds"
Preprocessed source code - 123 characters long

Parsing sequence: T(DATA|'fabrics\r\n') T(TAG|'<SIrifQYp>\r\n') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\r\n') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\r\n') T(LINK|'[]\r\n') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\r\n') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 123 characters, into 9 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
Preprocessed source code - 233 characters long

Parsing sequence: T(DATA|'платове ') T(TAG|'<ФЛГмссД> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'вълнени платове ') T(TAG|'<ПеП0ТхЗй>') T(LINK|'[https://www.домейн.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n\t') T(DATA|'памучни платове ') T(TAG|'<ПТъЗАфЪа>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n\t') T(DATA|'копринени платове ') T(TAG|'<5Суак3ИЙ>') T(SEPARATOR|',\r\n\t') T(DATA|'синтетични платове ') T(TAG|'<ЛКтрт5КН>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 233 characters, into 19 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
Preprocessed source code - 239 characters long

Parsing sequence: T(DATA|'fa brics ') T(TAG|'<6O4fovPJ>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics ') T(TAG|'<cTk1qeGz>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(ESCAPE_LEFT_SQUARE|'\[') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TAG|'<evssLum4>') T(SEPARATOR|',\r\n    ') T(DATA|'silk ') T(ESCAPE_LEFT_SQUARE|'\[') T(DATA|'https') T(PROTO_SLASHES|'://') T(DATA|'www.notube.com') T(FORWARD_SLASH|'/') T(DATA|'watch?v=hTui12lKus') T(ESCAPE_RIGHT_SQUARE|'\]') T(DATA|'fabrics') T(TAG|'<WR31xpLW>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<sfObQkOm>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 239 characters, into 27 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
Preprocessed source code - 351 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]     ') T(TAG|'<TSbLGnNG> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool   fabrics\t ') T(TAG|'<QWVZ3pp9> ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_LEFT_SQUARE|'\[ ') T(DATA|'fabrics textiles ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]   ') T(TAG|'<75NTfebY>') T(SEPARATOR|',\r\n    ') T(DATA|'silk') T(ESCAPE_LEFT_SQUARE|'\[') T(ESCAPE_LEFT_SQUARE|'\[') T(ESCAPE_LEFT_SQUARE|'\[') T(ESCAPE_RIGHT_SQUARE|'\]') T(DATA|'fabrics ') T(TAG|'<Sqs0lm7S>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'syntic \t\tfabrics ') T(TAG|'<GcZEI9gy>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 351 characters, into 28 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
Preprocessed source code - 297 characters long

Parsing sequence: T(DATA|'fabric     s    ') T(TAG|'<sJZOzSdo>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\t') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool   fabrics') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\t') T(TAG|'<UlJXGWLS>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles  ') T(ESCAPE_RIGHT_SQUARE|'\]') T(TAG|'<d4jKusMe>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'silk') T(ESCAPE_LEFT_SQUARE|'\[') T(DATA|'fabrics ') T(TAG|'<Bgx8M6B1>') T(SEPARATOR|',\r\n    ') T(DATA|'syntic \t\tfabrics ') T(TAG|'<7vbW9VSB>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 297 characters, into 25 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
Preprocessed source code - 159 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<0CmyN2Mb> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<CMxWzMs5> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(LINK|'[http://testlink.com/]') T(TAG|'<hzAzwlx6>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<UHOcZPAm>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<BBmOZjJa>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 159 characters, into 19 tokens.
Those were translated to 2 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
Preprocessed source code - 173 characters long

Parsing sequence: T(DATA|'macronutrients ') T(LINK|'[http://testlink.com/]') T(TAG|'<eQxYylc3> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water ') T(TAG|'<tdgS8qBO>') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(TAG|'<OpdFntBx> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(LINK|'[http://testlink.com/]') T(TAG|'<MLUxjdg8>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<qkVgxZIs>') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 173 characters, into 21 tokens.
Those were translated to 2 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
Preprocessed source code - 243 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<oVs6tsnU> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water ') T(TAG|'<9Y9uFDwu>') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(TAG|'<PALnQoTQ>') T(LINK|'[http://testlink.com/] ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(LINK|'[http://testlink.com/]') T(TAG|'<6hlYVfaz>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(LINK|'[http://testlink.com/]') T(TAG|'<gubSBEDe>') T(TERMINATOR|';\r\n\r\n\t') T(DATA|'somth else ') T(LINK|'[http://testlink.com/]') T(TAG|'<hAyLdw3m>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 243 characters, into 25 tokens.
Those were translated to 2 productions, containing 6 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
Preprocessed source code - 308 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<xkQxOfc9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<CbALGP8d> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<7KNUmetK>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(LINK|'[http://testlink.com/] ') T(TAG|'<6qFQ0HxK>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<o8lvOnlB> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<SbQjE2YS>') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics ') T(TAG|'<CVOSiiAS>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(LINK|'[http://testlink.com/] ') T(TAG|'<1G0hZLJ4>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<ozhHnNOU>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<jMBLOKGE>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 308 characters, into 36 tokens.
Those were translated to 3 productions, containing 10 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
Preprocessed source code - 298 characters long

Parsing sequence: T(DATA|'macronutrients ') T(LINK|'[http://testlink.com/]') T(TAG|'<SxOf3elF> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water ') T(TAG|'<8S3IwDlG>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<RV4OUQoy>') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(TAG|'<G3tWgyDr> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<AwPl7oBK>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<OcIUTGif>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(LINK|'[http://testlink.com/]') T(TAG|'<k543P1uB> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<IZZ9vPiK>') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics ') T(TAG|'<OMH9y9Jn>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<UuA1ITf9>') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 298 characters, into 37 tokens.
Those were translated to 3 productions, containing 10 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
Preprocessed source code - 340 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<VNvl4KbI> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<BNdiPBY8> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<47GG8irk>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<vRje122z>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<4Zohe6QE> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<u87kglXS> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra ') T(LINK|'[http://testlink.com/]') T(TAG|'<VB7KNYBw>') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry ') T(TAG|'<gKznl6RJ>') T(TERMINATOR|';\r\n\t\t\t\r\n\t\t') T(DATA|'informathics ') T(TAG|'<Uon0W1e7>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<rBW9kGDK>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<3QJz4slg>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<X2BTGncx>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 340 characters, into 42 tokens.
Those were translated to 4 productions, containing 12 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
Preprocessed source code - 569 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<ryQ27h6e>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water ') T(TAG|'<hAdLCBLZ>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<GotVxcPm>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(TAG|'<CHcd0L0E>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus] ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<jiSw0LNV>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<TpR3PZdW>') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<qlMb3HAO> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t\r\n\t\t') T(DATA|'informathics ') T(TAG|'<jn0zFcnW>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<JZmdtZj5>') T(SEPARATOR|',\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<bYBIKVXn> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra ') T(TAG|'<nFxP8YKb>') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry ') T(TAG|'<hDNMVYP0>') T(TERMINATOR|';') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 569 characters, into 49 tokens.
Those were translated to 4 productions, containing 12 entries.
All Files: 24, Succeeded: 24, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "l.ZN2KQN4L.QpeudYXy" 

    .Productions
        "l.ZN2KQN4L.QpeudYXy" -> "l.ZN2KQN4L.54vHCQwI", "l.ZN2KQN4L.Ll0bDtIQ", "l.ZN2KQN4L.6huM44Hm", "l.ZN2KQN4L.oAgVUPi0";
        "l.ATTRZCPJ.QE9A1B9S" -> "l.ATTRZCPJ.i1NLckN6";
        "l.8KA4BN3V.zAfn39Kh" -> "l.8KA4BN3V.hOy5oL3B";
        "l.BBP2516L.wIcCuax5" -> "l.BBP2516L.C92Mf6yV", "l.BBP2516L.TxW3Yetp", "l.BBP2516L.08yGbnMX", "l.BBP2516L.7MZTHLMY";
        "l.07ME5B7Q.Zcm0y9mS" -> "l.07ME5B7Q.ZxMvmqeZ", "l.07ME5B7Q.xePTheNI";
        "l.07ME5B7Q.l7qy3zi2" -> "l.07ME5B7Q.6Nq8AWj7", "l.07ME5B7Q.jG4U9bwg";
        "l.GU2NPK65.KvtgGtnv" -> "l.GU2NPK65.rUEqmXfk", "l.GU2NPK65.wpra8mUV", "l.GU2NPK65.VFoIEr0T", "l.GU2NPK65.oI5DOuPh";
        "l.LQCSF60I.aXLBEer9" -> "l.LQCSF60I.evhAIQx4", "l.LQCSF60I.h0e5wwEY", "l.LQCSF60I.WryZrSIJ";
        "l.3XP10XPU.QuvD4gqX" -> "l.3XP10XPU.VBsu8OpW", "l.3XP10XPU.0RdNAvNs";
        "l.2FMABYEA.qJobcYNC" -> "l.2FMABYEA.WmtITd8B", "l.2FMABYEA.KGkvDUZH", "l.2FMABYEA.BbiZz4Ie", "l.2FMABYEA.gCWv1P46";
        "l.RUQVFLQE.xpXWehDW" -> "l.RUQVFLQE.TcD3LcoW", "l.RUQVFLQE.thZBzyNc", "l.RUQVFLQE.dOlQGMJ4", "l.RUQVFLQE.Ln7Y7Dme";
        "l.6DFKQXBG.ФЛГмссД" -> "l.6DFKQXBG.ПеП0ТхЗй", "l.6DFKQXBG.ПТъЗАфЪа", "l.6DFKQXBG.5Суак3ИЙ", "l.6DFKQXBG.ЛКтрт5КН";
        "l.YP1UHKOX.6O4fovPJ" -> "l.YP1UHKOX.cTk1qeGz", "l.YP1UHKOX.evssLum4", "l.YP1UHKOX.WR31xpLW", "l.YP1UHKOX.sfObQkOm";
        "l.SWBH1S54.TSbLGnNG" -> "l.SWBH1S54.QWVZ3pp9", "l.SWBH1S54.75NTfebY", "l.SWBH1S54.Sqs0lm7S", "l.SWBH1S54.GcZEI9gy";
        "l.6URJDWXS.sJZOzSdo" -> "l.6URJDWXS.UlJXGWLS", "l.6URJDWXS.d4jKusMe", "l.6URJDWXS.Bgx8M6B1", "l.6URJDWXS.7vbW9VSB";
        "l.GM2SPH9U.CMxWzMs5" -> "l.GM2SPH9U.hzAzwlx6", "l.GM2SPH9U.UHOcZPAm";
        "l.GM2SPH9U.0CmyN2Mb" -> "l.GM2SPH9U.CMxWzMs5", "l.GM2SPH9U.BBmOZjJa";
        "l.FKISMPHC.OpdFntBx" -> "l.FKISMPHC.MLUxjdg8", "l.FKISMPHC.qkVgxZIs";
        "l.FKISMPHC.eQxYylc3" -> "l.FKISMPHC.tdgS8qBO", "l.FKISMPHC.OpdFntBx";
        "l.OXYNKL4W.PALnQoTQ" -> "l.OXYNKL4W.6hlYVfaz", "l.OXYNKL4W.gubSBEDe";
        "l.OXYNKL4W.oVs6tsnU" -> "l.OXYNKL4W.9Y9uFDwu", "l.OXYNKL4W.PALnQoTQ", "l.OXYNKL4W.hAyLdw3m";
        "l.YUY6P8WN.CbALGP8d" -> "l.YUY6P8WN.7KNUmetK", "l.YUY6P8WN.6qFQ0HxK";
        "l.YUY6P8WN.o8lvOnlB" -> "l.YUY6P8WN.SbQjE2YS", "l.YUY6P8WN.CVOSiiAS", "l.YUY6P8WN.1G0hZLJ4";
        "l.YUY6P8WN.xkQxOfc9" -> "l.YUY6P8WN.CbALGP8d", "l.YUY6P8WN.o8lvOnlB", "l.YUY6P8WN.ozhHnNOU", "l.YUY6P8WN.jMBLOKGE";
        "l.2X5HL6OM.G3tWgyDr" -> "l.2X5HL6OM.AwPl7oBK", "l.2X5HL6OM.OcIUTGif";
        "l.2X5HL6OM.k543P1uB" -> "l.2X5HL6OM.IZZ9vPiK", "l.2X5HL6OM.OMH9y9Jn", "l.2X5HL6OM.UuA1ITf9";
        "l.2X5HL6OM.SxOf3elF" -> "l.2X5HL6OM.8S3IwDlG", "l.2X5HL6OM.RV4OUQoy", "l.2X5HL6OM.G3tWgyDr", "l.2X5HL6OM.k543P1uB";
        "l.R8C66UWB.BNdiPBY8" -> "l.R8C66UWB.47GG8irk", "l.R8C66UWB.vRje122z";
        "l.R8C66UWB.u87kglXS" -> "l.R8C66UWB.VB7KNYBw", "l.R8C66UWB.gKznl6RJ";
        "l.R8C66UWB.4Zohe6QE" -> "l.R8C66UWB.u87kglXS", "l.R8C66UWB.Uon0W1e7", "l.R8C66UWB.rBW9kGDK";
        "l.R8C66UWB.VNvl4KbI" -> "l.R8C66UWB.BNdiPBY8", "l.R8C66UWB.4Zohe6QE", "l.R8C66UWB.3QJz4slg", "l.R8C66UWB.X2BTGncx";
        "l.UQB6107R.CHcd0L0E" -> "l.UQB6107R.jiSw0LNV", "l.UQB6107R.TpR3PZdW";
        "l.UQB6107R.bYBIKVXn" -> "l.UQB6107R.nFxP8YKb", "l.UQB6107R.hDNMVYP0";
        "l.UQB6107R.qlMb3HAO" -> "l.UQB6107R.jn0zFcnW", "l.UQB6107R.JZmdtZj5", "l.UQB6107R.bYBIKVXn";
        "l.UQB6107R.ryQ27h6e" -> "l.UQB6107R.hAdLCBLZ", "l.UQB6107R.GotVxcPm", "l.UQB6107R.CHcd0L0E", "l.UQB6107R.qlMb3HAO";

    .Translations
        "l.ZN2KQN4L.QpeudYXy" - "fabrics"
        "l.ZN2KQN4L.54vHCQwI" - "wool fabrics"
        "l.ZN2KQN4L.Ll0bDtIQ" - "cotton fabrics"
        "l.ZN2KQN4L.6huM44Hm" - "silk fabrics"
        "l.ZN2KQN4L.oAgVUPi0" - "synthetic fabrics"
        "l.ATTRZCPJ.QE9A1B9S" - "fabrics"
        "l.ATTRZCPJ.i1NLckN6" - "synthetic fabrics"
        "l.8KA4BN3V.zAfn39Kh" - "fabrics"
        "l.8KA4BN3V.hOy5oL3B" - "synthetic fabrics"
        "l.BBP2516L.wIcCuax5" - "fabrics"
        "l.BBP2516L.C92Mf6yV" - "wool fabrics"
        "l.BBP2516L.TxW3Yetp" - "cotton fabrics"
        "l.BBP2516L.08yGbnMX" - "silk fabrics"
        "l.BBP2516L.7MZTHLMY" - "synthetic fabrics"
        "l.07ME5B7Q.Zcm0y9mS" - "macronutrients"
        "l.07ME5B7Q.ZxMvmqeZ" - "fiber"
        "l.07ME5B7Q.xePTheNI" - "water"
        "l.07ME5B7Q.l7qy3zi2" - "micronutrients"
        "l.07ME5B7Q.6Nq8AWj7" - "vitamins (ABCDEK)"
        "l.07ME5B7Q.jG4U9bwg" - "minerals (micronutrients)"
        "l.GU2NPK65.KvtgGtnv" - "fabrics"
        "l.GU2NPK65.rUEqmXfk" - "wool fabrics"
        "l.GU2NPK65.wpra8mUV" - "cotton fabrics"
        "l.GU2NPK65.VFoIEr0T" - "silk fabrics"
        "l.GU2NPK65.oI5DOuPh" - "synthetic fabrics"
        "l.LQCSF60I.aXLBEer9" - "fabrics"
        "l.LQCSF60I.evhAIQx4" - "cotton fabrics"
        "l.LQCSF60I.h0e5wwEY" - "silk fabrics"
        "l.LQCSF60I.WryZrSIJ" - "synthetic fabrics"
        "l.3XP10XPU.QuvD4gqX" - "fabrics"
        "l.3XP10XPU.VBsu8OpW" - "wool fabrics"
        "l.3XP10XPU.0RdNAvNs" - "cotton fabrics"
        "l.2FMABYEA.qJobcYNC" - "fabrics"
        "l.2FMABYEA.WmtITd8B" - "wool fabrics"
        "l.2FMABYEA.KGkvDUZH" - "cotton fabrics"
        "l.2FMABYEA.BbiZz4Ie" - "silk fabrics"
        "l.2FMABYEA.gCWv1P46" - "synthetic fabrics"
        "l.RUQVFLQE.xpXWehDW" - "fabrics"
        "l.RUQVFLQE.TcD3LcoW" - "wool fabrics"
        "l.RUQVFLQE.thZBzyNc" - "cotton fabrics"
        "l.RUQVFLQE.dOlQGMJ4" - "silk fabrics"
        "l.RUQVFLQE.Ln7Y7Dme" - "synthetic fabrics"
        "l.2MSWM5L0.c42Q6wPH" - "fabrics"
        "l.9HCDAUOK.YACUz3H9" - "fabrics"
        "l.5V2S0KTJ.SIrifQYp" - "fabrics"
        "l.6DFKQXBG.ФЛГмссД" - "платове"
        "l.6DFKQXBG.ПеП0ТхЗй" - "вълнени платове"
        "l.6DFKQXBG.ПТъЗАфЪа" - "памучни платове"
        "l.6DFKQXBG.5Суак3ИЙ" - "копринени платове"
        "l.6DFKQXBG.ЛКтрт5КН" - "синтетични платове"
        "l.YP1UHKOX.6O4fovPJ" - "fa brics"
        "l.YP1UHKOX.cTk1qeGz" - "wool fabrics"
        "l.YP1UHKOX.evssLum4" - "cotton fabrics \["
        "l.YP1UHKOX.WR31xpLW" - "silk \[https://www.notube.com/watch?v=hTui12lKus\]fabrics"
        "l.YP1UHKOX.sfObQkOm" - "synthetic fabrics"
        "l.SWBH1S54.TSbLGnNG" - "fabric     s"
        "l.SWBH1S54.QWVZ3pp9" - "wool   fabrics"
        "l.SWBH1S54.75NTfebY" - "cotton\[ fabrics textiles"
        "l.SWBH1S54.Sqs0lm7S" - "silk\[\[\[\]fabrics"
        "l.SWBH1S54.GcZEI9gy" - "syntic 		fabrics"
        "l.6URJDWXS.sJZOzSdo" - "fabric     s"
        "l.6URJDWXS.UlJXGWLS" - "wool   fabrics"
        "l.6URJDWXS.d4jKusMe" - "cotton\, fabrics textiles  \]"
        "l.6URJDWXS.Bgx8M6B1" - "silk\[fabrics"
        "l.6URJDWXS.7vbW9VSB" - "syntic 		fabrics"
        "l.GM2SPH9U.0CmyN2Mb" - "macronutrients"
        "l.GM2SPH9U.CMxWzMs5" - "fiber"
        "l.GM2SPH9U.hzAzwlx6" - "what"
        "l.GM2SPH9U.UHOcZPAm" - "not"
        "l.GM2SPH9U.BBmOZjJa" - "water"
        "l.FKISMPHC.eQxYylc3" - "macronutrients"
        "l.FKISMPHC.tdgS8qBO" - "water"
        "l.FKISMPHC.OpdFntBx" - "fiber"
        "l.FKISMPHC.MLUxjdg8" - "what"
        "l.FKISMPHC.qkVgxZIs" - "not"
        "l.OXYNKL4W.oVs6tsnU" - "macronutrients"
        "l.OXYNKL4W.9Y9uFDwu" - "water"
        "l.OXYNKL4W.PALnQoTQ" - "fiber"
        "l.OXYNKL4W.6hlYVfaz" - "what"
        "l.OXYNKL4W.gubSBEDe" - "not"
        "l.OXYNKL4W.hAyLdw3m" - "somth else"
        "l.YUY6P8WN.xkQxOfc9" - "macronutrients"
        "l.YUY6P8WN.CbALGP8d" - "fiber"
        "l.YUY6P8WN.7KNUmetK" - "what"
        "l.YUY6P8WN.6qFQ0HxK" - "not"
        "l.YUY6P8WN.o8lvOnlB" - "science"
        "l.YUY6P8WN.SbQjE2YS" - "math"
        "l.YUY6P8WN.CVOSiiAS" - "informathics"
        "l.YUY6P8WN.1G0hZLJ4" - "medicine"
        "l.YUY6P8WN.ozhHnNOU" - "water"
        "l.YUY6P8WN.jMBLOKGE" - "salt"
        "l.2X5HL6OM.SxOf3elF" - "macronutrients"
        "l.2X5HL6OM.8S3IwDlG" - "water"
        "l.2X5HL6OM.RV4OUQoy" - "salt"
        "l.2X5HL6OM.G3tWgyDr" - "fiber"
        "l.2X5HL6OM.AwPl7oBK" - "what"
        "l.2X5HL6OM.OcIUTGif" - "not"
        "l.2X5HL6OM.k543P1uB" - "science"
        "l.2X5HL6OM.IZZ9vPiK" - "math"
        "l.2X5HL6OM.OMH9y9Jn" - "informathics"
        "l.2X5HL6OM.UuA1ITf9" - "medicine"
        "l.R8C66UWB.VNvl4KbI" - "macronutrients"
        "l.R8C66UWB.BNdiPBY8" - "fiber"
        "l.R8C66UWB.47GG8irk" - "what"
        "l.R8C66UWB.vRje122z" - "not"
        "l.R8C66UWB.4Zohe6QE" - "science"
        "l.R8C66UWB.u87kglXS" - "math"
        "l.R8C66UWB.VB7KNYBw" - "algebra"
        "l.R8C66UWB.gKznl6RJ" - "geometry"
        "l.R8C66UWB.Uon0W1e7" - "informathics"
        "l.R8C66UWB.rBW9kGDK" - "medicine"
        "l.R8C66UWB.3QJz4slg" - "water"
        "l.R8C66UWB.X2BTGncx" - "salt"
        "l.UQB6107R.ryQ27h6e" - "macronutrients"
        "l.UQB6107R.hAdLCBLZ" - "water"
        "l.UQB6107R.GotVxcPm" - "salt"
        "l.UQB6107R.CHcd0L0E" - "fiber"
        "l.UQB6107R.jiSw0LNV" - "what"
        "l.UQB6107R.TpR3PZdW" - "not"
        "l.UQB6107R.qlMb3HAO" - "science"
        "l.UQB6107R.jn0zFcnW" - "informathics"
        "l.UQB6107R.JZmdtZj5" - "medicine"
        "l.UQB6107R.bYBIKVXn" - "math"
        "l.UQB6107R.nFxP8YKb" - "algebra"
        "l.UQB6107R.hDNMVYP0" - "geometry"

    .Links
        "l.ZN2KQN4L.QpeudYXy" - "https://en.test.org/wiki/List_of_fabrics"
        "l.ZN2KQN4L.54vHCQwI" -  | "wikipedia"
        "l.ZN2KQN4L.Ll0bDtIQ" - "https://en.test.org/wiki/Cotton"
        "l.ZN2KQN4L.6huM44Hm" -  | "test.org"
        "l.ZN2KQN4L.oAgVUPi0" - "https://en.test.org/wiki/Synthetic"
        "l.ATTRZCPJ.QE9A1B9S" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.ATTRZCPJ.i1NLckN6" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.8KA4BN3V.zAfn39Kh" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.8KA4BN3V.hOy5oL3B" - 
        "l.BBP2516L.wIcCuax5" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.BBP2516L.C92Mf6yV" - "https://www.notube.com/watch?v=hTui12lKus"

        "l.BBP2516L.TxW3Yetp" -
             | "notube"
             | "yestube"

        "l.BBP2516L.08yGbnMX" - 
        "l.BBP2516L.7MZTHLMY" - 
        "l.07ME5B7Q.Zcm0y9mS" - 
        "l.07ME5B7Q.ZxMvmqeZ" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.07ME5B7Q.xePTheNI" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.07ME5B7Q.l7qy3zi2" - 
        "l.07ME5B7Q.6Nq8AWj7" - 
        "l.07ME5B7Q.jG4U9bwg" - 
        "l.GU2NPK65.KvtgGtnv" - 
        "l.GU2NPK65.rUEqmXfk" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.GU2NPK65.wpra8mUV" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.GU2NPK65.VFoIEr0T" - 
        "l.GU2NPK65.oI5DOuPh" - 
        "l.LQCSF60I.aXLBEer9" - 
        "l.LQCSF60I.evhAIQx4" - 
        "l.LQCSF60I.h0e5wwEY" - 
        "l.LQCSF60I.WryZrSIJ" - 
        "l.3XP10XPU.QuvD4gqX" - 
        "l.3XP10XPU.VBsu8OpW" - 
        "l.3XP10XPU.0RdNAvNs" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.2FMABYEA.qJobcYNC" - 
        "l.2FMABYEA.WmtITd8B" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.2FMABYEA.KGkvDUZH" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.2FMABYEA.BbiZz4Ie" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.2FMABYEA.gCWv1P46" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.RUQVFLQE.xpXWehDW" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.RUQVFLQE.TcD3LcoW" - 
        "l.RUQVFLQE.thZBzyNc" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.RUQVFLQE.dOlQGMJ4" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.RUQVFLQE.Ln7Y7Dme" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.2MSWM5L0.c42Q6wPH" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.9HCDAUOK.YACUz3H9" - "https://www.notube.com/watch?v=hTui12lKus"

        "l.5V2S0KTJ.SIrifQYp" -
            "https://www.notube.com/watch?v=hTui12lKus"
            "https://www.notube.com/watch?v=hTui12lKus"

        "l.6DFKQXBG.ФЛГмссД" - 
        "l.6DFKQXBG.ПеП0ТхЗй" - "https://www.домейн.com/watch?v=hTui12lKus"
        "l.6DFKQXBG.ПТъЗАфЪа" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.6DFKQXBG.5Суак3ИЙ" - 
        "l.6DFKQXBG.ЛКтрт5КН" - 
        "l.YP1UHKOX.6O4fovPJ" - 
        "l.YP1UHKOX.cTk1qeGz" - 
        "l.YP1UHKOX.evssLum4" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.YP1UHKOX.WR31xpLW" - 
        "l.YP1UHKOX.sfObQkOm" - 
        "l.SWBH1S54.TSbLGnNG" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.SWBH1S54.QWVZ3pp9" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.SWBH1S54.75NTfebY" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.SWBH1S54.Sqs0lm7S" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.SWBH1S54.GcZEI9gy" - 
        "l.6URJDWXS.sJZOzSdo" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.6URJDWXS.UlJXGWLS" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.6URJDWXS.d4jKusMe" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.6URJDWXS.Bgx8M6B1" - 
        "l.6URJDWXS.7vbW9VSB" - 
        "l.GM2SPH9U.0CmyN2Mb" - 
        "l.GM2SPH9U.CMxWzMs5" - 
        "l.GM2SPH9U.hzAzwlx6" - "http://testlink.com/"
        "l.GM2SPH9U.UHOcZPAm" - 
        "l.GM2SPH9U.BBmOZjJa" - 
        "l.FKISMPHC.eQxYylc3" - "http://testlink.com/"
        "l.FKISMPHC.tdgS8qBO" - 
        "l.FKISMPHC.OpdFntBx" - 
        "l.FKISMPHC.MLUxjdg8" - "http://testlink.com/"
        "l.FKISMPHC.qkVgxZIs" - 
        "l.OXYNKL4W.oVs6tsnU" - 
        "l.OXYNKL4W.9Y9uFDwu" - 
        "l.OXYNKL4W.PALnQoTQ" - "http://testlink.com/"
        "l.OXYNKL4W.6hlYVfaz" - "http://testlink.com/"
        "l.OXYNKL4W.gubSBEDe" - "http://testlink.com/"
        "l.OXYNKL4W.hAyLdw3m" - "http://testlink.com/"
        "l.YUY6P8WN.xkQxOfc9" - 
        "l.YUY6P8WN.CbALGP8d" - 
        "l.YUY6P8WN.7KNUmetK" - 
        "l.YUY6P8WN.6qFQ0HxK" - "http://testlink.com/"
        "l.YUY6P8WN.o8lvOnlB" - 
        "l.YUY6P8WN.SbQjE2YS" - 
        "l.YUY6P8WN.CVOSiiAS" - 
        "l.YUY6P8WN.1G0hZLJ4" - "http://testlink.com/"
        "l.YUY6P8WN.ozhHnNOU" - 
        "l.YUY6P8WN.jMBLOKGE" - 
        "l.2X5HL6OM.SxOf3elF" - "http://testlink.com/"
        "l.2X5HL6OM.8S3IwDlG" - 
        "l.2X5HL6OM.RV4OUQoy" - 
        "l.2X5HL6OM.G3tWgyDr" - 
        "l.2X5HL6OM.AwPl7oBK" - 
        "l.2X5HL6OM.OcIUTGif" - 
        "l.2X5HL6OM.k543P1uB" - "http://testlink.com/"
        "l.2X5HL6OM.IZZ9vPiK" - 
        "l.2X5HL6OM.OMH9y9Jn" - 
        "l.2X5HL6OM.UuA1ITf9" - 
        "l.R8C66UWB.VNvl4KbI" - 
        "l.R8C66UWB.BNdiPBY8" - 
        "l.R8C66UWB.47GG8irk" - 
        "l.R8C66UWB.vRje122z" - 
        "l.R8C66UWB.4Zohe6QE" - 
        "l.R8C66UWB.u87kglXS" - 
        "l.R8C66UWB.VB7KNYBw" - "http://testlink.com/"
        "l.R8C66UWB.gKznl6RJ" - 
        "l.R8C66UWB.Uon0W1e7" - 
        "l.R8C66UWB.rBW9kGDK" - 
        "l.R8C66UWB.3QJz4slg" - 
        "l.R8C66UWB.X2BTGncx" - 
        "l.UQB6107R.ryQ27h6e" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.hAdLCBLZ" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.GotVxcPm" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.CHcd0L0E" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.jiSw0LNV" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.TpR3PZdW" - "https://www.notube.com/watch?v=hTui12lKus"
        "l.UQB6107R.qlMb3HAO" - 
        "l.UQB6107R.jn0zFcnW" - 
        "l.UQB6107R.JZmdtZj5" - 
        "l.UQB6107R.bYBIKVXn" - 
        "l.UQB6107R.nFxP8YKb" - 
        "l.UQB6107R.hDNMVYP0" - 

    .Decorators
        "l.ZN2KQN4L.QpeudYXy" - 
        "l.ZN2KQN4L.54vHCQwI" - 
        "l.ZN2KQN4L.Ll0bDtIQ" - 
        "l.ZN2KQN4L.6huM44Hm" - 
        "l.ZN2KQN4L.oAgVUPi0" - 
        "l.ATTRZCPJ.QE9A1B9S" - 
        "l.ATTRZCPJ.i1NLckN6" - 
        "l.8KA4BN3V.zAfn39Kh" - 
        "l.8KA4BN3V.hOy5oL3B" - 
        "l.BBP2516L.wIcCuax5" - 
        "l.BBP2516L.C92Mf6yV" - 
        "l.BBP2516L.TxW3Yetp" - 
        "l.BBP2516L.08yGbnMX" - 
        "l.BBP2516L.7MZTHLMY" - 
        "l.07ME5B7Q.Zcm0y9mS" - 
        "l.07ME5B7Q.ZxMvmqeZ" - 
        "l.07ME5B7Q.xePTheNI" - 
        "l.07ME5B7Q.l7qy3zi2" - 
        "l.07ME5B7Q.6Nq8AWj7" - 
        "l.07ME5B7Q.jG4U9bwg" - 
        "l.GU2NPK65.KvtgGtnv" - 
        "l.GU2NPK65.rUEqmXfk" - 
        "l.GU2NPK65.wpra8mUV" - 
        "l.GU2NPK65.VFoIEr0T" - 
        "l.GU2NPK65.oI5DOuPh" - 
        "l.LQCSF60I.aXLBEer9" - 
        "l.LQCSF60I.evhAIQx4" - 
        "l.LQCSF60I.h0e5wwEY" - 
        "l.LQCSF60I.WryZrSIJ" - 
        "l.3XP10XPU.QuvD4gqX" - 
        "l.3XP10XPU.VBsu8OpW" - 
        "l.3XP10XPU.0RdNAvNs" - 
        "l.2FMABYEA.qJobcYNC" - 
        "l.2FMABYEA.WmtITd8B" - 
        "l.2FMABYEA.KGkvDUZH" - 
        "l.2FMABYEA.BbiZz4Ie" - 
        "l.2FMABYEA.gCWv1P46" - 
        "l.RUQVFLQE.xpXWehDW" - 
        "l.RUQVFLQE.TcD3LcoW" - 
        "l.RUQVFLQE.thZBzyNc" - 
        "l.RUQVFLQE.dOlQGMJ4" - 
        "l.RUQVFLQE.Ln7Y7Dme" - 
        "l.2MSWM5L0.c42Q6wPH" - 
        "l.9HCDAUOK.YACUz3H9" - 
        "l.5V2S0KTJ.SIrifQYp" - 
        "l.6DFKQXBG.ФЛГмссД" - 
        "l.6DFKQXBG.ПеП0ТхЗй" - 
        "l.6DFKQXBG.ПТъЗАфЪа" - 
        "l.6DFKQXBG.5Суак3ИЙ" - 
        "l.6DFKQXBG.ЛКтрт5КН" - 
        "l.YP1UHKOX.6O4fovPJ" - 
        "l.YP1UHKOX.cTk1qeGz" - 
        "l.YP1UHKOX.evssLum4" - 
        "l.YP1UHKOX.WR31xpLW" - 
        "l.YP1UHKOX.sfObQkOm" - 
        "l.SWBH1S54.TSbLGnNG" - 
        "l.SWBH1S54.QWVZ3pp9" - 
        "l.SWBH1S54.75NTfebY" - 
        "l.SWBH1S54.Sqs0lm7S" - 
        "l.SWBH1S54.GcZEI9gy" - 
        "l.6URJDWXS.sJZOzSdo" - 
        "l.6URJDWXS.UlJXGWLS" - 
        "l.6URJDWXS.d4jKusMe" - 
        "l.6URJDWXS.Bgx8M6B1" - 
        "l.6URJDWXS.7vbW9VSB" - 
        "l.GM2SPH9U.0CmyN2Mb" - 
        "l.GM2SPH9U.CMxWzMs5" - 
        "l.GM2SPH9U.hzAzwlx6" - 
        "l.GM2SPH9U.UHOcZPAm" - 
        "l.GM2SPH9U.BBmOZjJa" - 
        "l.FKISMPHC.eQxYylc3" - 
        "l.FKISMPHC.tdgS8qBO" - 
        "l.FKISMPHC.OpdFntBx" - 
        "l.FKISMPHC.MLUxjdg8" - 
        "l.FKISMPHC.qkVgxZIs" - 
        "l.OXYNKL4W.oVs6tsnU" - 
        "l.OXYNKL4W.9Y9uFDwu" - 
        "l.OXYNKL4W.PALnQoTQ" - 
        "l.OXYNKL4W.6hlYVfaz" - 
        "l.OXYNKL4W.gubSBEDe" - 
        "l.OXYNKL4W.hAyLdw3m" - 
        "l.YUY6P8WN.xkQxOfc9" - 
        "l.YUY6P8WN.CbALGP8d" - 
        "l.YUY6P8WN.7KNUmetK" - 
        "l.YUY6P8WN.6qFQ0HxK" - 
        "l.YUY6P8WN.o8lvOnlB" - 
        "l.YUY6P8WN.SbQjE2YS" - 
        "l.YUY6P8WN.CVOSiiAS" - 
        "l.YUY6P8WN.1G0hZLJ4" - 
        "l.YUY6P8WN.ozhHnNOU" - 
        "l.YUY6P8WN.jMBLOKGE" - 
        "l.2X5HL6OM.SxOf3elF" - 
        "l.2X5HL6OM.8S3IwDlG" - 
        "l.2X5HL6OM.RV4OUQoy" - 
        "l.2X5HL6OM.G3tWgyDr" - 
        "l.2X5HL6OM.AwPl7oBK" - 
        "l.2X5HL6OM.OcIUTGif" - 
        "l.2X5HL6OM.k543P1uB" - 
        "l.2X5HL6OM.IZZ9vPiK" - 
        "l.2X5HL6OM.OMH9y9Jn" - 
        "l.2X5HL6OM.UuA1ITf9" - 
        "l.R8C66UWB.VNvl4KbI" - 
        "l.R8C66UWB.BNdiPBY8" - 
        "l.R8C66UWB.47GG8irk" - 
        "l.R8C66UWB.vRje122z" - 
        "l.R8C66UWB.4Zohe6QE" - 
        "l.R8C66UWB.u87kglXS" - 
        "l.R8C66UWB.VB7KNYBw" - 
        "l.R8C66UWB.gKznl6RJ" - 
        "l.R8C66UWB.Uon0W1e7" - 
        "l.R8C66UWB.rBW9kGDK" - 
        "l.R8C66UWB.3QJz4slg" - 
        "l.R8C66UWB.X2BTGncx" - 
        "l.UQB6107R.ryQ27h6e" - 
        "l.UQB6107R.hAdLCBLZ" - 
        "l.UQB6107R.GotVxcPm" - 
        "l.UQB6107R.CHcd0L0E" - 
        "l.UQB6107R.jiSw0LNV" - 
        "l.UQB6107R.TpR3PZdW" - 
        "l.UQB6107R.qlMb3HAO" - 
        "l.UQB6107R.jn0zFcnW" - 
        "l.UQB6107R.JZmdtZj5" - 
        "l.UQB6107R.bYBIKVXn" - 
        "l.UQB6107R.nFxP8YKb" - 
        "l.UQB6107R.hDNMVYP0" - 

    .Tildes

    .ProdidFile
        "l.ZN2KQN4L.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ATTRZCPJ.QE9A1B9S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic2.ds"
        "l.8KA4BN3V.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic3.ds"
        "l.BBP2516L.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.07ME5B7Q.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.GU2NPK65.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.LQCSF60I.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
        "l.3XP10XPU.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds"
        "l.2FMABYEA.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.RUQVFLQE.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.2MSWM5L0.c42Q6wPH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty1.ds"
        "l.9HCDAUOK.YACUz3H9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty2.ds"
        "l.5V2S0KTJ.SIrifQYp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty3.ds"
        "l.6DFKQXBG.ФЛГмссД" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.YP1UHKOX.6O4fovPJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.SWBH1S54.TSbLGnNG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.6URJDWXS.sJZOzSdo" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.GM2SPH9U.CMxWzMs5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.GM2SPH9U.0CmyN2Mb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.FKISMPHC.OpdFntBx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.FKISMPHC.eQxYylc3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.OXYNKL4W.PALnQoTQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.oVs6tsnU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.YUY6P8WN.CbALGP8d" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.o8lvOnlB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.xkQxOfc9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.2X5HL6OM.G3tWgyDr" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.k543P1uB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.SxOf3elF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.R8C66UWB.BNdiPBY8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.u87kglXS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.4Zohe6QE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.VNvl4KbI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.UQB6107R.CHcd0L0E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.bYBIKVXn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.qlMb3HAO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.ryQ27h6e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"

    .ItemidFile
        "l.ZN2KQN4L.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ZN2KQN4L.54vHCQwI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ZN2KQN4L.Ll0bDtIQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ZN2KQN4L.6huM44Hm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ZN2KQN4L.oAgVUPi0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "l.ATTRZCPJ.QE9A1B9S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic2.ds"
        "l.ATTRZCPJ.i1NLckN6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic2.ds"
        "l.8KA4BN3V.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic3.ds"
        "l.8KA4BN3V.hOy5oL3B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic3.ds"
        "l.BBP2516L.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.BBP2516L.C92Mf6yV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.BBP2516L.TxW3Yetp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.BBP2516L.08yGbnMX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.BBP2516L.7MZTHLMY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic4.ds"
        "l.07ME5B7Q.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.ZxMvmqeZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.xePTheNI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.6Nq8AWj7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.07ME5B7Q.jG4U9bwg" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_twoRoots.ds"
        "l.GU2NPK65.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.GU2NPK65.rUEqmXfk" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.GU2NPK65.wpra8mUV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.GU2NPK65.VFoIEr0T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.GU2NPK65.oI5DOuPh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments1.ds"
        "l.LQCSF60I.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
        "l.LQCSF60I.evhAIQx4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
        "l.LQCSF60I.h0e5wwEY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
        "l.LQCSF60I.WryZrSIJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments2.ds"
        "l.3XP10XPU.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds"
        "l.3XP10XPU.VBsu8OpW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds"
        "l.3XP10XPU.0RdNAvNs" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments3.ds"
        "l.2FMABYEA.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.2FMABYEA.WmtITd8B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.2FMABYEA.KGkvDUZH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.2FMABYEA.BbiZz4Ie" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.2FMABYEA.gCWv1P46" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments4.ds"
        "l.RUQVFLQE.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.RUQVFLQE.TcD3LcoW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.RUQVFLQE.thZBzyNc" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.RUQVFLQE.dOlQGMJ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.RUQVFLQE.Ln7Y7Dme" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.B_comments5.ds"
        "l.2MSWM5L0.c42Q6wPH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty1.ds"
        "l.9HCDAUOK.YACUz3H9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty2.ds"
        "l.5V2S0KTJ.SIrifQYp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.C_empty3.ds"
        "l.6DFKQXBG.ФЛГмссД" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.6DFKQXBG.ПеП0ТхЗй" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.6DFKQXBG.ПТъЗАфЪа" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.6DFKQXBG.5Суак3ИЙ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.6DFKQXBG.ЛКтрт5КН" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_cyrillic.ds"
        "l.YP1UHKOX.6O4fovPJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.YP1UHKOX.cTk1qeGz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.YP1UHKOX.evssLum4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.YP1UHKOX.WR31xpLW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.YP1UHKOX.sfObQkOm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.D_escaped_double_characters1.ds"
        "l.SWBH1S54.TSbLGnNG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.SWBH1S54.QWVZ3pp9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.SWBH1S54.75NTfebY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.SWBH1S54.Sqs0lm7S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.SWBH1S54.GcZEI9gy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_N.ds"
        "l.6URJDWXS.sJZOzSdo" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.6URJDWXS.UlJXGWLS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.6URJDWXS.d4jKusMe" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.6URJDWXS.Bgx8M6B1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.6URJDWXS.7vbW9VSB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.E_spaces_escapes_RN.ds"
        "l.GM2SPH9U.0CmyN2Mb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.GM2SPH9U.CMxWzMs5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.GM2SPH9U.hzAzwlx6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.GM2SPH9U.UHOcZPAm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.GM2SPH9U.BBmOZjJa" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production1.ds"
        "l.FKISMPHC.eQxYylc3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.FKISMPHC.tdgS8qBO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.FKISMPHC.OpdFntBx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.FKISMPHC.MLUxjdg8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.FKISMPHC.qkVgxZIs" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production2.ds"
        "l.OXYNKL4W.oVs6tsnU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.9Y9uFDwu" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.PALnQoTQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.6hlYVfaz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.gubSBEDe" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.OXYNKL4W.hAyLdw3m" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production3.ds"
        "l.YUY6P8WN.xkQxOfc9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.CbALGP8d" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.7KNUmetK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.6qFQ0HxK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.o8lvOnlB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.SbQjE2YS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.CVOSiiAS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.1G0hZLJ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.ozhHnNOU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.YUY6P8WN.jMBLOKGE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production4.ds"
        "l.2X5HL6OM.SxOf3elF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.8S3IwDlG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.RV4OUQoy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.G3tWgyDr" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.AwPl7oBK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.OcIUTGif" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.k543P1uB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.IZZ9vPiK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.OMH9y9Jn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.2X5HL6OM.UuA1ITf9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production5.ds"
        "l.R8C66UWB.VNvl4KbI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.BNdiPBY8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.47GG8irk" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.vRje122z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.4Zohe6QE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.u87kglXS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.VB7KNYBw" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.gKznl6RJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.Uon0W1e7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.rBW9kGDK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.3QJz4slg" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.R8C66UWB.X2BTGncx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production6.ds"
        "l.UQB6107R.ryQ27h6e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.hAdLCBLZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.GotVxcPm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.CHcd0L0E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.jiSw0LNV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.TpR3PZdW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.qlMb3HAO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.jn0zFcnW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.JZmdtZj5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.bYBIKVXn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.nFxP8YKb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"
        "l.UQB6107R.hDNMVYP0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.F_production_in_production7.ds"

