========================================
Source Code (between the arrows)
========================================

🡆directives ->
	language-version <1.0>,
	namespace <radiowatch.bg>;

Nova News playlist <novanews> ->

	April 2024 {comment},
	Monday 15 <.novanews.20240415>,
	Tuesday 16 <.novanews.20240416>,
	Wednesday 17 <.novanews.20240417>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"
Preprocessed source code - 164 characters long

Parsing sequence: T(DATA|'Nova News playlist ') T(TAG|'<novanews> ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'April 2024 ') T(DECORATOR|'{comment}') T(SEPARATOR|',\r\n\t') T(DATA|'Monday 15 ') T(TAG|'<.novanews.20240415>') T(SEPARATOR|',\r\n\t') T(DATA|'Tuesday 16 ') T(TAG|'<.novanews.20240416>') T(SEPARATOR|',\r\n\t') T(DATA|'Wednesday 17 ') T(TAG|'<.novanews.20240417>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 164 characters, into 17 tokens.
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
        "novanews" 

    .Productions
        "novanews" -> "radiowatch.bg.X1SNKTAC", "radiowatch.bg.novanews.20240415", "radiowatch.bg.novanews.20240416", "radiowatch.bg.novanews.20240417";

    .Translations
        "novanews" - "Nova News playlist"
        "radiowatch.bg.X1SNKTAC" - "April 2024"
        "radiowatch.bg.novanews.20240415" - "Monday 15"
        "radiowatch.bg.novanews.20240416" - "Tuesday 16"
        "radiowatch.bg.novanews.20240417" - "Wednesday 17"

    .Links
        "novanews" - 
        "radiowatch.bg.X1SNKTAC" - 
        "radiowatch.bg.novanews.20240415" - 
        "radiowatch.bg.novanews.20240416" - 
        "radiowatch.bg.novanews.20240417" - 

    .Decorators
        "novanews" - 
        "radiowatch.bg.X1SNKTAC" - "comment"
        "radiowatch.bg.novanews.20240415" - 
        "radiowatch.bg.novanews.20240416" - 
        "radiowatch.bg.novanews.20240417" - 

    .Tildes
        "novanews" -> 


    .ProdidFile
        "novanews" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"

    .ItemidFile
        "novanews" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"
        "radiowatch.bg.X1SNKTAC" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"
        "radiowatch.bg.novanews.20240415" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"
        "radiowatch.bg.novanews.20240416" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"
        "radiowatch.bg.novanews.20240417" - "Tests.Integration.Transpiler.TestFiles.live_Radio.NovaNews.ds"

