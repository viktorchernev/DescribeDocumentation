========================================
Source Code (between the arrows)
========================================

🡆fabrics [https://en.test.org/wiki/List_of_fabrics] <QpeudYXy> ->

	wool fabrics [https://en.test.org/wiki/Wool | wikipedia] <54vHCQwI>,
	cotton fabrics [https://en.test.org/wiki/Cotton] <Ll0bDtIQ>,
	silk fabrics [https://en.test.org/wiki/Silk | test.org]<6huM44Hm>,
	synthetic fabrics [https://en.test.org/wiki/Synthetic]<oAgVUPi0>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Links - v0.8
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
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
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "QpeudYXy" 

    .Productions
        "QpeudYXy" -> "54vHCQwI", "Ll0bDtIQ", "6huM44Hm", "oAgVUPi0";

    .Translations
        "QpeudYXy" - "fabrics"
        "54vHCQwI" - "wool fabrics"
        "Ll0bDtIQ" - "cotton fabrics"
        "6huM44Hm" - "silk fabrics"
        "oAgVUPi0" - "synthetic fabrics"

    .Links
        "QpeudYXy" - "https://en.test.org/wiki/List_of_fabrics"
        "54vHCQwI" -  | "wikipedia"
        "Ll0bDtIQ" - "https://en.test.org/wiki/Cotton"
        "6huM44Hm" -  | "test.org"
        "oAgVUPi0" - "https://en.test.org/wiki/Synthetic"

    .Decorators
        "QpeudYXy" - 
        "54vHCQwI" - 
        "Ll0bDtIQ" - 
        "6huM44Hm" - 
        "oAgVUPi0" - 

    .Tildes

    .ProdidFile
        "QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"

    .ItemidFile
        "QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "54vHCQwI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "Ll0bDtIQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "6huM44Hm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"
        "oAgVUPi0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor08.A_basic1.ds"

