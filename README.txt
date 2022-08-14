Name: Ronney Sanchez
Date: 4/11/19
Course: COMP3010 Organization of Programming Languages
Assignment 3
Email: Ronney_Sanchez@student.uml.edu
Partner: David Bacon (other class section), Patrick Fuller (other class section)
Source: https://github.com/chichunchen/cal-translator-and-interpreter/blob/master/translator.ml

In my assignment, I got my translator done and working properly. I finally got
done with part 2 which is the C code translation. It does the translation
correctly but it prints with no newline. Instead of the code going into a 
newline, it prints a newline indicator ("\n"). The printing gets done all in 
one line. I think that that has to do with the ocaml interpreter. So far I got my abstract syntax tree to work correctly with the right grammar and tie that 
AST tree with the translation function to C code. I'm so happy that it finally 
works. I finally got both parts done to this assignment.

For part 2 I used a source to help me with the translation to C code. It was
a git hub account.
https://github.com/chichunchen/cal-translator-and-interpreter/blob/mast
er/translator.ml

To run the program, you need to us an interpreter. You must type "ocaml" on the
command line and it brings up an ocaml interpreter. Then you type 
"#use "translator.ml";;" to run the code from that file and it prints the 
syntax tree. Then you type "ast_ize_P(parse ecg_parse_table primes_prog);;" to 
print out the AST tree that will be use to generate C code. Finally, you then
type "translate(ast_ize_P(parse ecg_parse_table primes_prog));;" and it
generates C code from the AST.

For this assignment, I worked with David Bacon and Patrick Fuller. They both
are in the other section of the OPL course. We spent a lot of time figuring out
how to build the abstract syntax tree and C code generation.

