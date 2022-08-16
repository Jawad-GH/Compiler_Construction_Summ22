Phase 2

Phase Name

Lexical Analyzer of Mini C

Lexical Analyzer
Lexical Analyzer is the first step in the Compiler. It takes Code Input ----> and give Token Stream Output.
To do this the first step a Lexical Analyzer performs is to make lexemes.
Lexemes are subsets of the code usually, lexemes are part of the code from which tokens are identified. The Lexical Analyzer then after making lexemes matches them to their respective token classes. Tokens are usually identified using Regular Expressions (reason we are using flex in this project).

What is happening
The lex file outputs tokens <tokenclass,lexeme> of the given code in C language present in code.c file.
As mentioned above to do so first have to make lexemes.
Let me explain in the simplest way as possible how our code recognises the Lexemes. To start off the explanation one thing is that we have prioritized some of the token classes over others. So if there is a word "for" the analyzer will not say it is an identifier as "for" is a reserved keyword and have a higher priority than an identifier. The other thing we do is use whitespaces to separate lexemes in the code. We have already explained a simple example of Keywords and Identifiers but it gets much more complicated than that as "for" can also be written as a string in a print statement. We will discuss more about issues like this in the next section and how and which rules are used to recognize each token class.

Features
-> List the Keywords -> How are identifiers recognized -> Comments -> Stings -> Constants

Organization of Files
File Name	Details
code.c	The code to make tokens of
lexl.l	Flex code for the Lexical Analyzer
Takeaways
-> Learning and getting a deeper knowledge about Regular Expressions
-> In depth understanding of how lexemes are created
-> Getting a concept of tokens, token class and how they are recognized
-> Understanding how IDE's give different colors to different identifiers

Sample Video
 lex.video.mp4 
How to run
Make sure Flex is installed and running
Download the flex file and store it in a folder
In the same folder create a file (code.c) of c language
Compile the Flex file using the follwing commands:
--> flex lexl.l
--> gcc lex.yy.c -lfl
--> ./a/out
The desird output of the tokens <tokenclass, lexeme> will be shown.

Pre-Requisites
--> Flex
