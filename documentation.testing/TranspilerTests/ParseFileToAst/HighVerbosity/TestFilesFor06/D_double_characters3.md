========================================
Source Code (between the arrows)
========================================

🡆fa \ br\ics\ ->

    wool\fabrics,
    \cotton fabrics,
    \ silk \ fabrics,
    synthetic fabrics;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'File -> AST' operation...
------------------------
Starting a parse operation on file: "C:\Users\Viktor Chernev\Desktop\testing\TestFiles\TestFilesFor06\D_double_characters3.ds"
Fetched file contents - 105 characters long

Parsing sequence: T(DATA|'fa ') T(ESCAPE|'\ ') T(DATA|'br') T(ESCAPE|'\') T(DATA|'ics') T(ESCAPE|'\ ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\r\n\r\n    ') T(DATA|'wool') T(ESCAPE|'\') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\') T(DATA|'cotton fabrics') T(SEPARATOR|',\r\n    ') T(ESCAPE|'\ ') T(DATA|'silk ') T(ESCAPE|'\ ') T(DATA|'fabrics') T(SEPARATOR|',\r\n    ') T(DATA|'synthetic fabrics') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

File parsed successfully
Parser red 105 characters, into 23 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"C:\\Users\\Viktor Chernev\\Desktop\\testing\\TestFiles\\TestFilesFor06\\D_double_characters3.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fa \\ br\\ics\\","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\r\n\r\n    "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool\\fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"\\cotton fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"\\ silk \\ fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\r\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"synthetic fabrics","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}