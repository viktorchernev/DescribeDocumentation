========================================
Source Code (between the arrows)
========================================

🡆fabric     s 	->

	wool   fabrics	,
	cotton\, fabrics textiles  ,
    silk\->fabrics,
    syntic 		fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor06\E_spaces_escapes_N.ds"
Fetched file contents - 107 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n\t') T(DATA|'wool   fabrics\t') T(SEPARATOR|',\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles  ') T(SEPARATOR|',\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(SEPARATOR|',\n    ') T(DATA|'syntic \t\tfabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 107 characters, into 17 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor06\\E_spaces_escapes_N.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabric     s","leadingTrivia":"","trailingTrivia":" \t"},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\n\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool   fabrics","leadingTrivia":"","trailingTrivia":"\t"},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton\\, fabrics textiles","leadingTrivia":"","trailingTrivia":"  "},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk\\->fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"syntic \t\tfabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}