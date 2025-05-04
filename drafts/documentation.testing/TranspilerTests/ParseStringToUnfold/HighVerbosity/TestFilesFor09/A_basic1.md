========================================
Source Code (between the arrows)
========================================

🡆fabrics [https://en.test.org/wiki/List_of_fabrics] <QpeudYXy> ->

	http://fabrics.com wool [https://en.test.org/wiki/Wool] {}<54vHCQwI>,
	cotton fabrics [https://en.test.org/wiki/Cotton]{} <Ll0bDtIQ>,
	silk http://fabrics.com/index.html fabrics {}[https://en.test.org/wiki/Silk]<6huM44Hm>,
	synthetic fabrics{} [https://en.test.org/wiki/Synthetic]<oAgVUPi0>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Decorators - v0.9
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
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
        "54vHCQwI" - "http://fabrics.com wool"
        "Ll0bDtIQ" - "cotton fabrics"
        "6huM44Hm" - "silk http://fabrics.com/index.html fabrics"
        "oAgVUPi0" - "synthetic fabrics"

    .Links
        "QpeudYXy" - "https://en.test.org/wiki/List_of_fabrics"
        "54vHCQwI" - "https://en.test.org/wiki/Wool"
        "Ll0bDtIQ" - "https://en.test.org/wiki/Cotton"
        "6huM44Hm" - "https://en.test.org/wiki/Silk"
        "oAgVUPi0" - "https://en.test.org/wiki/Synthetic"

    .Decorators
        "QpeudYXy" - 
        "54vHCQwI" - 
        "Ll0bDtIQ" - 
        "6huM44Hm" - 
        "oAgVUPi0" - 

    .Tildes

    .ProdidFile
        "QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"

    .ItemidFile
        "QpeudYXy" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "54vHCQwI" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "Ll0bDtIQ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "6huM44Hm" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
        "oAgVUPi0" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"

