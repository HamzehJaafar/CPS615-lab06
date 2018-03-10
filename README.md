To clean up files type at the command line:

> make clean

To create the parser (executable file called 'parser') type:

> make parser

To test the parser on a test sLisp program file, say `test.lsp`,  type:

> ./parser < test.lsp

Nota Bene: if your test program has a syntax error, then the parser will output the message *syntax error* when you execute the above command. If the parser does not output that message, then your sLisp program is syntactically correct.
