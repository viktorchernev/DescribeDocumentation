========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool\;; fabrics ->
	cotton ;\; fabrics ->
	silk \;\;fabrics->
	synthetic ,
	fabrics\;;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
Preprocessed source code - 112 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(SEMICOLON|'; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(SEMICOLON|';') T(ESCAPE_TERMINATOR|'\; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(ESCAPE_TERMINATOR|'\;') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 112 characters, into 30 tokens.
Those were translated to 4 productions, containing 6 entries.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "8K0AN61C" 

    .Productions
        "VS360VU6" -> "U1QL7FAS", "HFZBX12T";
        "UEWJWMQM" -> "VS360VU6";
        "9YPVJ2SC" -> "UEWJWMQM";
        "8K0AN61C" -> "9YPVJ2SC";

    .Translations
        "8K0AN61C" - "fabrics"
        "9YPVJ2SC" - "wool\;; fabrics"
        "UEWJWMQM" - "cotton ;\; fabrics"
        "VS360VU6" - "silk \;\;fabrics"
        "U1QL7FAS" - "synthetic"
        "HFZBX12T" - "fabrics\;"

    .Links
        "8K0AN61C" - 
        "9YPVJ2SC" - 
        "UEWJWMQM" - 
        "VS360VU6" - 
        "U1QL7FAS" - 
        "HFZBX12T" - 

    .Decorators
        "8K0AN61C" - 
        "9YPVJ2SC" - 
        "UEWJWMQM" - 
        "VS360VU6" - 
        "U1QL7FAS" - 
        "HFZBX12T" - 

    .Tildes
        "VS360VU6" -> 
        "UEWJWMQM" -> 
        "9YPVJ2SC" -> 
        "8K0AN61C" -> 


    .ProdidFile
        "VS360VU6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "UEWJWMQM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "9YPVJ2SC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "8K0AN61C" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"

    .ItemidFile
        "8K0AN61C" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "9YPVJ2SC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "UEWJWMQM" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "VS360VU6" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "U1QL7FAS" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"
        "HFZBX12T" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_semicolons.ds"

