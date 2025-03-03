# Toy R Parser
This project is a parse tree generator for programs that use a toy R BNF grammar. The project
was used to test my understanding of parsing and generating a parse tree without a parser
generator. The lexical analyzer was created using JFlex.

This project was completed for my programming languages course on October 10, 2021, and I
created a compiler using JFlex and CUP in the following year for my compilation methods
course. The output is parse tree generator for programs that use a toy R BNF grammar created
by the instructor.

## Structure
This parser was created using JFlex as a lexical analyzer. Then I parse using the BNF grammar
defined by the professor.

The parser then generates a parse tree in prefix notation.

The goal was to eventually create a Mirco R interpreter by converting the parse tree to Lisp.
