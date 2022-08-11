%{
 #include<stdio.h>
%}

%%
[\n] {printf("\n\nEnter mobile Number: ");}

[+][0-9]{6,14} {printf("Phone Number accepted");}


.* {printf("Phone number Invalid.");}
%%

int main()
{
 printf("\nEnter Phone Number: ");
 yylex();
 return 0;
}
int yywrap(){return(1);}
