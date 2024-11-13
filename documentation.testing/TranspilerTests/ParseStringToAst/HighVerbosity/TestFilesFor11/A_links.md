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
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds"
Preprocessed source code - 150 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[[http://someurl.net]]') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(LINK|'[[http://otherurl.net]] ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[[http://url.net]] ') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 150 characters, into 15 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor11.A_links.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}