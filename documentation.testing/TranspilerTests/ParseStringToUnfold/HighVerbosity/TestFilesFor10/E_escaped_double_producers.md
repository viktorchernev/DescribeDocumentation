========================================
Source Code (between the arrows)
========================================

🡆fabrics \->> wool fabrics ->
	synthetic fabrics;

fabrics->\> wool fabrics ->
	cotton fabrics;

fabrics -\>>wool fabrics ->
	silk fabrics;

fabrics-\>\>wool fabrics ->
	other fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
Preprocessed source code - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(ESCAPE_HYPHEN|'\-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(ESCAPE_RIGHT_ARROW|'\> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(RIGHT_ARROW|'>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 193 characters, into 36 tokens.
Those were translated to 4 productions, containing 8 entries.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "Z729OTOM" "49SZNG63" "U6TD8H81" "MBNWP93P" 

    .Productions
        "Z729OTOM" -> "SRS57X3";
        "49SZNG63" -> "KQOYET2";
        "U6TD8H81" -> "NQ07TME";
        "MBNWP93P" -> "7Z02PEW";

    .Translations
        "Z729OTOM" - "fabrics \->> wool fabrics"
        "YSRS57X3" - "synthetic fabrics"
        "49SZNG63" - "fabrics->\> wool fabrics"
        "KKQOYET2" - "cotton fabrics"
        "U6TD8H81" - "fabrics -\>>wool fabrics"
        "YNQ07TME" - "silk fabrics"
        "MBNWP93P" - "fabrics-\>\>wool fabrics"
        "B7Z02PEW" - "other fabrics"

    .Links
        "Z729OTOM" - 
        "YSRS57X3" - 
        "49SZNG63" - 
        "KKQOYET2" - 
        "U6TD8H81" - 
        "YNQ07TME" - 
        "MBNWP93P" - 
        "B7Z02PEW" - 

    .Decorators
        "Z729OTOM" - 
        "YSRS57X3" - 
        "49SZNG63" - 
        "KKQOYET2" - 
        "U6TD8H81" - 
        "YNQ07TME" - 
        "MBNWP93P" - 
        "B7Z02PEW" - 

    .Tildes
        "Z729OTOM" -> 
        "49SZNG63" -> 
        "U6TD8H81" -> 
        "MBNWP93P" -> 


    .ProdidFile
        "Z729OTOM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "49SZNG63" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "U6TD8H81" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "MBNWP93P" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"

    .ItemidFile
        "Z729OTOM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "YSRS57X3" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "49SZNG63" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "KKQOYET2" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "U6TD8H81" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "YNQ07TME" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "MBNWP93P" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
        "B7Z02PEW" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"

