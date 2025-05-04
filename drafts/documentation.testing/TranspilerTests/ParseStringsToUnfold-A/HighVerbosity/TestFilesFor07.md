========================================
Source Code File Names (between the arrows)
========================================

🡆Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds
Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Tags - v0.7
Describe Transpiler initialized.
Starting a 'String[] -> Unfold' operation...
STOP_ON_ERROR - False
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
Preprocessed source code - 138 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<QpeudYXy> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(TAG|'<54vHCQwI>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(TAG|'<Ll0bDtIQ>') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics ') T(TAG|'<6huM44Hm>') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(TAG|'<oAgVUPi0>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 138 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic2.ds"
Preprocessed source code - 46 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\t\r\n\t') T(DATA|'synthetic fabrics ') T(TAG|'<i1NLckN6>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 46 characters, into 7 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic3.ds"
Preprocessed source code - 51 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<zAfn39Kh>') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'synthetic fabrics ') T(TAG|'<hOy5oL3B> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 51 characters, into 8 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
Preprocessed source code - 146 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<wIcCuax5>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool fabrics') T(TAG|'<C92Mf6yV>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics') T(TAG|'<TxW3Yetp>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(TAG|'<08yGbnMX>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TAG|'<7MZTHLMY>') T(TERMINATOR|';\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 146 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
Preprocessed source code - 153 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<wIcCuax5>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\r\n    ') T(DATA|'wool fabrics') T(TAG|'<C92Mf6yV>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<TxW3Yetp>') T(SEPARATOR|',\r\n\t\r\n    ') T(DATA|'silk fabrics') T(TAG|'<08yGbnMX>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<7MZTHLMY>') T(TERMINATOR|';\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 153 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
Preprocessed source code - 179 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<Zcm0y9mS> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'fiber ') T(TAG|'<ZxMvmqeZ>') T(SEPARATOR|',\n    ') T(DATA|'water ') T(TAG|'<xePTheNI>') T(TERMINATOR|';\n\n') T(DATA|'micronutrients ') T(TAG|'<l7qy3zi2>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'vitamins (ABCDEK) ') T(TAG|'<6Nq8AWj7>') T(SEPARATOR|',\n    ') T(DATA|'minerals (micronutrients) ') T(TAG|'<jG4U9bwg>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 179 characters, into 21 tokens.
Those were translated to 2 productions, containing 6 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
Preprocessed source code - 166 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<KvtgGtnv> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<rUEqmXfk>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<wpra8mUV>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<VFoIEr0T>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<oI5DOuPh>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 166 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
Preprocessed source code - 172 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<aXLBEer9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'cotton fabrics ') T(TAG|'<evhAIQx4>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<h0e5wwEY>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<WryZrSIJ>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 172 characters, into 14 tokens.
Those were translated to 1 productions, containing 4 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds"
Preprocessed source code - 139 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<QuvD4gqX> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>        ') T(DATA|'wool fabrics ') T(TAG|'<VBsu8OpW>') T(SEPARATOR|', ') T(DATA|'cotton fabrics ') T(TAG|'<0RdNAvNs> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 139 characters, into 11 tokens.
Those were translated to 1 productions, containing 3 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
Preprocessed source code - 185 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<qJobcYNC> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<WmtITd8B>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<KGkvDUZH>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<BbiZz4Ie>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<gCWv1P46>') T(TERMINATOR|';\r\n\r\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 185 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
Preprocessed source code - 181 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<xpXWehDW> ') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(DATA|'wool fabrics ') T(TAG|'<TcD3LcoW>') T(SEPARATOR|',\r\n    ') T(DATA|'cotton fabrics ') T(TAG|'<thZBzyNc>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics ') T(TAG|'<dOlQGMJ4>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics ') T(TAG|'<Ln7Y7Dme>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 181 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty1.ds"
Preprocessed source code - 21 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<c42Q6wPH> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 21 characters, into 6 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty2.ds"
Preprocessed source code - 22 characters long

Parsing sequence: T(DATA|'fabrics ') T(TAG|'<YACUz3H9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 22 characters, into 6 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty3.ds"
Preprocessed source code - 21 characters long

Parsing sequence: T(DATA|'fabrics') T(TAG|'<YMFX0PTE>') T(HYPHEN|'-') T(RIGHT_ARROW|'> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 21 characters, into 6 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty4.ds"
Preprocessed source code - 29 characters long

Parsing sequence: T(DATA|'fabrics\r\n') T(TAG|'<SIrifQYp>\r\n') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\r\n') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 29 characters, into 6 tokens.
Those were translated to 0 productions, containing 1 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
Preprocessed source code - 148 characters long

Parsing sequence: T(DATA|'платове ') T(TAG|'<ФЛГмссД5> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'вълнени платове ') T(TAG|'<ПеП0ТхЗй>') T(SEPARATOR|',\r\n\t') T(DATA|'памучни платове ') T(TAG|'<ПТъЗАфЪа>') T(SEPARATOR|',\r\n\t') T(DATA|'копринени платове ') T(TAG|'<5Суак3ИЙ>') T(SEPARATOR|',\r\n\t') T(DATA|'синтетични платове ') T(TAG|'<ЛКтрт5КН>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 148 characters, into 17 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
Preprocessed source code - 165 characters long

Parsing sequence: T(DATA|'fa ') T(HYPHEN|'-') T(DATA|' br') T(HYPHEN|'-') T(DATA|'ics') T(HYPHEN|'-') T(DATA|' ') T(TAG|'<45mns0l-O>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(HYPHEN|'-') T(DATA|'fabrics ') T(TAG|'<-5g1GJyFS>') T(SEPARATOR|',\r\n    ') T(HYPHEN|'-') T(DATA|'cotton fabrics ') T(TAG|'<f75CKWhl->') T(SEPARATOR|',\r\n    ') T(HYPHEN|'-') T(DATA|' silk ') T(HYPHEN|'-') T(DATA|' fabrics ') T(TAG|'<68Es--hujI>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(HYPHEN|'-') T(DATA|' ') T(TAG|'<mWa4QdRm>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 165 characters, into 31 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
Preprocessed source code - 163 characters long

Parsing sequence: T(DATA|'fa ') T(FORWARD_SLASH|'/ ') T(DATA|'br') T(FORWARD_SLASH|'/') T(DATA|'ics') T(FORWARD_SLASH|'/ ') T(TAG|'<ToUZ5J7e> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(FORWARD_SLASH|'/') T(DATA|'fabrics ') T(TAG|'</DZChUWeh>') T(SEPARATOR|',\r\n    ') T(FORWARD_SLASH|'/') T(DATA|'cotton fabrics ') T(TAG|'<XBru/v3rK>') T(SEPARATOR|',\r\n    ') T(FORWARD_SLASH|'/ ') T(DATA|'silk ') T(FORWARD_SLASH|'/ ') T(DATA|'fabrics') T(TAG|'<7tewYK/BC>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(FORWARD_SLASH|'/') T(TAG|'<qStgB/Iqw>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 163 characters, into 29 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
Preprocessed source code - 164 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE|'\ ') T(DATA|'br') T(ESCAPE|'\') T(DATA|'ics') T(ESCAPE|'\ ') T(TAG|'<AkoHsBxP>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE|'\') T(DATA|'fabrics ') T(TAG|'<\2\2gPwg0Z>') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\') T(DATA|'cotton fabrics ') T(TAG|'<\6KbLpKF2>') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\ ') T(DATA|'silk ') T(ESCAPE|'\ ') T(DATA|'fabrics ') T(TAG|'<YA0\Cn7gP>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE|'\ ') T(TAG|'<V4tLOkb5>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 164 characters, into 29 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
Preprocessed source code - 178 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'> ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'> ') T(TAG|'<uqkUXoj0>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<y3rd1tuM>') T(SEPARATOR|',\r\n    ') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'cotton fabrics') T(TAG|'<l9JX2YWw>') T(SEPARATOR|',\r\n    ') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'> ') T(DATA|'silk ') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'> ') T(DATA|'fabrics  ') T(TAG|'<INIKQpj4>  ') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(TAG|'<gF7eKSgr> ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 178 characters, into 37 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
Preprocessed source code - 166 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics') T(ESCAPE_LCOMMENT|'\// ') T(TAG|'<6O4fovPJ>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics ') T(TAG|'<cTk1qeGz>') T(SEPARATOR|',\r\n    ') T(ESCAPE_SEPARATOR|'\,') T(DATA|'cotton fabrics') T(ESCAPE_LEFT_ARROW|'\<') T(TAG|'<cTk1qeGz>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(TAG|'<cTk1qeGz>  ') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_TERMINATOR|'\; ') T(TAG|'<cTk1qeGz>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 166 characters, into 28 tokens.
Those were translated to 1 productions, containing 2 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
Preprocessed source code - 169 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'br') T(ESCAPE_ESCAPE|'\\') T(DATA|'ics') T(ESCAPE_ESCAPE|'\\ ') T(TAG|'<rDD37re8> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_ESCAPE|'\\') T(DATA|'fabrics ') T(TAG|'<uCzQa1uW>') T(SEPARATOR|',\r\n    ') T(ESCAPE_ESCAPE|'\\') T(DATA|'cotton fabrics ') T(TAG|'<UxMKgYjI>') T(SEPARATOR|',\r\n    ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'silk ') T(ESCAPE_ESCAPE|'\\ ') T(DATA|'fabrics ') T(TAG|'<Ux6wwQBT>') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_ESCAPE|'\\ ') T(TAG|'<dbpyUcza>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 169 characters, into 29 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
Preprocessed source code - 164 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(TAG|'<TSbLGnNG> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n\t') T(DATA|'wool   fabrics\t ') T(TAG|'<QWVZ3pp9> ') T(SEPARATOR|',\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles   ') T(TAG|'<75NTfebY>') T(SEPARATOR|',\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'fabrics ') T(TAG|'<Sqs0lm7S>') T(SEPARATOR|',\n    ') T(DATA|'syntic \t\tfabrics ') T(TAG|'<GcZEI9gy>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 164 characters, into 22 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
Preprocessed source code - 173 characters long

Parsing sequence: T(DATA|'fabric     s    ') T(TAG|'<sJZOzSdo>\t') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool   fabrics\t') T(TAG|'<UlJXGWLS> ') T(SEPARATOR|',\r\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles  ') T(ESCAPE_LEFT_ARROW|'\<') T(TAG|'<d4jKusMe>') T(SEPARATOR|',\r\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<Bgx8/M6B1>') T(SEPARATOR|',\r\n    ') T(DATA|'syntic \t\tfabrics ') T(TAG|'<7vb\\W9VSB>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 173 characters, into 23 tokens.
Those were translated to 1 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
Preprocessed source code - 137 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<0CmyN2Mb> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<CMxWzMs5> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<hzAzwlx6>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<UHOcZPAm>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<BBmOZjJa>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 137 characters, into 18 tokens.
Those were translated to 2 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
Preprocessed source code - 129 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<eQxYylc3> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water ') T(TAG|'<tdgS8qBO>') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(TAG|'<OpdFntBx> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<MLUxjdg8>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<qkVgxZIs>') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 129 characters, into 19 tokens.
Those were translated to 2 productions, containing 5 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
Preprocessed source code - 155 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<oVs6tsnU> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'water ') T(TAG|'<9Y9uFDwu>') T(SEPARATOR|',\r\n\t') T(DATA|'fiber ') T(TAG|'<PALnQoTQ> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<6hlYVfaz>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<gubSBEDe>') T(TERMINATOR|';\r\n\r\n\t') T(DATA|'somth else ') T(TAG|'<hAyLdw3m>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 155 characters, into 21 tokens.
Those were translated to 2 productions, containing 6 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
Preprocessed source code - 262 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<xkQxOfc9> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<CbALGP8d> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<7KNUmetK>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<6qFQ0HxK>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<o8lvOnlB> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<SbQjE2YS>') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics ') T(TAG|'<CVOSiiAS>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<1G0hZLJ4>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<ozhHnNOU>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<jMBLOKGE>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 262 characters, into 34 tokens.
Those were translated to 3 productions, containing 10 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
Preprocessed source code - 254 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<SxOf3elF> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water ') T(TAG|'<8S3IwDlG>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<RV4OUQoy>') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(TAG|'<G3tWgyDr> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<AwPl7oBK>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<OcIUTGif>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<k543P1uB> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<IZZ9vPiK>') T(SEPARATOR|',\r\n\t\t') T(DATA|'informathics ') T(TAG|'<OMH9y9Jn>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<UuA1ITf9>') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 254 characters, into 35 tokens.
Those were translated to 3 productions, containing 10 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
Preprocessed source code - 318 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<VNvl4KbI> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(TAG|'<BNdiPBY8> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<47GG8irk>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<vRje122z>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<4Zohe6QE> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<u87kglXS> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra ') T(TAG|'<VB7KNYBw>') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry ') T(TAG|'<gKznl6RJ>') T(TERMINATOR|';\r\n\t\t\t\r\n\t\t') T(DATA|'informathics ') T(TAG|'<Uon0W1e7>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<rBW9kGDK>') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water ') T(TAG|'<3QJz4slg>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<X2BTGncx>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 318 characters, into 41 tokens.
Those were translated to 4 productions, containing 12 entries.
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
Preprocessed source code - 311 characters long

Parsing sequence: T(DATA|'macronutrients ') T(TAG|'<ryQ27h6e> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water ') T(TAG|'<hAdLCBLZ>') T(SEPARATOR|',\r\n    ') T(DATA|'salt ') T(TAG|'<GotVxcPm>') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(TAG|'<CHcd0L0E> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what ') T(TAG|'<jiSw0LNV>') T(SEPARATOR|',\r\n        ') T(DATA|'not ') T(TAG|'<TpR3PZdW>') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(TAG|'<qlMb3HAO> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t\r\n\t\t') T(DATA|'informathics ') T(TAG|'<jn0zFcnW>') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine ') T(TAG|'<JZmdtZj5>') T(SEPARATOR|',\r\n\t\t\r\n\t\t') T(DATA|'math ') T(TAG|'<bYBIKVXn> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra ') T(TAG|'<nFxP8YKb>') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry ') T(TAG|'<hDNMVYP0>') T(TERMINATOR|';') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 311 characters, into 43 tokens.
Those were translated to 4 productions, containing 12 entries.
All Files: 31, Succeeded: 31, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "l.4VGPOFIK.QpeudYXy" 

    .Productions
        "l.4VGPOFIK.QpeudYXy" -> "l.4VGPOFIK.54vHCQwI", "l.4VGPOFIK.Ll0bDtIQ", "l.4VGPOFIK.6huM44Hm", "l.4VGPOFIK.oAgVUPi0";
        "l.JGNXPSZ9.BTTI4E8I" -> "l.JGNXPSZ9.i1NLckN6";
        "l.SGEJMZCU.zAfn39Kh" -> "l.SGEJMZCU.hOy5oL3B";
        "l.WIAEAJVY.wIcCuax5" -> "l.WIAEAJVY.C92Mf6yV", "l.WIAEAJVY.TxW3Yetp", "l.WIAEAJVY.08yGbnMX", "l.WIAEAJVY.7MZTHLMY";
        "l.T1I939RG.wIcCuax5" -> "l.T1I939RG.C92Mf6yV", "l.T1I939RG.TxW3Yetp", "l.T1I939RG.08yGbnMX", "l.T1I939RG.7MZTHLMY";
        "l.DA8XJBW9.Zcm0y9mS" -> "l.DA8XJBW9.ZxMvmqeZ", "l.DA8XJBW9.xePTheNI";
        "l.DA8XJBW9.l7qy3zi2" -> "l.DA8XJBW9.6Nq8AWj7", "l.DA8XJBW9.jG4U9bwg";
        "l.GZJA5O6C.KvtgGtnv" -> "l.GZJA5O6C.rUEqmXfk", "l.GZJA5O6C.wpra8mUV", "l.GZJA5O6C.VFoIEr0T", "l.GZJA5O6C.oI5DOuPh";
        "l.636ALFWU.aXLBEer9" -> "l.636ALFWU.evhAIQx4", "l.636ALFWU.h0e5wwEY", "l.636ALFWU.WryZrSIJ";
        "l.G2QE8QFO.QuvD4gqX" -> "l.G2QE8QFO.VBsu8OpW", "l.G2QE8QFO.0RdNAvNs";
        "l.FJ1ZBSU3.qJobcYNC" -> "l.FJ1ZBSU3.WmtITd8B", "l.FJ1ZBSU3.KGkvDUZH", "l.FJ1ZBSU3.BbiZz4Ie", "l.FJ1ZBSU3.gCWv1P46";
        "l.V14NRGSC.xpXWehDW" -> "l.V14NRGSC.TcD3LcoW", "l.V14NRGSC.thZBzyNc", "l.V14NRGSC.dOlQGMJ4", "l.V14NRGSC.Ln7Y7Dme";
        "l.U1WWM48Q.ФЛГмссД5" -> "l.U1WWM48Q.ПеП0ТхЗй", "l.U1WWM48Q.ПТъЗАфЪа", "l.U1WWM48Q.5Суак3ИЙ", "l.U1WWM48Q.ЛКтрт5КН";
        "l.TAW342MZ.45mns0l-O" -> "l.TAW342MZ.-5g1GJyFS", "l.TAW342MZ.f75CKWhl-", "l.TAW342MZ.68Es--hujI", "l.TAW342MZ.mWa4QdRm";
        "l.0PIDIGQS.ToUZ5J7e" -> "l.0PIDIGQS./DZChUWeh", "l.0PIDIGQS.XBru/v3rK", "l.0PIDIGQS.7tewYK/BC", "l.0PIDIGQS.qStgB/Iqw";
        "l.2ENRY7HC.AkoHsBxP" -> "l.2ENRY7HC.\2\2gPwg0Z", "l.2ENRY7HC.\6KbLpKF2", "l.2ENRY7HC.YA0\Cn7gP", "l.2ENRY7HC.V4tLOkb5";
        "l.499X5PCX.uqkUXoj0" -> "l.499X5PCX.y3rd1tuM", "l.499X5PCX.l9JX2YWw", "l.499X5PCX.INIKQpj4", "l.499X5PCX.gF7eKSgr";
        "l.QOQUB1UK.6O4fovPJ" -> "l.QOQUB1UK.cTk1qeGz", "l.QOQUB1UK.cTk1qeGz", "l.QOQUB1UK.cTk1qeGz", "l.QOQUB1UK.cTk1qeGz";
        "l.E6TP864U.rDD37re8" -> "l.E6TP864U.uCzQa1uW", "l.E6TP864U.UxMKgYjI", "l.E6TP864U.Ux6wwQBT", "l.E6TP864U.dbpyUcza";
        "l.U5LTTGUD.TSbLGnNG" -> "l.U5LTTGUD.QWVZ3pp9", "l.U5LTTGUD.75NTfebY", "l.U5LTTGUD.Sqs0lm7S", "l.U5LTTGUD.GcZEI9gy";
        "l.D6UB9E70.sJZOzSdo" -> "l.D6UB9E70.UlJXGWLS", "l.D6UB9E70.d4jKusMe", "l.D6UB9E70.Bgx8/M6B1", "l.D6UB9E70.7vb\\W9VSB";
        "l.ATEW5430.CMxWzMs5" -> "l.ATEW5430.hzAzwlx6", "l.ATEW5430.UHOcZPAm";
        "l.ATEW5430.0CmyN2Mb" -> "l.ATEW5430.CMxWzMs5", "l.ATEW5430.BBmOZjJa";
        "l.Z1N73TAG.OpdFntBx" -> "l.Z1N73TAG.MLUxjdg8", "l.Z1N73TAG.qkVgxZIs";
        "l.Z1N73TAG.eQxYylc3" -> "l.Z1N73TAG.tdgS8qBO", "l.Z1N73TAG.OpdFntBx";
        "l.YEA295XP.PALnQoTQ" -> "l.YEA295XP.6hlYVfaz", "l.YEA295XP.gubSBEDe";
        "l.YEA295XP.oVs6tsnU" -> "l.YEA295XP.9Y9uFDwu", "l.YEA295XP.PALnQoTQ", "l.YEA295XP.hAyLdw3m";
        "l.DR6GVNSX.CbALGP8d" -> "l.DR6GVNSX.7KNUmetK", "l.DR6GVNSX.6qFQ0HxK";
        "l.DR6GVNSX.o8lvOnlB" -> "l.DR6GVNSX.SbQjE2YS", "l.DR6GVNSX.CVOSiiAS", "l.DR6GVNSX.1G0hZLJ4";
        "l.DR6GVNSX.xkQxOfc9" -> "l.DR6GVNSX.CbALGP8d", "l.DR6GVNSX.o8lvOnlB", "l.DR6GVNSX.ozhHnNOU", "l.DR6GVNSX.jMBLOKGE";
        "l.HUZX3HK7.G3tWgyDr" -> "l.HUZX3HK7.AwPl7oBK", "l.HUZX3HK7.OcIUTGif";
        "l.HUZX3HK7.k543P1uB" -> "l.HUZX3HK7.IZZ9vPiK", "l.HUZX3HK7.OMH9y9Jn", "l.HUZX3HK7.UuA1ITf9";
        "l.HUZX3HK7.SxOf3elF" -> "l.HUZX3HK7.8S3IwDlG", "l.HUZX3HK7.RV4OUQoy", "l.HUZX3HK7.G3tWgyDr", "l.HUZX3HK7.k543P1uB";
        "l.V2X8V8O9.BNdiPBY8" -> "l.V2X8V8O9.47GG8irk", "l.V2X8V8O9.vRje122z";
        "l.V2X8V8O9.u87kglXS" -> "l.V2X8V8O9.VB7KNYBw", "l.V2X8V8O9.gKznl6RJ";
        "l.V2X8V8O9.4Zohe6QE" -> "l.V2X8V8O9.u87kglXS", "l.V2X8V8O9.Uon0W1e7", "l.V2X8V8O9.rBW9kGDK";
        "l.V2X8V8O9.VNvl4KbI" -> "l.V2X8V8O9.BNdiPBY8", "l.V2X8V8O9.4Zohe6QE", "l.V2X8V8O9.3QJz4slg", "l.V2X8V8O9.X2BTGncx";
        "l.YZI3JXZM.CHcd0L0E" -> "l.YZI3JXZM.jiSw0LNV", "l.YZI3JXZM.TpR3PZdW";
        "l.YZI3JXZM.bYBIKVXn" -> "l.YZI3JXZM.nFxP8YKb", "l.YZI3JXZM.hDNMVYP0";
        "l.YZI3JXZM.qlMb3HAO" -> "l.YZI3JXZM.jn0zFcnW", "l.YZI3JXZM.JZmdtZj5", "l.YZI3JXZM.bYBIKVXn";
        "l.YZI3JXZM.ryQ27h6e" -> "l.YZI3JXZM.hAdLCBLZ", "l.YZI3JXZM.GotVxcPm", "l.YZI3JXZM.CHcd0L0E", "l.YZI3JXZM.qlMb3HAO";

    .Translations
        "l.4VGPOFIK.QpeudYXy" - "fabrics"
        "l.4VGPOFIK.54vHCQwI" - "wool fabrics"
        "l.4VGPOFIK.Ll0bDtIQ" - "cotton fabrics"
        "l.4VGPOFIK.6huM44Hm" - "silk fabrics"
        "l.4VGPOFIK.oAgVUPi0" - "synthetic fabrics"
        "l.JGNXPSZ9.BTTI4E8I" - "fabrics"
        "l.JGNXPSZ9.i1NLckN6" - "synthetic fabrics"
        "l.SGEJMZCU.zAfn39Kh" - "fabrics"
        "l.SGEJMZCU.hOy5oL3B" - "synthetic fabrics"
        "l.WIAEAJVY.wIcCuax5" - "fabrics"
        "l.WIAEAJVY.C92Mf6yV" - "wool fabrics"
        "l.WIAEAJVY.TxW3Yetp" - "cotton fabrics"
        "l.WIAEAJVY.08yGbnMX" - "silk fabrics"
        "l.WIAEAJVY.7MZTHLMY" - "synthetic fabrics"
        "l.T1I939RG.wIcCuax5" - "fabrics"
        "l.T1I939RG.C92Mf6yV" - "wool fabrics"
        "l.T1I939RG.TxW3Yetp" - "cotton fabrics"
        "l.T1I939RG.08yGbnMX" - "silk fabrics"
        "l.T1I939RG.7MZTHLMY" - "synthetic fabrics"
        "l.DA8XJBW9.Zcm0y9mS" - "macronutrients"
        "l.DA8XJBW9.ZxMvmqeZ" - "fiber"
        "l.DA8XJBW9.xePTheNI" - "water"
        "l.DA8XJBW9.l7qy3zi2" - "micronutrients"
        "l.DA8XJBW9.6Nq8AWj7" - "vitamins (ABCDEK)"
        "l.DA8XJBW9.jG4U9bwg" - "minerals (micronutrients)"
        "l.GZJA5O6C.KvtgGtnv" - "fabrics"
        "l.GZJA5O6C.rUEqmXfk" - "wool fabrics"
        "l.GZJA5O6C.wpra8mUV" - "cotton fabrics"
        "l.GZJA5O6C.VFoIEr0T" - "silk fabrics"
        "l.GZJA5O6C.oI5DOuPh" - "synthetic fabrics"
        "l.636ALFWU.aXLBEer9" - "fabrics"
        "l.636ALFWU.evhAIQx4" - "cotton fabrics"
        "l.636ALFWU.h0e5wwEY" - "silk fabrics"
        "l.636ALFWU.WryZrSIJ" - "synthetic fabrics"
        "l.G2QE8QFO.QuvD4gqX" - "fabrics"
        "l.G2QE8QFO.VBsu8OpW" - "wool fabrics"
        "l.G2QE8QFO.0RdNAvNs" - "cotton fabrics"
        "l.FJ1ZBSU3.qJobcYNC" - "fabrics"
        "l.FJ1ZBSU3.WmtITd8B" - "wool fabrics"
        "l.FJ1ZBSU3.KGkvDUZH" - "cotton fabrics"
        "l.FJ1ZBSU3.BbiZz4Ie" - "silk fabrics"
        "l.FJ1ZBSU3.gCWv1P46" - "synthetic fabrics"
        "l.V14NRGSC.xpXWehDW" - "fabrics"
        "l.V14NRGSC.TcD3LcoW" - "wool fabrics"
        "l.V14NRGSC.thZBzyNc" - "cotton fabrics"
        "l.V14NRGSC.dOlQGMJ4" - "silk fabrics"
        "l.V14NRGSC.Ln7Y7Dme" - "synthetic fabrics"
        "l.336FYZJD.c42Q6wPH" - "fabrics"
        "l.NNQFP0DW.YACUz3H9" - "fabrics"
        "l.F584FEOU.YMFX0PTE" - "fabrics"
        "l.EP0R2YGC.SIrifQYp" - "fabrics"
        "l.U1WWM48Q.ФЛГмссД5" - "платове"
        "l.U1WWM48Q.ПеП0ТхЗй" - "вълнени платове"
        "l.U1WWM48Q.ПТъЗАфЪа" - "памучни платове"
        "l.U1WWM48Q.5Суак3ИЙ" - "копринени платове"
        "l.U1WWM48Q.ЛКтрт5КН" - "синтетични платове"
        "l.TAW342MZ.45mns0l-O" - "fa - br-ics-"
        "l.TAW342MZ.-5g1GJyFS" - "wool-fabrics"
        "l.TAW342MZ.f75CKWhl-" - "-cotton fabrics"
        "l.TAW342MZ.68Es--hujI" - "- silk - fabrics"
        "l.TAW342MZ.mWa4QdRm" - "synthetic fabrics-"
        "l.0PIDIGQS.ToUZ5J7e" - "fa / br/ics/"
        "l.0PIDIGQS./DZChUWeh" - "wool/fabrics"
        "l.0PIDIGQS.XBru/v3rK" - "/cotton fabrics"
        "l.0PIDIGQS.7tewYK/BC" - "/ silk / fabrics"
        "l.0PIDIGQS.qStgB/Iqw" - "synthetic fabrics/"
        "l.2ENRY7HC.AkoHsBxP" - "fa \ br\ics\"
        "l.2ENRY7HC.\2\2gPwg0Z" - "wool\fabrics"
        "l.2ENRY7HC.\6KbLpKF2" - "\cotton fabrics"
        "l.2ENRY7HC.YA0\Cn7gP" - "\ silk \ fabrics"
        "l.2ENRY7HC.V4tLOkb5" - "synthetic fabrics\"
        "l.499X5PCX.uqkUXoj0" - "fa \-> br\->ics\->"
        "l.499X5PCX.y3rd1tuM" - "wool\->fabrics"
        "l.499X5PCX.l9JX2YWw" - "\->cotton fabrics"
        "l.499X5PCX.INIKQpj4" - "\-> silk \-> fabrics"
        "l.499X5PCX.gF7eKSgr" - "synthetic fabrics\->"
        "l.QOQUB1UK.6O4fovPJ" - "fa \, br\->ics\//"
        "l.QOQUB1UK.cTk1qeGz" - "synthetic fabrics\;"
        "l.E6TP864U.rDD37re8" - "fa \\ br\\ics\\"
        "l.E6TP864U.uCzQa1uW" - "wool\\fabrics"
        "l.E6TP864U.UxMKgYjI" - "\\cotton fabrics"
        "l.E6TP864U.Ux6wwQBT" - "\\ silk \\ fabrics"
        "l.E6TP864U.dbpyUcza" - "synthetic fabrics\\"
        "l.U5LTTGUD.TSbLGnNG" - "fabric     s"
        "l.U5LTTGUD.QWVZ3pp9" - "wool   fabrics"
        "l.U5LTTGUD.75NTfebY" - "cotton\, fabrics textiles"
        "l.U5LTTGUD.Sqs0lm7S" - "silk\-\>fabrics"
        "l.U5LTTGUD.GcZEI9gy" - "syntic 		fabrics"
        "l.D6UB9E70.sJZOzSdo" - "fabric     s"
        "l.D6UB9E70.UlJXGWLS" - "wool   fabrics"
        "l.D6UB9E70.d4jKusMe" - "cotton\, fabrics textiles  \<"
        "l.D6UB9E70.Bgx8/M6B1" - "silk\->fabrics"
        "l.D6UB9E70.7vb\\W9VSB" - "syntic 		fabrics"
        "l.ATEW5430.0CmyN2Mb" - "macronutrients"
        "l.ATEW5430.CMxWzMs5" - "fiber"
        "l.ATEW5430.hzAzwlx6" - "what"
        "l.ATEW5430.UHOcZPAm" - "not"
        "l.ATEW5430.BBmOZjJa" - "water"
        "l.Z1N73TAG.eQxYylc3" - "macronutrients"
        "l.Z1N73TAG.tdgS8qBO" - "water"
        "l.Z1N73TAG.OpdFntBx" - "fiber"
        "l.Z1N73TAG.MLUxjdg8" - "what"
        "l.Z1N73TAG.qkVgxZIs" - "not"
        "l.YEA295XP.oVs6tsnU" - "macronutrients"
        "l.YEA295XP.9Y9uFDwu" - "water"
        "l.YEA295XP.PALnQoTQ" - "fiber"
        "l.YEA295XP.6hlYVfaz" - "what"
        "l.YEA295XP.gubSBEDe" - "not"
        "l.YEA295XP.hAyLdw3m" - "somth else"
        "l.DR6GVNSX.xkQxOfc9" - "macronutrients"
        "l.DR6GVNSX.CbALGP8d" - "fiber"
        "l.DR6GVNSX.7KNUmetK" - "what"
        "l.DR6GVNSX.6qFQ0HxK" - "not"
        "l.DR6GVNSX.o8lvOnlB" - "science"
        "l.DR6GVNSX.SbQjE2YS" - "math"
        "l.DR6GVNSX.CVOSiiAS" - "informathics"
        "l.DR6GVNSX.1G0hZLJ4" - "medicine"
        "l.DR6GVNSX.ozhHnNOU" - "water"
        "l.DR6GVNSX.jMBLOKGE" - "salt"
        "l.HUZX3HK7.SxOf3elF" - "macronutrients"
        "l.HUZX3HK7.8S3IwDlG" - "water"
        "l.HUZX3HK7.RV4OUQoy" - "salt"
        "l.HUZX3HK7.G3tWgyDr" - "fiber"
        "l.HUZX3HK7.AwPl7oBK" - "what"
        "l.HUZX3HK7.OcIUTGif" - "not"
        "l.HUZX3HK7.k543P1uB" - "science"
        "l.HUZX3HK7.IZZ9vPiK" - "math"
        "l.HUZX3HK7.OMH9y9Jn" - "informathics"
        "l.HUZX3HK7.UuA1ITf9" - "medicine"
        "l.V2X8V8O9.VNvl4KbI" - "macronutrients"
        "l.V2X8V8O9.BNdiPBY8" - "fiber"
        "l.V2X8V8O9.47GG8irk" - "what"
        "l.V2X8V8O9.vRje122z" - "not"
        "l.V2X8V8O9.4Zohe6QE" - "science"
        "l.V2X8V8O9.u87kglXS" - "math"
        "l.V2X8V8O9.VB7KNYBw" - "algebra"
        "l.V2X8V8O9.gKznl6RJ" - "geometry"
        "l.V2X8V8O9.Uon0W1e7" - "informathics"
        "l.V2X8V8O9.rBW9kGDK" - "medicine"
        "l.V2X8V8O9.3QJz4slg" - "water"
        "l.V2X8V8O9.X2BTGncx" - "salt"
        "l.YZI3JXZM.ryQ27h6e" - "macronutrients"
        "l.YZI3JXZM.hAdLCBLZ" - "water"
        "l.YZI3JXZM.GotVxcPm" - "salt"
        "l.YZI3JXZM.CHcd0L0E" - "fiber"
        "l.YZI3JXZM.jiSw0LNV" - "what"
        "l.YZI3JXZM.TpR3PZdW" - "not"
        "l.YZI3JXZM.qlMb3HAO" - "science"
        "l.YZI3JXZM.jn0zFcnW" - "informathics"
        "l.YZI3JXZM.JZmdtZj5" - "medicine"
        "l.YZI3JXZM.bYBIKVXn" - "math"
        "l.YZI3JXZM.nFxP8YKb" - "algebra"
        "l.YZI3JXZM.hDNMVYP0" - "geometry"

    .Links
        "l.4VGPOFIK.QpeudYXy" - 
        "l.4VGPOFIK.54vHCQwI" - 
        "l.4VGPOFIK.Ll0bDtIQ" - 
        "l.4VGPOFIK.6huM44Hm" - 
        "l.4VGPOFIK.oAgVUPi0" - 
        "l.JGNXPSZ9.BTTI4E8I" - 
        "l.JGNXPSZ9.i1NLckN6" - 
        "l.SGEJMZCU.zAfn39Kh" - 
        "l.SGEJMZCU.hOy5oL3B" - 
        "l.WIAEAJVY.wIcCuax5" - 
        "l.WIAEAJVY.C92Mf6yV" - 
        "l.WIAEAJVY.TxW3Yetp" - 
        "l.WIAEAJVY.08yGbnMX" - 
        "l.WIAEAJVY.7MZTHLMY" - 
        "l.T1I939RG.wIcCuax5" - 
        "l.T1I939RG.C92Mf6yV" - 
        "l.T1I939RG.TxW3Yetp" - 
        "l.T1I939RG.08yGbnMX" - 
        "l.T1I939RG.7MZTHLMY" - 
        "l.DA8XJBW9.Zcm0y9mS" - 
        "l.DA8XJBW9.ZxMvmqeZ" - 
        "l.DA8XJBW9.xePTheNI" - 
        "l.DA8XJBW9.l7qy3zi2" - 
        "l.DA8XJBW9.6Nq8AWj7" - 
        "l.DA8XJBW9.jG4U9bwg" - 
        "l.GZJA5O6C.KvtgGtnv" - 
        "l.GZJA5O6C.rUEqmXfk" - 
        "l.GZJA5O6C.wpra8mUV" - 
        "l.GZJA5O6C.VFoIEr0T" - 
        "l.GZJA5O6C.oI5DOuPh" - 
        "l.636ALFWU.aXLBEer9" - 
        "l.636ALFWU.evhAIQx4" - 
        "l.636ALFWU.h0e5wwEY" - 
        "l.636ALFWU.WryZrSIJ" - 
        "l.G2QE8QFO.QuvD4gqX" - 
        "l.G2QE8QFO.VBsu8OpW" - 
        "l.G2QE8QFO.0RdNAvNs" - 
        "l.FJ1ZBSU3.qJobcYNC" - 
        "l.FJ1ZBSU3.WmtITd8B" - 
        "l.FJ1ZBSU3.KGkvDUZH" - 
        "l.FJ1ZBSU3.BbiZz4Ie" - 
        "l.FJ1ZBSU3.gCWv1P46" - 
        "l.V14NRGSC.xpXWehDW" - 
        "l.V14NRGSC.TcD3LcoW" - 
        "l.V14NRGSC.thZBzyNc" - 
        "l.V14NRGSC.dOlQGMJ4" - 
        "l.V14NRGSC.Ln7Y7Dme" - 
        "l.336FYZJD.c42Q6wPH" - 
        "l.NNQFP0DW.YACUz3H9" - 
        "l.F584FEOU.YMFX0PTE" - 
        "l.EP0R2YGC.SIrifQYp" - 
        "l.U1WWM48Q.ФЛГмссД5" - 
        "l.U1WWM48Q.ПеП0ТхЗй" - 
        "l.U1WWM48Q.ПТъЗАфЪа" - 
        "l.U1WWM48Q.5Суак3ИЙ" - 
        "l.U1WWM48Q.ЛКтрт5КН" - 
        "l.TAW342MZ.45mns0l-O" - 
        "l.TAW342MZ.-5g1GJyFS" - 
        "l.TAW342MZ.f75CKWhl-" - 
        "l.TAW342MZ.68Es--hujI" - 
        "l.TAW342MZ.mWa4QdRm" - 
        "l.0PIDIGQS.ToUZ5J7e" - 
        "l.0PIDIGQS./DZChUWeh" - 
        "l.0PIDIGQS.XBru/v3rK" - 
        "l.0PIDIGQS.7tewYK/BC" - 
        "l.0PIDIGQS.qStgB/Iqw" - 
        "l.2ENRY7HC.AkoHsBxP" - 
        "l.2ENRY7HC.\2\2gPwg0Z" - 
        "l.2ENRY7HC.\6KbLpKF2" - 
        "l.2ENRY7HC.YA0\Cn7gP" - 
        "l.2ENRY7HC.V4tLOkb5" - 
        "l.499X5PCX.uqkUXoj0" - 
        "l.499X5PCX.y3rd1tuM" - 
        "l.499X5PCX.l9JX2YWw" - 
        "l.499X5PCX.INIKQpj4" - 
        "l.499X5PCX.gF7eKSgr" - 
        "l.QOQUB1UK.6O4fovPJ" - 
        "l.QOQUB1UK.cTk1qeGz" - 
        "l.E6TP864U.rDD37re8" - 
        "l.E6TP864U.uCzQa1uW" - 
        "l.E6TP864U.UxMKgYjI" - 
        "l.E6TP864U.Ux6wwQBT" - 
        "l.E6TP864U.dbpyUcza" - 
        "l.U5LTTGUD.TSbLGnNG" - 
        "l.U5LTTGUD.QWVZ3pp9" - 
        "l.U5LTTGUD.75NTfebY" - 
        "l.U5LTTGUD.Sqs0lm7S" - 
        "l.U5LTTGUD.GcZEI9gy" - 
        "l.D6UB9E70.sJZOzSdo" - 
        "l.D6UB9E70.UlJXGWLS" - 
        "l.D6UB9E70.d4jKusMe" - 
        "l.D6UB9E70.Bgx8/M6B1" - 
        "l.D6UB9E70.7vb\\W9VSB" - 
        "l.ATEW5430.0CmyN2Mb" - 
        "l.ATEW5430.CMxWzMs5" - 
        "l.ATEW5430.hzAzwlx6" - 
        "l.ATEW5430.UHOcZPAm" - 
        "l.ATEW5430.BBmOZjJa" - 
        "l.Z1N73TAG.eQxYylc3" - 
        "l.Z1N73TAG.tdgS8qBO" - 
        "l.Z1N73TAG.OpdFntBx" - 
        "l.Z1N73TAG.MLUxjdg8" - 
        "l.Z1N73TAG.qkVgxZIs" - 
        "l.YEA295XP.oVs6tsnU" - 
        "l.YEA295XP.9Y9uFDwu" - 
        "l.YEA295XP.PALnQoTQ" - 
        "l.YEA295XP.6hlYVfaz" - 
        "l.YEA295XP.gubSBEDe" - 
        "l.YEA295XP.hAyLdw3m" - 
        "l.DR6GVNSX.xkQxOfc9" - 
        "l.DR6GVNSX.CbALGP8d" - 
        "l.DR6GVNSX.7KNUmetK" - 
        "l.DR6GVNSX.6qFQ0HxK" - 
        "l.DR6GVNSX.o8lvOnlB" - 
        "l.DR6GVNSX.SbQjE2YS" - 
        "l.DR6GVNSX.CVOSiiAS" - 
        "l.DR6GVNSX.1G0hZLJ4" - 
        "l.DR6GVNSX.ozhHnNOU" - 
        "l.DR6GVNSX.jMBLOKGE" - 
        "l.HUZX3HK7.SxOf3elF" - 
        "l.HUZX3HK7.8S3IwDlG" - 
        "l.HUZX3HK7.RV4OUQoy" - 
        "l.HUZX3HK7.G3tWgyDr" - 
        "l.HUZX3HK7.AwPl7oBK" - 
        "l.HUZX3HK7.OcIUTGif" - 
        "l.HUZX3HK7.k543P1uB" - 
        "l.HUZX3HK7.IZZ9vPiK" - 
        "l.HUZX3HK7.OMH9y9Jn" - 
        "l.HUZX3HK7.UuA1ITf9" - 
        "l.V2X8V8O9.VNvl4KbI" - 
        "l.V2X8V8O9.BNdiPBY8" - 
        "l.V2X8V8O9.47GG8irk" - 
        "l.V2X8V8O9.vRje122z" - 
        "l.V2X8V8O9.4Zohe6QE" - 
        "l.V2X8V8O9.u87kglXS" - 
        "l.V2X8V8O9.VB7KNYBw" - 
        "l.V2X8V8O9.gKznl6RJ" - 
        "l.V2X8V8O9.Uon0W1e7" - 
        "l.V2X8V8O9.rBW9kGDK" - 
        "l.V2X8V8O9.3QJz4slg" - 
        "l.V2X8V8O9.X2BTGncx" - 
        "l.YZI3JXZM.ryQ27h6e" - 
        "l.YZI3JXZM.hAdLCBLZ" - 
        "l.YZI3JXZM.GotVxcPm" - 
        "l.YZI3JXZM.CHcd0L0E" - 
        "l.YZI3JXZM.jiSw0LNV" - 
        "l.YZI3JXZM.TpR3PZdW" - 
        "l.YZI3JXZM.qlMb3HAO" - 
        "l.YZI3JXZM.jn0zFcnW" - 
        "l.YZI3JXZM.JZmdtZj5" - 
        "l.YZI3JXZM.bYBIKVXn" - 
        "l.YZI3JXZM.nFxP8YKb" - 
        "l.YZI3JXZM.hDNMVYP0" - 

    .Decorators
        "l.4VGPOFIK.QpeudYXy" - 
        "l.4VGPOFIK.54vHCQwI" - 
        "l.4VGPOFIK.Ll0bDtIQ" - 
        "l.4VGPOFIK.6huM44Hm" - 
        "l.4VGPOFIK.oAgVUPi0" - 
        "l.JGNXPSZ9.BTTI4E8I" - 
        "l.JGNXPSZ9.i1NLckN6" - 
        "l.SGEJMZCU.zAfn39Kh" - 
        "l.SGEJMZCU.hOy5oL3B" - 
        "l.WIAEAJVY.wIcCuax5" - 
        "l.WIAEAJVY.C92Mf6yV" - 
        "l.WIAEAJVY.TxW3Yetp" - 
        "l.WIAEAJVY.08yGbnMX" - 
        "l.WIAEAJVY.7MZTHLMY" - 
        "l.T1I939RG.wIcCuax5" - 
        "l.T1I939RG.C92Mf6yV" - 
        "l.T1I939RG.TxW3Yetp" - 
        "l.T1I939RG.08yGbnMX" - 
        "l.T1I939RG.7MZTHLMY" - 
        "l.DA8XJBW9.Zcm0y9mS" - 
        "l.DA8XJBW9.ZxMvmqeZ" - 
        "l.DA8XJBW9.xePTheNI" - 
        "l.DA8XJBW9.l7qy3zi2" - 
        "l.DA8XJBW9.6Nq8AWj7" - 
        "l.DA8XJBW9.jG4U9bwg" - 
        "l.GZJA5O6C.KvtgGtnv" - 
        "l.GZJA5O6C.rUEqmXfk" - 
        "l.GZJA5O6C.wpra8mUV" - 
        "l.GZJA5O6C.VFoIEr0T" - 
        "l.GZJA5O6C.oI5DOuPh" - 
        "l.636ALFWU.aXLBEer9" - 
        "l.636ALFWU.evhAIQx4" - 
        "l.636ALFWU.h0e5wwEY" - 
        "l.636ALFWU.WryZrSIJ" - 
        "l.G2QE8QFO.QuvD4gqX" - 
        "l.G2QE8QFO.VBsu8OpW" - 
        "l.G2QE8QFO.0RdNAvNs" - 
        "l.FJ1ZBSU3.qJobcYNC" - 
        "l.FJ1ZBSU3.WmtITd8B" - 
        "l.FJ1ZBSU3.KGkvDUZH" - 
        "l.FJ1ZBSU3.BbiZz4Ie" - 
        "l.FJ1ZBSU3.gCWv1P46" - 
        "l.V14NRGSC.xpXWehDW" - 
        "l.V14NRGSC.TcD3LcoW" - 
        "l.V14NRGSC.thZBzyNc" - 
        "l.V14NRGSC.dOlQGMJ4" - 
        "l.V14NRGSC.Ln7Y7Dme" - 
        "l.336FYZJD.c42Q6wPH" - 
        "l.NNQFP0DW.YACUz3H9" - 
        "l.F584FEOU.YMFX0PTE" - 
        "l.EP0R2YGC.SIrifQYp" - 
        "l.U1WWM48Q.ФЛГмссД5" - 
        "l.U1WWM48Q.ПеП0ТхЗй" - 
        "l.U1WWM48Q.ПТъЗАфЪа" - 
        "l.U1WWM48Q.5Суак3ИЙ" - 
        "l.U1WWM48Q.ЛКтрт5КН" - 
        "l.TAW342MZ.45mns0l-O" - 
        "l.TAW342MZ.-5g1GJyFS" - 
        "l.TAW342MZ.f75CKWhl-" - 
        "l.TAW342MZ.68Es--hujI" - 
        "l.TAW342MZ.mWa4QdRm" - 
        "l.0PIDIGQS.ToUZ5J7e" - 
        "l.0PIDIGQS./DZChUWeh" - 
        "l.0PIDIGQS.XBru/v3rK" - 
        "l.0PIDIGQS.7tewYK/BC" - 
        "l.0PIDIGQS.qStgB/Iqw" - 
        "l.2ENRY7HC.AkoHsBxP" - 
        "l.2ENRY7HC.\2\2gPwg0Z" - 
        "l.2ENRY7HC.\6KbLpKF2" - 
        "l.2ENRY7HC.YA0\Cn7gP" - 
        "l.2ENRY7HC.V4tLOkb5" - 
        "l.499X5PCX.uqkUXoj0" - 
        "l.499X5PCX.y3rd1tuM" - 
        "l.499X5PCX.l9JX2YWw" - 
        "l.499X5PCX.INIKQpj4" - 
        "l.499X5PCX.gF7eKSgr" - 
        "l.QOQUB1UK.6O4fovPJ" - 
        "l.QOQUB1UK.cTk1qeGz" - 
        "l.E6TP864U.rDD37re8" - 
        "l.E6TP864U.uCzQa1uW" - 
        "l.E6TP864U.UxMKgYjI" - 
        "l.E6TP864U.Ux6wwQBT" - 
        "l.E6TP864U.dbpyUcza" - 
        "l.U5LTTGUD.TSbLGnNG" - 
        "l.U5LTTGUD.QWVZ3pp9" - 
        "l.U5LTTGUD.75NTfebY" - 
        "l.U5LTTGUD.Sqs0lm7S" - 
        "l.U5LTTGUD.GcZEI9gy" - 
        "l.D6UB9E70.sJZOzSdo" - 
        "l.D6UB9E70.UlJXGWLS" - 
        "l.D6UB9E70.d4jKusMe" - 
        "l.D6UB9E70.Bgx8/M6B1" - 
        "l.D6UB9E70.7vb\\W9VSB" - 
        "l.ATEW5430.0CmyN2Mb" - 
        "l.ATEW5430.CMxWzMs5" - 
        "l.ATEW5430.hzAzwlx6" - 
        "l.ATEW5430.UHOcZPAm" - 
        "l.ATEW5430.BBmOZjJa" - 
        "l.Z1N73TAG.eQxYylc3" - 
        "l.Z1N73TAG.tdgS8qBO" - 
        "l.Z1N73TAG.OpdFntBx" - 
        "l.Z1N73TAG.MLUxjdg8" - 
        "l.Z1N73TAG.qkVgxZIs" - 
        "l.YEA295XP.oVs6tsnU" - 
        "l.YEA295XP.9Y9uFDwu" - 
        "l.YEA295XP.PALnQoTQ" - 
        "l.YEA295XP.6hlYVfaz" - 
        "l.YEA295XP.gubSBEDe" - 
        "l.YEA295XP.hAyLdw3m" - 
        "l.DR6GVNSX.xkQxOfc9" - 
        "l.DR6GVNSX.CbALGP8d" - 
        "l.DR6GVNSX.7KNUmetK" - 
        "l.DR6GVNSX.6qFQ0HxK" - 
        "l.DR6GVNSX.o8lvOnlB" - 
        "l.DR6GVNSX.SbQjE2YS" - 
        "l.DR6GVNSX.CVOSiiAS" - 
        "l.DR6GVNSX.1G0hZLJ4" - 
        "l.DR6GVNSX.ozhHnNOU" - 
        "l.DR6GVNSX.jMBLOKGE" - 
        "l.HUZX3HK7.SxOf3elF" - 
        "l.HUZX3HK7.8S3IwDlG" - 
        "l.HUZX3HK7.RV4OUQoy" - 
        "l.HUZX3HK7.G3tWgyDr" - 
        "l.HUZX3HK7.AwPl7oBK" - 
        "l.HUZX3HK7.OcIUTGif" - 
        "l.HUZX3HK7.k543P1uB" - 
        "l.HUZX3HK7.IZZ9vPiK" - 
        "l.HUZX3HK7.OMH9y9Jn" - 
        "l.HUZX3HK7.UuA1ITf9" - 
        "l.V2X8V8O9.VNvl4KbI" - 
        "l.V2X8V8O9.BNdiPBY8" - 
        "l.V2X8V8O9.47GG8irk" - 
        "l.V2X8V8O9.vRje122z" - 
        "l.V2X8V8O9.4Zohe6QE" - 
        "l.V2X8V8O9.u87kglXS" - 
        "l.V2X8V8O9.VB7KNYBw" - 
        "l.V2X8V8O9.gKznl6RJ" - 
        "l.V2X8V8O9.Uon0W1e7" - 
        "l.V2X8V8O9.rBW9kGDK" - 
        "l.V2X8V8O9.3QJz4slg" - 
        "l.V2X8V8O9.X2BTGncx" - 
        "l.YZI3JXZM.ryQ27h6e" - 
        "l.YZI3JXZM.hAdLCBLZ" - 
        "l.YZI3JXZM.GotVxcPm" - 
        "l.YZI3JXZM.CHcd0L0E" - 
        "l.YZI3JXZM.jiSw0LNV" - 
        "l.YZI3JXZM.TpR3PZdW" - 
        "l.YZI3JXZM.qlMb3HAO" - 
        "l.YZI3JXZM.jn0zFcnW" - 
        "l.YZI3JXZM.JZmdtZj5" - 
        "l.YZI3JXZM.bYBIKVXn" - 
        "l.YZI3JXZM.nFxP8YKb" - 
        "l.YZI3JXZM.hDNMVYP0" - 

    .Tildes

    .ProdidFile
        "l.4VGPOFIK.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.JGNXPSZ9.BTTI4E8I" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic2.ds"
        "l.SGEJMZCU.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic3.ds"
        "l.WIAEAJVY.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.T1I939RG.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.DA8XJBW9.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.GZJA5O6C.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.636ALFWU.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
        "l.G2QE8QFO.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds"
        "l.FJ1ZBSU3.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.V14NRGSC.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.336FYZJD.c42Q6wPH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty1.ds"
        "l.NNQFP0DW.YACUz3H9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty2.ds"
        "l.F584FEOU.YMFX0PTE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty3.ds"
        "l.EP0R2YGC.SIrifQYp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty4.ds"
        "l.U1WWM48Q.ФЛГмссД5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.TAW342MZ.45mns0l-O" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.0PIDIGQS.ToUZ5J7e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.2ENRY7HC.AkoHsBxP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.499X5PCX.uqkUXoj0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.QOQUB1UK.6O4fovPJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
        "l.E6TP864U.rDD37re8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.U5LTTGUD.TSbLGnNG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.D6UB9E70.sJZOzSdo" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.ATEW5430.CMxWzMs5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.ATEW5430.0CmyN2Mb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.Z1N73TAG.OpdFntBx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.Z1N73TAG.eQxYylc3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.YEA295XP.PALnQoTQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.oVs6tsnU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.DR6GVNSX.CbALGP8d" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.o8lvOnlB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.xkQxOfc9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.HUZX3HK7.G3tWgyDr" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.k543P1uB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.SxOf3elF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.V2X8V8O9.BNdiPBY8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.u87kglXS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.4Zohe6QE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.VNvl4KbI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.YZI3JXZM.CHcd0L0E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.bYBIKVXn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.qlMb3HAO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.ryQ27h6e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"

    .ItemidFile
        "l.4VGPOFIK.QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.4VGPOFIK.54vHCQwI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.4VGPOFIK.Ll0bDtIQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.4VGPOFIK.6huM44Hm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.4VGPOFIK.oAgVUPi0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic1.ds"
        "l.JGNXPSZ9.BTTI4E8I" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic2.ds"
        "l.JGNXPSZ9.i1NLckN6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic2.ds"
        "l.SGEJMZCU.zAfn39Kh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic3.ds"
        "l.SGEJMZCU.hOy5oL3B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic3.ds"
        "l.WIAEAJVY.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.WIAEAJVY.C92Mf6yV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.WIAEAJVY.TxW3Yetp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.WIAEAJVY.08yGbnMX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.WIAEAJVY.7MZTHLMY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic4.ds"
        "l.T1I939RG.wIcCuax5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.T1I939RG.C92Mf6yV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.T1I939RG.TxW3Yetp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.T1I939RG.08yGbnMX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.T1I939RG.7MZTHLMY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_basic5.ds"
        "l.DA8XJBW9.Zcm0y9mS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.ZxMvmqeZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.xePTheNI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.l7qy3zi2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.6Nq8AWj7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.DA8XJBW9.jG4U9bwg" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.A_twoRoots.ds"
        "l.GZJA5O6C.KvtgGtnv" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.GZJA5O6C.rUEqmXfk" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.GZJA5O6C.wpra8mUV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.GZJA5O6C.VFoIEr0T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.GZJA5O6C.oI5DOuPh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments1.ds"
        "l.636ALFWU.aXLBEer9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
        "l.636ALFWU.evhAIQx4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
        "l.636ALFWU.h0e5wwEY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
        "l.636ALFWU.WryZrSIJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments2.ds"
        "l.G2QE8QFO.QuvD4gqX" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds"
        "l.G2QE8QFO.VBsu8OpW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds"
        "l.G2QE8QFO.0RdNAvNs" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments3.ds"
        "l.FJ1ZBSU3.qJobcYNC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.FJ1ZBSU3.WmtITd8B" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.FJ1ZBSU3.KGkvDUZH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.FJ1ZBSU3.BbiZz4Ie" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.FJ1ZBSU3.gCWv1P46" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments4.ds"
        "l.V14NRGSC.xpXWehDW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.V14NRGSC.TcD3LcoW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.V14NRGSC.thZBzyNc" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.V14NRGSC.dOlQGMJ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.V14NRGSC.Ln7Y7Dme" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.B_comments5.ds"
        "l.336FYZJD.c42Q6wPH" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty1.ds"
        "l.NNQFP0DW.YACUz3H9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty2.ds"
        "l.F584FEOU.YMFX0PTE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty3.ds"
        "l.EP0R2YGC.SIrifQYp" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.C_empty4.ds"
        "l.U1WWM48Q.ФЛГмссД5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.U1WWM48Q.ПеП0ТхЗй" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.U1WWM48Q.ПТъЗАфЪа" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.U1WWM48Q.5Суак3ИЙ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.U1WWM48Q.ЛКтрт5КН" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_cyrillic.ds"
        "l.TAW342MZ.45mns0l-O" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.TAW342MZ.-5g1GJyFS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.TAW342MZ.f75CKWhl-" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.TAW342MZ.68Es--hujI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.TAW342MZ.mWa4QdRm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters1.ds"
        "l.0PIDIGQS.ToUZ5J7e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.0PIDIGQS./DZChUWeh" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.0PIDIGQS.XBru/v3rK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.0PIDIGQS.7tewYK/BC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.0PIDIGQS.qStgB/Iqw" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters2.ds"
        "l.2ENRY7HC.AkoHsBxP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.2ENRY7HC.\2\2gPwg0Z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.2ENRY7HC.\6KbLpKF2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.2ENRY7HC.YA0\Cn7gP" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.2ENRY7HC.V4tLOkb5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_double_characters3.ds"
        "l.499X5PCX.uqkUXoj0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.499X5PCX.y3rd1tuM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.499X5PCX.l9JX2YWw" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.499X5PCX.INIKQpj4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.499X5PCX.gF7eKSgr" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters1.ds"
        "l.QOQUB1UK.6O4fovPJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
        "l.QOQUB1UK.cTk1qeGz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
            "l.QOQUB1UK.cTk1qeGz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
            "l.QOQUB1UK.cTk1qeGz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
            "l.QOQUB1UK.cTk1qeGz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
        "l.E6TP864U.rDD37re8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.E6TP864U.uCzQa1uW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.E6TP864U.UxMKgYjI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.E6TP864U.Ux6wwQBT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.E6TP864U.dbpyUcza" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters3.ds"
        "l.U5LTTGUD.TSbLGnNG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.U5LTTGUD.QWVZ3pp9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.U5LTTGUD.75NTfebY" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.U5LTTGUD.Sqs0lm7S" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.U5LTTGUD.GcZEI9gy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
        "l.D6UB9E70.sJZOzSdo" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.D6UB9E70.UlJXGWLS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.D6UB9E70.d4jKusMe" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.D6UB9E70.Bgx8/M6B1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.D6UB9E70.7vb\\W9VSB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_RN.ds"
        "l.ATEW5430.0CmyN2Mb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.ATEW5430.CMxWzMs5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.ATEW5430.hzAzwlx6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.ATEW5430.UHOcZPAm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.ATEW5430.BBmOZjJa" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production1.ds"
        "l.Z1N73TAG.eQxYylc3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.Z1N73TAG.tdgS8qBO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.Z1N73TAG.OpdFntBx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.Z1N73TAG.MLUxjdg8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.Z1N73TAG.qkVgxZIs" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production2.ds"
        "l.YEA295XP.oVs6tsnU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.9Y9uFDwu" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.PALnQoTQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.6hlYVfaz" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.gubSBEDe" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.YEA295XP.hAyLdw3m" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production3.ds"
        "l.DR6GVNSX.xkQxOfc9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.CbALGP8d" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.7KNUmetK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.6qFQ0HxK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.o8lvOnlB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.SbQjE2YS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.CVOSiiAS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.1G0hZLJ4" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.ozhHnNOU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.DR6GVNSX.jMBLOKGE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production4.ds"
        "l.HUZX3HK7.SxOf3elF" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.8S3IwDlG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.RV4OUQoy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.G3tWgyDr" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.AwPl7oBK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.OcIUTGif" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.k543P1uB" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.IZZ9vPiK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.OMH9y9Jn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.HUZX3HK7.UuA1ITf9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production5.ds"
        "l.V2X8V8O9.VNvl4KbI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.BNdiPBY8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.47GG8irk" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.vRje122z" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.4Zohe6QE" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.u87kglXS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.VB7KNYBw" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.gKznl6RJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.Uon0W1e7" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.rBW9kGDK" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.3QJz4slg" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.V2X8V8O9.X2BTGncx" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production6.ds"
        "l.YZI3JXZM.ryQ27h6e" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.hAdLCBLZ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.GotVxcPm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.CHcd0L0E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.jiSw0LNV" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.TpR3PZdW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.qlMb3HAO" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.jn0zFcnW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.JZmdtZj5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.bYBIKVXn" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.nFxP8YKb" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"
        "l.YZI3JXZM.hDNMVYP0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.F_production_in_production7.ds"

