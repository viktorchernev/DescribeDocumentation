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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"
Fetched file contents - 149 characters long

Parsing sequence: T(DATA|'Radio City playlist ') T(TAG|'<city> ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'April 2024 ') T(DECORATOR|'{comment}') T(SEPARATOR|',\r\n\t') T(DATA|'Monday 15 ') T(TAG|'<.city.20240415>') T(SEPARATOR|',\r\n\t') T(DATA|'Tuesday 16 ') T(TAG|'<.city.20240416>') T(SEPARATOR|',\r\n\t') T(DATA|'Wednesday 17 ') T(TAG|'<.city.20240417>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "city" -> "radiowatch.bg.YRCZX30V", "radiowatch.bg.city.20240415", "radiowatch.bg.city.20240416", "radiowatch.bg.city.20240417";

    .Translations
        "city" - "Radio City playlist"
        "radiowatch.bg.YRCZX30V" - "April 2024"
        "radiowatch.bg.city.20240415" - "Monday 15"
        "radiowatch.bg.city.20240416" - "Tuesday 16"
        "radiowatch.bg.city.20240417" - "Wednesday 17"

    .Links
        "city" - 
        "radiowatch.bg.YRCZX30V" - 
        "radiowatch.bg.city.20240415" - 
        "radiowatch.bg.city.20240416" - 
        "radiowatch.bg.city.20240417" - 

    .Decorators
        "city" - 
        "radiowatch.bg.YRCZX30V" - "comment"
        "radiowatch.bg.city.20240415" - 
        "radiowatch.bg.city.20240416" - 
        "radiowatch.bg.city.20240417" - 

    .Tildes
        "city" -> 


    .ProdidFile
        "city" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"

    .ItemidFile
        "city" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"
        "radiowatch.bg.YRCZX30V" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"
        "radiowatch.bg.city.20240415" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"
        "radiowatch.bg.city.20240416" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"
        "radiowatch.bg.city.20240417" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\City.ds"

