========================================
Source Code (between the arrows)
========================================

🡆fabrics ->// comment
/* comment */

	wool fabrics,
	cotton fabrics,// comment
	/* comment */

	silk fabrics,
	synthetic fabrics;/* comment *//* comment */
	// comment🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
Preprocessed source code - 175 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>// comment\r\n') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';/* comment *//* comment */\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 175 characters, into 12 tokens.
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
        "LHO5JYP1" 

    .Productions
        "LHO5JYP1" -> "WK8CW136", "W9L1BK4J", "W9DI9ES2", "GOC2E3E8";

    .Translations
        "LHO5JYP1" - "fabrics"
        "WK8CW136" - "wool fabrics"
        "W9L1BK4J" - "cotton fabrics"
        "W9DI9ES2" - "silk fabrics"
        "GOC2E3E8" - "synthetic fabrics"

    .Links
        "LHO5JYP1" - 
        "WK8CW136" - 
        "W9L1BK4J" - 
        "W9DI9ES2" - 
        "GOC2E3E8" - 

    .Decorators
        "LHO5JYP1" - 
        "WK8CW136" - 
        "W9L1BK4J" - 
        "W9DI9ES2" - 
        "GOC2E3E8" - 

    .Tildes
        "LHO5JYP1" -> 


    .ProdidFile
        "LHO5JYP1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"

    .ItemidFile
        "LHO5JYP1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "WK8CW136" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "W9L1BK4J" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "W9DI9ES2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"
        "GOC2E3E8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_multiple_mixed_comments.ds"

