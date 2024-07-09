# Parsing

Next, you'll craete a parser that takes the tokens and forms an Abstract Syntax Tree (AST).

```c
// A simple parser in C 
// Aassume `Token`is defined from the previous step

typedef struct Node{
	Token token; 
	struct Node* left; 
	struct Node* right; 
} Node; 

Node* parse(Token* tokens){
	// Implementation goes here; 
}
```


