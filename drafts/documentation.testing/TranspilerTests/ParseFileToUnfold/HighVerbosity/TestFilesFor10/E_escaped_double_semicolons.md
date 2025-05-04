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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
Fetched file contents - 112 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(SEMICOLON|'; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton ') T(SEMICOLON|';') T(ESCAPE_TERMINATOR|'\; ') T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk ') T(ESCAPE_TERMINATOR|'\;') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic ') T(SEPARATOR|',\r\n\t') T(DATA|'fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(TERMINATOR|';\n') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "CJKLZ7TH" 

    .Productions
        "RO3ZUFLP" -> "148QEKBY", "DJGK94FH";
        "8TF6QC0H" -> "RO3ZUFLP";
        "CRJT5EIF" -> "8TF6QC0H";
        "CJKLZ7TH" -> "CRJT5EIF";

    .Translations
        "CJKLZ7TH" - "fabrics"
        "CRJT5EIF" - "wool\;; fabrics"
        "8TF6QC0H" - "cotton ;\; fabrics"
        "RO3ZUFLP" - "silk \;\;fabrics"
        "148QEKBY" - "synthetic"
        "DJGK94FH" - "fabrics\;"

    .Links
        "CJKLZ7TH" - 
        "CRJT5EIF" - 
        "8TF6QC0H" - 
        "RO3ZUFLP" - 
        "148QEKBY" - 
        "DJGK94FH" - 

    .Decorators
        "CJKLZ7TH" - 
        "CRJT5EIF" - 
        "8TF6QC0H" - 
        "RO3ZUFLP" - 
        "148QEKBY" - 
        "DJGK94FH" - 

    .Tildes
        "RO3ZUFLP" -> 
        "8TF6QC0H" -> 
        "CRJT5EIF" -> 
        "CJKLZ7TH" -> 


    .ProdidFile
        "RO3ZUFLP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "8TF6QC0H" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "CRJT5EIF" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "CJKLZ7TH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"

    .ItemidFile
        "CJKLZ7TH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "CRJT5EIF" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "8TF6QC0H" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "RO3ZUFLP" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "148QEKBY" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"
        "DJGK94FH" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\E_escaped_double_semicolons.ds"

