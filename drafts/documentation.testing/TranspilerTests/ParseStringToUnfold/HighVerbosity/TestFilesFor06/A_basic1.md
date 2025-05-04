========================================
Source Code (between the arrows)
========================================

🡆fabric*s ->

	wool http://abc.de fabrics,
	cotton fabrics,
	silk fabrics,
	synthetic fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
Preprocessed source code - 98 characters long

Parsing sequence: T(DATA|'fabric') T(STAR|'*') T(DATA|'s ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool http') T(PROTO_SLASHES|'://') T(DATA|'abc.de fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 98 characters, into 16 tokens.
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
        "MOEP32BT" 

    .Productions
        "MOEP32BT" -> "2W9GVB8G", "1DIX0CX1", "0ZNA0KMG", "MVZEOUNL";

    .Translations
        "MOEP32BT" - "fabric*s"
        "2W9GVB8G" - "wool http://abc.de fabrics"
        "1DIX0CX1" - "cotton fabrics"
        "0ZNA0KMG" - "silk fabrics"
        "MVZEOUNL" - "synthetic fabrics"

    .Links
        "MOEP32BT" - 
        "2W9GVB8G" - 
        "1DIX0CX1" - 
        "0ZNA0KMG" - 
        "MVZEOUNL" - 

    .Decorators
        "MOEP32BT" - 
        "2W9GVB8G" - 
        "1DIX0CX1" - 
        "0ZNA0KMG" - 
        "MVZEOUNL" - 

    .Tildes

    .ProdidFile
        "MOEP32BT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"

    .ItemidFile
        "MOEP32BT" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
        "2W9GVB8G" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
        "1DIX0CX1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
        "0ZNA0KMG" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"
        "MVZEOUNL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_basic1.ds"

