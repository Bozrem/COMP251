## Foundations of C
C uses a **single compiler**, meaning it only runs through once. It follows down the program, so functions must be declared before used

### Example Overview
foo.c
```
// comments and includes at the top
#include<stdio.h>

// prototypes
int foo(void);

// function declaration
int foo(void){
	return 1;
} // Needs to be declared before usage

int main(){
	if (foo() == 1){
		printf("test complete");
	}

	return 0; // Always has to end with a return
}
```
The program above works and prints "test complete"

### Important Elements
#### Include
Lines at the top often contain \#include<>, which includes any other libraries that need to be used
#### Define
If you want to define any global variables, you can do so with \#define VARNAME value at the top
#### Prototypes
To avoid any errors of not having functions declared yet, we often start the program with Prototype versions of the functions we will use
#### Clang
Clang is a compiler. We can call it from the command line with "clang file.c" to create an executable named a.out. 
If we want a specific name we can do "clang file.c -o desiredName"

## Questions
1. Does a prototype prevent us from getting an error if we call the function before its declared? Wouldn't it still error out due to not having a return statement?
