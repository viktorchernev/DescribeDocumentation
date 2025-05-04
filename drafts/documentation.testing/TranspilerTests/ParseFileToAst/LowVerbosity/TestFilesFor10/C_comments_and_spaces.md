========================================
Source Code (between the arrows)
========================================

🡆fabrics ->	  // comment
 /* comment */

	wool fabrics,
	cotton fabrics,	// comment
	/* comment */

	silk fabrics,
	synthetic fabrics;  /* comment */ /* comment */	
	// comment🡄

========================================
Logged text
========================================

🡆Verbosity set to: Low
Language version set to: Describe Lines - v1.0
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
"C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor10\C_comments_and_spaces.ds" - parsed successfully
Parser red 184 characters, into 12 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor10\\C_comments_and_spaces.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->\t  // comment","leadingTrivia":"","trailingTrivia":"\r\n "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",\t// comment","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";  /* comment */ /* comment */","leadingTrivia":"","trailingTrivia":"\t\r\n\t"}}]}],"exception":null}