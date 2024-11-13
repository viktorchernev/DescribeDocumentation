========================================
Source Code (between the arrows)
========================================

🡆fabrics -> /* comment *//* comment */
/* comment */

	wool fabrics,
	cotton fabrics, /*comment*/
	/* comment */
	silk fabrics,
	synthetic fabrics; /* comment *//* comment */🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
Fetched file contents - 180 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'> /* comment *//* comment */\r\n/* comment */\r\n\r\n\t') T(DATA|'wool fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|', /*comment*/\r\n\t/* comment */\r\n\t') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|'; /* comment *//* comment */') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
Parser red 180 characters, into 12 tokens.
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
        "DGR026YG" 

    .Productions
        "DGR026YG" -> "8SA84NA1", "JZ7O3BPQ", "X61ZFPJJ", "E5W5ROX0";

    .Translations
        "DGR026YG" - "fabrics"
        "8SA84NA1" - "wool fabrics"
        "JZ7O3BPQ" - "cotton fabrics"
        "X61ZFPJJ" - "silk fabrics"
        "E5W5ROX0" - "synthetic fabrics"

    .Links
        "DGR026YG" - 
        "8SA84NA1" - 
        "JZ7O3BPQ" - 
        "X61ZFPJJ" - 
        "E5W5ROX0" - 

    .Decorators
        "DGR026YG" - 
        "8SA84NA1" - 
        "JZ7O3BPQ" - 
        "X61ZFPJJ" - 
        "E5W5ROX0" - 

    .Tildes
        "DGR026YG" -> 


    .ProdidFile
        "DGR026YG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"

    .ItemidFile
        "DGR026YG" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "8SA84NA1" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "JZ7O3BPQ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "X61ZFPJJ" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"
        "E5W5ROX0" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_multiple_block_comments.ds"

