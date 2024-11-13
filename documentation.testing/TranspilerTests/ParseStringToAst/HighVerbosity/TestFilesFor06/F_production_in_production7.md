========================================
Source Code (between the arrows)
========================================

🡆macronutrients ->

	water,
    salt,
    fiber ->

        what,
        not;
	
	science ->
			
		informathics,
		medicine,
		
		math ->
			algebra,
			geometry;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production7.ds"
Preprocessed source code - 179 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n\t') T(DATA|'water') T(SEPARATOR|',\r\n    ') T(DATA|'salt') T(SEPARATOR|',\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n\t\r\n\t') T(DATA|'science ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t\r\n\t\t') T(DATA|'informathics') T(SEPARATOR|',\r\n\t\t') T(DATA|'medicine') T(SEPARATOR|',\r\n\t\t\r\n\t\t') T(DATA|'math ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\t\t\t') T(DATA|'algebra') T(SEPARATOR|',\r\n\t\t\t') T(DATA|'geometry') T(TERMINATOR|';') T(TERMINATOR|';') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 179 characters, into 31 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor06.F_production_in_production7.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"macronutrients","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"water","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"salt","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"title":{"tilde":null,"text":{"leafType":"Text","text":"fiber","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n        "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"what","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n        "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"not","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":"\r\n\t\r\n\t"}}]},"punctuation":null},{"body":{"title":{"tilde":null,"text":{"leafType":"Text","text":"science","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t\t\t\r\n\t\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"informathics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"medicine","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t\t\r\n\t\t"}},{"body":{"title":{"tilde":null,"text":{"leafType":"Text","text":"math","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\t\t\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"algebra","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n\t\t\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"geometry","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}