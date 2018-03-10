# Creating a parser in Yacc

## What is asked:

In this assignment you are given a parser (written in Lex and Yacc) for an incomplete grammar of the sLisp  (the language we created a lexer for in an earlier assignment).

In the Lab web page you will find three files:
* `lexer.l`: an incomplete (but working) lex/flex specification of a lexer for sLisp
* `parser.y`: an incomplete yacc/bison specification of a parser for sLisp
* `Makefile`: do not change this file.
* `README.md`: a text file with instructions on how to compile the parser

When you compile the above files you will notice a message regarding *shift/reduce* conflicts and some warning messages.  The conflicts are indicate that your grammar is ambiguous. The warning messages may ignore them.

You are asked to
* Create a 'README.md' file that includes  the title of the assignment, your full name,  student ID, a statement attesting that this is your own work, and instructions on how to compile the parser. Below is an example of a `README.md` file
> # LAB06
> John doe
> This is my own work.
>
> To compile the parser...
* improve the provided `lexer.l` code as appropriate. You must use this starter code. You are not allowed to create your own new lex code.
* remove the ambiguity from the grammar
* introduce grammar rules to accommodate the following new constructs:
  * boolean constants are atoms
  * an `sexpr` can also be a `vector`. Example of a vector `#(4 3 a #( 1 a) (b c) *s* lol)`. Notice each element in the vector is an `sexpr`


## What to submit:

**Nota Bene**: Before submitting your solution, make sure your parser compiles with the *provided Makefile*.

Create an archive (.zip) file named yourName.zip (where `yourName` represents your actual name) containing the following files:
* your `README.md` file
* the provided Makefile
* your Yacc file
* your Lex file

Visit the assignment web page to submit a copy of your archive .zip file.

** EMAIL SUBMISSIONS WILL NOT BE ACCEPTED**
