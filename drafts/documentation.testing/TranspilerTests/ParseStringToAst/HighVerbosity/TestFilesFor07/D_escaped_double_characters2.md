========================================
Source Code (between the arrows)
========================================

🡆fa \, br\->ics\// <6O4fovPJ>->

    wool\;fabrics <cTk1qeGz>,
    \,cotton fabrics\<<cTk1qeGz>,
    silk fabrics<cTk1qeGz>  ,
    synthetic fabrics\; <cTk1qeGz>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Tags - v0.7
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds"
Preprocessed source code - 166 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics') T(ESCAPE_LCOMMENT|'\// ') T(TAG|'<6O4fovPJ>') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics ') T(TAG|'<cTk1qeGz>') T(SEPARATOR|',\r\n    ') T(ESCAPE_SEPARATOR|'\,') T(DATA|'cotton fabrics') T(ESCAPE_LEFT_ARROW|'\<') T(TAG|'<cTk1qeGz>') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(TAG|'<cTk1qeGz>  ') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_TERMINATOR|'\; ') T(TAG|'<cTk1qeGz>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 166 characters, into 28 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor07.D_escaped_double_characters2.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fa \\, br\\->ics\\//","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"6O4fovPJ","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n    "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool\\;fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"cTk1qeGz","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"\\,cotton fabrics\\<","leadingTrivia":"","trailingTrivia":""},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"cTk1qeGz","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"cTk1qeGz","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":"  "}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics\\;","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"cTk1qeGz","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}