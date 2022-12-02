# Ruby-Interpreter
Designing a basic interpreter for RUBY in PYTHON

## Breif Description:

This Ruby Interpreter takes the code line by line given by the user and interprets and gives the output if required.
It has three main files which have different functionalites, namely Lexer, Parser, Interpreter.

[*Lexer*](#lexer) - It takes the given Input as a String and divides it into Tokens. It has Reserved Keywords, a Token class and a Lexer class.

[*Parser*](#parser) - It sends the given String to Lexer and gets all the Tokens of the given Line and Create an Abstract Syntax tree from it.

[*Interpreter*](#interpreter) - It gets the Abtract Syntax Tree from the Parser and visit each node and evaluate it according to the semantics of Ruby and produce the required output.



# Lexer:
