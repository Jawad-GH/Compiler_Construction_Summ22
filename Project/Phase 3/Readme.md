Phase 3

Phase Name
C code to Python Code Converter

** What is happening

The output of the flex is in tokens, as we are aware and have already seen in the previous phase. These tokens are taken by Yacc, who parses them using the given Grammer. In most cases, this phenomena is utilised to translate HLL (high level language) into machine language; however, in our project, it is being used to translate Mini C (details in Phase 1) into Python. Our provided CFG is translated into a C code implementation in Yacc.

** Features of project
The phase may translate small C language code to python code. It accomplishes the following by utilising grammars in Yacc and regular expressions in Flex.

** Organization of Files

The code to change the output language is contained in the code folder. contains the program's output, such as Python code.
flex code lex.
lex.yy.c Flex compilation file
yacc.y Yacc code
Takeaways -> Got a better understanding of how the compilers work -> Deeper understanding of how errors are caught in a compiler -> Understanding of grammars and parsing


** How to run

- Yacc and Flex should be installed
- Download all the files
- Navigate to the folder of the project
- Compile flex and yacc code
- Run the executable file in terminal

Pre-Requisites
--> Flex
--> Yacc
