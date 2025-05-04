========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool fabrics [[http://someurl.net]],
	cotton fabrics,
	silk fabrics[[http://otherurl.net]] ,
	synthetic fabrics [[http://url.net]] ;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
Preprocessed source code - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 150 characters, into 15 tokens.
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
        "VN16WN34" 

    .Productions
        "VN16WN34" -> "Q1UEJZTC", "CSNP4LB5", "FZKI85OU", "E0W0RV8N";

    .Translations
        "VN16WN34" - "fabrics"
        "Q1UEJZTC" - "wool fabrics"
        "CSNP4LB5" - "cotton fabrics"
        "FZKI85OU" - "silk fabrics"
        "E0W0RV8N" - "synthetic fabrics"

    .Links
        "VN16WN34" - 
        "Q1UEJZTC" - "http://someurl.net"
        "CSNP4LB5" - 
        "FZKI85OU" - "http://otherurl.net"
        "E0W0RV8N" - "http://url.net"

    .Decorators
        "VN16WN34" - 
        "Q1UEJZTC" - 
        "CSNP4LB5" - 
        "FZKI85OU" - 
        "E0W0RV8N" - 

    .Tildes
        "VN16WN34" -> 


    .ProdidFile
        "VN16WN34" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"

    .ItemidFile
        "VN16WN34" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "Q1UEJZTC" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "CSNP4LB5" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "FZKI85OU" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
        "E0W0RV8N" - "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"

