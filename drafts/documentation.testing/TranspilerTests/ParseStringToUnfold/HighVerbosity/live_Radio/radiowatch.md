========================================
Source Code (between the arrows)
========================================

🡆directives ->
	language-version <1.0>,
	namespace <radiowatch>;

Radio playlists <.rnode> ->

	Bulgarian {comment},
	Radio 1 Rock playlist <.bg.onerock>,
	Radio Energy playlist <.bg.energy>,
	Nova News playlist <.bg.novanews>,
	Radio City playlist <.bg.city>,
	Radio Veselina playlist <.bg.veselina>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> Unfold' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
Preprocessed source code - 242 characters long

Parsing sequence: T(DATA|'Radio playlists ') T(TAG|'<.rnode> ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'Bulgarian ') T(DECORATOR|'{comment}') T(SEPARATOR|',\r\n\t') T(DATA|'Radio 1 Rock playlist ') T(TAG|'<.bg.onerock>') T(SEPARATOR|',\r\n\t') T(DATA|'Radio Energy playlist ') T(TAG|'<.bg.energy>') T(SEPARATOR|',\r\n\t') T(DATA|'Nova News playlist ') T(TAG|'<.bg.novanews>') T(SEPARATOR|',\r\n\t') T(DATA|'Radio City playlist ') T(TAG|'<.bg.city>') T(SEPARATOR|',\r\n\t') T(DATA|'Radio Veselina playlist ') T(TAG|'<.bg.veselina>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 242 characters, into 23 tokens.
Those were translated to 1 productions, containing 7 entries.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced Unfold
========================================

DescribeUnfold

    .AllFiles
    .ParsedFiles
    .FailedFiles

    .PrimaryProductions
        "radiowatch.rnode" 

    .Productions
        "radiowatch.rnode" -> "radiowatch.0Y8GZG5A", "radiowatch.bg.onerock", "radiowatch.bg.energy", "radiowatch.bg.novanews", "radiowatch.bg.city", "radiowatch.bg.veselina";

    .Translations
        "radiowatch.rnode" - "Radio playlists"
        "radiowatch.0Y8GZG5A" - "Bulgarian"
        "radiowatch.bg.onerock" - "Radio 1 Rock playlist"
        "radiowatch.bg.energy" - "Radio Energy playlist"
        "radiowatch.bg.novanews" - "Nova News playlist"
        "radiowatch.bg.city" - "Radio City playlist"
        "radiowatch.bg.veselina" - "Radio Veselina playlist"

    .Links
        "radiowatch.rnode" - 
        "radiowatch.0Y8GZG5A" - 
        "radiowatch.bg.onerock" - 
        "radiowatch.bg.energy" - 
        "radiowatch.bg.novanews" - 
        "radiowatch.bg.city" - 
        "radiowatch.bg.veselina" - 

    .Decorators
        "radiowatch.rnode" - 
        "radiowatch.0Y8GZG5A" - "comment"
        "radiowatch.bg.onerock" - 
        "radiowatch.bg.energy" - 
        "radiowatch.bg.novanews" - 
        "radiowatch.bg.city" - 
        "radiowatch.bg.veselina" - 

    .Tildes
        "radiowatch.rnode" -> 


    .ProdidFile
        "radiowatch.rnode" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"

    .ItemidFile
        "radiowatch.rnode" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.0Y8GZG5A" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.bg.onerock" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.bg.energy" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.bg.novanews" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.bg.city" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"
        "radiowatch.bg.veselina" - "Tests.Integration.Transpiler.TestFiles.live_Radio.radiowatch.ds"

