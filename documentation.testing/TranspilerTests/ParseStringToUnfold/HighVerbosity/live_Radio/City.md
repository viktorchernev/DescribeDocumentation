========================================
Source Code (between the arrows)
========================================

🡆directives ->
	language-version <1.0>,
	namespace <radiowatch.bg>;

Radio City playlist <city> ->

	April 2024 {comment},
	Monday 15 <.city.20240415>,
	Tuesday 16 <.city.20240416>,
	Wednesday 17 <.city.20240417>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"
Preprocessed source code - 149 characters long

Parsing sequence: T(DATA|'Radio City playlist ') T(TAG|'<city> ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'April 2024 ') T(DECORATOR|'{comment}') T(SEPARATOR|',\r\n\t') T(DATA|'Monday 15 ') T(TAG|'<.city.20240415>') T(SEPARATOR|',\r\n\t') T(DATA|'Tuesday 16 ') T(TAG|'<.city.20240416>') T(SEPARATOR|',\r\n\t') T(DATA|'Wednesday 17 ') T(TAG|'<.city.20240417>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 149 characters, into 17 tokens.
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
        "city" 

    .Productions
        "city" -> "radiowatch.bg.26YMEU4F", "radiowatch.bg.city.20240415", "radiowatch.bg.city.20240416", "radiowatch.bg.city.20240417";

    .Translations
        "city" - "Radio City playlist"
        "radiowatch.bg.26YMEU4F" - "April 2024"
        "radiowatch.bg.city.20240415" - "Monday 15"
        "radiowatch.bg.city.20240416" - "Tuesday 16"
        "radiowatch.bg.city.20240417" - "Wednesday 17"

    .Links
        "city" - 
        "radiowatch.bg.26YMEU4F" - 
        "radiowatch.bg.city.20240415" - 
        "radiowatch.bg.city.20240416" - 
        "radiowatch.bg.city.20240417" - 

    .Decorators
        "city" - 
        "radiowatch.bg.26YMEU4F" - "comment"
        "radiowatch.bg.city.20240415" - 
        "radiowatch.bg.city.20240416" - 
        "radiowatch.bg.city.20240417" - 

    .Tildes
        "city" -> 


    .ProdidFile
        "city" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"

    .ItemidFile
        "city" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"
        "radiowatch.bg.26YMEU4F" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"
        "radiowatch.bg.city.20240415" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"
        "radiowatch.bg.city.20240416" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"
        "radiowatch.bg.city.20240417" - "Tests.Integration.Transpiler.TestFiles.live_Radio.City.ds"

