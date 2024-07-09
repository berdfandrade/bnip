# The building blocks of your language

## Lexical analysis (tokeninzation)

```c
// A simple lexical analyzerr in C
// Assume `source_code` is a string containg the souce code

enum {TK_IDENTIFIER, TK_NUMBER, TK_EOF}; 

typedef struct{
	int type;
	char* value; 
} Token; 

Token* tokenize(const char* source_code){
	// implementation goes here 
}
```
