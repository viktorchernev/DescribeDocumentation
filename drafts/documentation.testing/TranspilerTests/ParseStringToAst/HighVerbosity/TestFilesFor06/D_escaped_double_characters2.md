========================================
Source Code (between the arrows)
========================================

🡆fa \, br\->ics\// ->

    wool\;fabrics,
    \,cotton fabrics,
    silk fabrics,
    synthetic fabrics\;;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters2.ds"
Preprocessed source code - 110 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'br') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'ics') T(ESCAPE_LCOMMENT|'\// ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE_TERMINATOR|'\;') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE_SEPARATOR|'\,') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'silk fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(ESCAPE_TERMINATOR|'\;') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 110 characters, into 22 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor06.D_escaped_double_characters2.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fa \\, br\\->ics\\//","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n    "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool\\;fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"\\,cotton fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics\\;","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}