# Functions
A function is a block of code that can be executed multiple times. It is advantageous to create a function if you plan on performing a particular calculation or procedure many times within your program. Before we are able to use or "call" our function, we must first write or "define" it.

To define a function, we first write a keyword that denotes what the data type of the functions return value will be, such as `int`, `string`, `bool`, etc. If the function will not return a value, we will use the keyword `void`.

After defining the return type, we write down the name of our function. Immediately following the name of our function we will add a pair of parentheses. Within these parentheses we will write our functions parameters. These parameters represent values that must be passed in by the user upon calling the function in order for the function to properly execute. 

After these parentheses we insert a pair of curly braces. The code that will be executed each time the function is called will be placed between these braces. Below is an example of a simple function.

```C++
int addNumbers(int x, int y) {
    return x + y;
}
```
---
- [Classes](./classes.md)
- [Welcome Page](./welcome.md)
