========================================
Source Code (between the arrows)
========================================

🡆fabrics -> /* comment */

	wool fabrics,
	cotton fabrics, /* comment *//* comment */
	silk fabrics,
	synthetic fabrics; /* comment */🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
Preprocessed source code - 138 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /* comment *//* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment */') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 138 characters, into 12 tokens.
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
        "GPYA0M3E" 

    .Productions
        "GPYA0M3E" -> "ISQMZNGL", "2VL410LM", "I2IAUAF9", "7FFPOHWR";

    .Translations
        "GPYA0M3E" - "fabrics"
        "ISQMZNGL" - "wool fabrics"
        "2VL410LM" - "cotton fabrics"
        "I2IAUAF9" - "silk fabrics"
        "7FFPOHWR" - "synthetic fabrics"

    .Links
        "GPYA0M3E" - 
        "ISQMZNGL" - 
        "2VL410LM" - 
        "I2IAUAF9" - 
        "7FFPOHWR" - 

    .Decorators
        "GPYA0M3E" - 
        "ISQMZNGL" - 
        "2VL410LM" - 
        "I2IAUAF9" - 
        "7FFPOHWR" - 

    .Tildes
        "GPYA0M3E" -> 


    .ProdidFile
        "GPYA0M3E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"

    .ItemidFile
        "GPYA0M3E" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "ISQMZNGL" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "2VL410LM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "I2IAUAF9" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"
        "7FFPOHWR" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.C_block_comment.ds"

