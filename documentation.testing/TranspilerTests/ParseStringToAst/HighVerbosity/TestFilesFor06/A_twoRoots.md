========================================
Source Code (between the arrows)
========================================

🡆macronutrients ->

    fiber,
    water;

micronutrients ->

    vitamins (ABCDEK),
    minerals (micronutrients);🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Basics - v0.6
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_twoRoots.ds"
Preprocessed source code - 114 characters long

Parsing sequence: T(DATA|'macronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'fiber') T(SEPARATOR|',\n    ') T(DATA|'water') T(TERMINATOR|';\n\n') T(DATA|'micronutrients ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n    ') T(DATA|'vitamins (ABCDEK)') T(SEPARATOR|',\n    ') T(DATA|'minerals (micronutrients)') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 114 characters, into 15 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor06.A_twoRoots.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"macronutrients","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\n\n    "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"fiber","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"water","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":"\n\n"}}]},{"title":{"tilde":null,"text":{"leafType":"Text","text":"micronutrients","leadingTrivia":"","trailingTrivia":" "},"tag":null,"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\n\n    "},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"vitamins (ABCDEK)","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"minerals (micronutrients)","leadingTrivia":"","trailingTrivia":""},"tag":null,"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}