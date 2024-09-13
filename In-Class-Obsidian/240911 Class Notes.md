## Fundamentals of C
1. Top Comments
2. Includes
3. Definitions
4. Prototypes
5. Functions
6. Main

### Types
* int
* double
* float
* char
* NO STRINGS (need char array)
* NO BOOLEAN 

You can CREATE a type with something like 
`typedef int myint;
Then something like 
`myint x = 5;`
But that isn't very useful. 

Instead, we can create a Struct, which stores multiple types inside. It does not support direct member methods, but it can be an easy way to group data

```
struct point{
	int x;
	int y;
}
```

### Variable
Have a:
* Value 
* Size
* Location in memory 
* Type
* Name
* Scope

### Printing
printf("Hey %d, today is %s", 5, "awesome");

%d -> int
%s -> char[]
%f -> float
%c -> char
%u -> unsigned int