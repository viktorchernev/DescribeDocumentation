========================================
Source Code (between the arrows)
========================================

🡆fabrics [https://en.test.org/wiki/List_of_fabrics] <QpeudYXy> ->

	wool fabrics [https://en.test.org/wiki/Wool | wikipedia] <54vHCQwI>,
	cotton fabrics [https://en.test.org/wiki/Cotton] <Ll0bDtIQ>,
	silk fabrics [https://en.test.org/wiki/Silk | test.org]<6huM44Hm>,
	synthetic fabrics [https://en.test.org/wiki/Synthetic]<oAgVUPi0>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Links - v0.8
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor08\A_basic1.ds"
Fetched file contents - 337 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://en.test.org/wiki/List_of_fabrics] ') T(TAG|'<QpeudYXy> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'wool fabrics ') T(LINK|'[https://en.test.org/wiki/Wool | wikipedia] ') T(TAG|'<54vHCQwI>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(LINK|'[https://en.test.org/wiki/Cotton] ') T(TAG|'<Ll0bDtIQ>') T(SEPARATOR|',\r\n\t') T(DATA|'silk fabrics ') T(LINK|'[https://en.test.org/wiki/Silk | test.org]') T(TAG|'<6huM44Hm>') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics ') T(LINK|'[https://en.test.org/wiki/Synthetic]') T(TAG|'<oAgVUPi0>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 337 characters, into 22 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor08\\A_basic1.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"QpeudYXy","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"54vHCQwI","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"Ll0bDtIQ","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"6huM44Hm","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"oAgVUPi0","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}