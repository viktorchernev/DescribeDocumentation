========================================
Source Code (between the arrows)
========================================

🡆fabrics [https://en.test.org/wiki/List_of_fabrics] <QpeudYXy> ->

	http://fabrics.com wool [https://en.test.org/wiki/Wool] {}<54vHCQwI>,
	cotton fabrics [https://en.test.org/wiki/Cotton]{} <Ll0bDtIQ>,
	silk http://fabrics.com/index.html fabrics {}[https://en.test.org/wiki/Silk]<6huM44Hm>,
	synthetic fabrics{} [https://en.test.org/wiki/Synthetic]<oAgVUPi0>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Decorators - v0.9
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds"
Preprocessed source code - 363 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://en.test.org/wiki/List_of_fabrics] ') T(TAG|'<QpeudYXy> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'http') T(PROTO_SLASHES|'://') T(DATA|'fabrics.com wool ') T(LINK|'[https://en.test.org/wiki/Wool] ') T(DECORATOR|'{}') T(TAG|'<54vHCQwI>') T(SEPARATOR|',\r\n\t') T(DATA|'cotton fabrics ') T(LINK|'[https://en.test.org/wiki/Cotton]') T(DECORATOR|'{} ') T(TAG|'<Ll0bDtIQ>') T(SEPARATOR|',\r\n\t') T(DATA|'silk http') T(PROTO_SLASHES|'://') T(DATA|'fabrics.com') T(FORWARD_SLASH|'/') T(DATA|'index.html fabrics ') T(DECORATOR|'{}') T(LINK|'[https://en.test.org/wiki/Silk]') T(TAG|'<6huM44Hm>') T(SEPARATOR|',\r\n\t') T(DATA|'synthetic fabrics') T(DECORATOR|'{} ') T(LINK|'[https://en.test.org/wiki/Synthetic]') T(TAG|'<oAgVUPi0>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 363 characters, into 32 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor09.A_basic1.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"QpeudYXy","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"http://fabrics.com wool","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"54vHCQwI","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"Ll0bDtIQ","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk http://fabrics.com/index.html fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"6huM44Hm","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":""},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"oAgVUPi0","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}