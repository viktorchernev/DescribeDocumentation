========================================
Source Code (between the arrows)
========================================

🡆fabric     s 	<TSbLGnNG> ->

	wool   fabrics	 <QWVZ3pp9> ,
	cotton\, fabrics textiles   <75NTfebY>,
    silk\-\>fabrics <Sqs0lm7S>,
    syntic 		fabrics <GcZEI9gy>;🡄

========================================
Logged text
========================================

🡆Verbosity set to: High
Language version set to: Describe Tags - v0.7
Describe Transpiler initialized.
Starting a 'String -> AST' operation...
------------------------
Starting a parse operation on "Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds"
Preprocessed source code - 164 characters long

Parsing sequence: T(DATA|'fabric     s \t') T(TAG|'<TSbLGnNG> ') T(HYPHEN|'-') T(RIGHT_ARROW|'>\n\n\t') T(DATA|'wool   fabrics\t ') T(TAG|'<QWVZ3pp9> ') T(SEPARATOR|',\n\t') T(DATA|'cotton') T(ESCAPE_SEPARATOR|'\, ') T(DATA|'fabrics textiles   ') T(TAG|'<75NTfebY>') T(SEPARATOR|',\n    ') T(DATA|'silk') T(ESCAPE_HYPHEN|'\-') T(ESCAPE_RIGHT_ARROW|'\>') T(DATA|'fabrics ') T(TAG|'<Sqs0lm7S>') T(SEPARATOR|',\n    ') T(DATA|'syntic \t\tfabrics ') T(TAG|'<GcZEI9gy>') T(TERMINATOR|';') T(EOF|'<EOF>') Ok

Source code parsed successfully
Parse tree unfolded successfully
Done!
------------------------
Parser red 164 characters, into 22 tokens.
Those were translated to an AST.
All Files: 1, Succeeded: 1, Failed: 0, Errors: 0🡄

========================================
Produced AST
========================================

{"filename":"Tests.Integration.Transpiler.TestFiles.TestFilesFor07.E_spaces_escapes_N.ds","nspace":null,"expressions":[{"title":{"tilde":null,"text":{"leafType":"Text","text":"fabric     s","leadingTrivia":"","trailingTrivia":" \t"},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"TSbLGnNG","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"arrow":{"leafType":"ProductionArrow","text":"->","leadingTrivia":"","trailingTrivia":"\n\n\t"},"lines":[{"body":{"tilde":null,"text":{"leafType":"Text","text":"wool   fabrics","leadingTrivia":"","trailingTrivia":"\t "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"QWVZ3pp9","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":" "}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n\t"}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"cotton\\, fabrics textiles","leadingTrivia":"","trailingTrivia":"   "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"75NTfebY","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"silk\\-\\>fabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"Sqs0lm7S","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Separator","text":",","leadingTrivia":"","trailingTrivia":"\n    "}},{"body":{"tilde":null,"text":{"leafType":"Text","text":"syntic \t\tfabrics","leadingTrivia":"","trailingTrivia":" "},"tag":{"openBracket":{"leafType":"OpenTag","text":"<","leadingTrivia":"","trailingTrivia":""},"id":{"leafType":"Text","text":"GcZEI9gy","leadingTrivia":"","trailingTrivia":""},"closeBracket":{"leafType":"CloseTag","text":">","leadingTrivia":"","trailingTrivia":""}},"links":null,"decorators":null},"punctuation":{"leafType":"Terminator","text":";","leadingTrivia":"","trailingTrivia":""}}]}],"exception":null}