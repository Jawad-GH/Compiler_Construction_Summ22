   ** CC-Phase 1: **

Language Selected:
We have selected Mini-C language that has a syntax similar to C.
Or in other words you can say it’s a subset of C language.

Language Specification:
Mini-C is straightforward language like C-language intended to be used for programming purposes. It very well may be utilized in institute/colleges worldwide to find and learn about programming exectuion of this mini language. Mini-C is simple and easy to use. This language can be further explained and understandable in below codes and examples in depth.

It consists of:

“if-statement”
Example of If Statement:
int num1 = 20;
int num2= 10;
int temp;
if(num1 > num2)
{ temp = num1 + num2;
print(toString(temp)); //30
}

“loop”
(while loop)
Example of loop:
int number = 1;
while(number <= 10){
printIn(toString(number));
number++;
}

Also, it consists of:
“variables,parameters”
“arithematic operations(%,*,+,-)”
“comparisions(>,<,=<=,>=,==,!=)”
“logical operations(&&,||,!)”
“concatenations b/w Strings ("a" + "b")”

It doesn’t include:
“Structures”
“Arrays”
“Files”
“Unions”
“Switch Statements”
“Do Statements”

Our selected mini language is not a exact replica of what is specified in the document as there are some changes we did due to a couple of reasons. One being that some specifications and samples were not of C language. Other reason is that some additional specification were implementable which we did.


If we talk about Data types, We have added support for some datatypes such as:
“int”
”string”
”bool”
”double”
“float”
"long"
"short"
"long long"
"signed"
"unsigned"

Few Examples of Above Datatypes are given below to understand how they works:
string hitMan = "Hello Mini-C";
println(hitMan); //Hello Mini-C

double omniMan = 20.8;
double oneMan = 20.8;
println(omniMan+oneMan); //41.7

Reference: http://compilersatkiet.22web.org/lang(2).pdf?i=1
