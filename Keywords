%{
%}
%%
"while"|"if"|"else"|int {printf("Keyword Entered!\n");}
[a-zA-z][A-Za-z0-9]* {printf("Identifier Entered!!\n");}
.+ {printf("Illegal Sequence!!\n");}
%%
int yywrap(void){}
int main()
{
	printf("\nEnter the Word:");
	yylex();
	printf("\n");
	return 0;
}
