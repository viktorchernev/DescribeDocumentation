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
Starting a 'File -> Unfold' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"
Fetched file contents - 164 characters long

Parsing sequence: T(DATA|'Nova News playlist ') T(TAG|'<novanews> ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'April 2024 ') T(DECORATOR|'{comment}') T(SEPARATOR|',\r\n\t') T(DATA|'Monday 15 ') T(TAG|'<.novanews.20240415>') T(SEPARATOR|',\r\n\t') T(DATA|'Tuesday 16 ') T(TAG|'<.novanews.20240416>') T(SEPARATOR|',\r\n\t') T(DATA|'Wednesday 17 ') T(TAG|'<.novanews.20240417>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parse tree unfolded successfully
Done!
------------------------
File parsed successfully
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
        "novanews" -> "radiowatch.bg.YV8BWD8G", "radiowatch.bg.novanews.20240415", "radiowatch.bg.novanews.20240416", "radiowatch.bg.novanews.20240417";

    .Translations
        "novanews" - "Nova News playlist"
        "radiowatch.bg.YV8BWD8G" - "April 2024"
        "radiowatch.bg.novanews.20240415" - "Monday 15"
        "radiowatch.bg.novanews.20240416" - "Tuesday 16"
        "radiowatch.bg.novanews.20240417" - "Wednesday 17"

    .Links
        "novanews" - 
        "radiowatch.bg.YV8BWD8G" - 
        "radiowatch.bg.novanews.20240415" - 
        "radiowatch.bg.novanews.20240416" - 
        "radiowatch.bg.novanews.20240417" - 

    .Decorators
        "novanews" - 
        "radiowatch.bg.YV8BWD8G" - "comment"
        "radiowatch.bg.novanews.20240415" - 
        "radiowatch.bg.novanews.20240416" - 
        "radiowatch.bg.novanews.20240417" - 

    .Tildes
        "novanews" -> 


    .ProdidFile
        "novanews" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"

    .ItemidFile
        "novanews" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"
        "radiowatch.bg.YV8BWD8G" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"
        "radiowatch.bg.novanews.20240415" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"
        "radiowatch.bg.novanews.20240416" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"
        "radiowatch.bg.novanews.20240417" - "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\live_Radio\NovaNews.ds"

