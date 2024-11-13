========================================
Source Code (between the arrows)
========================================

🡆fabrics \->> wool fabrics ->
	synthetic fabrics;

fabrics->\> wool fabrics ->
	cotton fabrics;

fabrics -\>>wool fabrics ->
	silk fabrics;

fabrics-\>\>wool fabrics ->
	other fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds"
Preprocessed source code - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(ESCAPE_HYPHEN|'\-') T(PRODUCTION_ARROW|'>> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'synthetic fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(RIGHT_ARROW|'>') T(ESCAPE_RIGHT_ARROW|'\> ') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'cotton fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics ') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(RIGHT_ARROW|'>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'silk fabrics') T(TERMINATOR|';\r\n\r\n') T(DATA|'fabrics') T(HYPHEN|'-') T(ESCAPE_RIGHT_ARROW|'\>') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'wool fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\t') T(DATA|'other fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 193 characters, into 36 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor10.E_escaped_double_producers.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics \\->> wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":"\r\n\r\n"}}]},{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics->\\> wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":"\r\n\r\n"}}]},{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics -\\>>wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":"\r\n\r\n"}}]},{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics-\\>\\>wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"other fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}