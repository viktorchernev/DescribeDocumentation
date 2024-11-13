========================================
Source Code (between the arrows)
========================================

🡆fabrics ->	  // comment
 /* comment */

	wool fabrics,
	cotton fabrics,	// comment
	/* comment */

	silk fabrics,
	synthetic fabrics;  /* comment */ /* comment */	
	// comment🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
Preprocessed source code - 184 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\t  // comment\r\n ') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\t// comment\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';  /* comment */ /* comment */\t\r\n\t') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 184 characters, into 12 tokens.
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
        "S7HBDVRJ" 

    .Productions
        "S7HBDVRJ" -> "TDOPC7R8", "VD75JF7D", "XM461WU1", "4GAWSU51";

    .Translations
        "S7HBDVRJ" - "fabrics"
        "TDOPC7R8" - "wool fabrics"
        "VD75JF7D" - "cotton fabrics"
        "XM461WU1" - "silk fabrics"
        "4GAWSU51" - "synthetic fabrics"

    .Links
        "S7HBDVRJ" - 
        "TDOPC7R8" - 
        "VD75JF7D" - 
        "XM461WU1" - 
        "4GAWSU51" - 

    .Decorators
        "S7HBDVRJ" - 
        "TDOPC7R8" - 
        "VD75JF7D" - 
        "XM461WU1" - 
        "4GAWSU51" - 

    .Tildes
        "S7HBDVRJ" -> 


    .ProdidFile
        "S7HBDVRJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"

    .ItemidFile
        "S7HBDVRJ" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "TDOPC7R8" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "VD75JF7D" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "XM461WU1" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"
        "4GAWSU51" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_comments_and_spaces.ds"

