========================================
Source Code (between the arrows)
========================================

🡆fabrics ->

	wool < fabrics <<someid>>,
	cotton >fabrics <<someid>> ,
	silk fabrics<<someid>> ,
	synthetic<>fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Doubles - v1.1
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor11\A_tags2.ds"
Fetched file contents - 121 characters long

Parsing sequence: T(DATA|'fabrics ') T(HYPHEN|'-') T(PRODUCTION_ARROW|'>\r\n\r\n\t') T(DATA|'wool ') T(LEFT_ARROW|'< ') T(DATA|'fabrics ') T(TAG|'<<someid>>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton ') T(RIGHT_ARROW|'>') T(DATA|'fabrics ') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics') T(TAG|'<<someid>> ') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic') T(LEFT_ARROW|'<') T(RIGHT_ARROW|'>') T(DATA|'fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 121 characters, into 22 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor11\\A_tags2.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool < fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"someid","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">>","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton >fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"someid","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">>","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":{"openBracket":{"leafType":"OpenTag","text":"<<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"someid","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">>","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic<>fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}