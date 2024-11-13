========================================
Source Code (between the arrows)
========================================

🡆fabrics [https://www.notube.com/watch?v=hTui12lKus]-> 
	
	synthetic fabrics https://some-link/
	<i1NLckN6> 
	[https://www.notube.com/watch?v=hTui12lKus]
	{
		info | more info here
	}
	;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Decorators - v0.9
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor09\A_basic2.ds"
Fetched file contents - 193 characters long

Parsing sequence: T(DATA|'fabrics ') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]') T(HYPHEN|'-') T(RIGHT_ARROW|'> \r\n\t\r\n\t') T(DATA|'synthetic fabrics https') T(PROTO_SLASHES|'://') T(DATA|'some') T(HYPHEN|'-') T(DATA|'link') T(FORWARD_SLASH|'/\r\n\t') T(TAG|'<i1NLckN6> \r\n\t') T(LINK|'[https://www.notube.com/watch?v=hTui12lKus]\r\n\t') T(DECORATOR|'{\r\n\t\tinfo | more info here\r\n\t}\r\n\t') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 193 characters, into 15 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor09\\A_basic2.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":" \r\n\t\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics https://some-link/","leadingTrivia":"","trailingTrivia":"\r\n\t"},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"i1NLckN6","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":" \r\n\t"}},"links":null,"decorators":null},"punctuation":{"leafType":"Text","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}