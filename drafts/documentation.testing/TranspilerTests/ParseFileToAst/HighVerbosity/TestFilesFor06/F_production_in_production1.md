========================================
Source Code (between the arrows)
========================================

🡆macronutrients ->

    fiber ->

        what,
        not;
    
    water;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor06\F_production_in_production1.ds"
Fetched file contents - 82 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'fiber ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n        ') T(DATA|'what') T(SEPARATOR|',\r\n        ') T(DATA|'not') T(TERMINATOR|';\r\n    \r\n    ') T(DATA|'water') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 82 characters, into 13 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor06\\F_production_in_production1.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"macronutrients","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n    "},"lines":[{"body":{"title":{"tilde":null,"text":{"leafType":"Text","text":"fiber","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n        "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"what","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n        "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"not","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":"\r\n    \r\n    "}}]},"punctuation":null},{"body":{"tilde":null,"text":{"leafType":"Text","text":"water","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}