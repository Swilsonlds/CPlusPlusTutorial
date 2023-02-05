# Variables
## Declaring a Variable
C++ is a statically typed language. This means that when declaring variables, we begin the expression with a keyword that lets the compiler know what type of variable we are creating. Below is a table containing a handful of some of the most commonly used data types, along with their declaration keyword and description.
<br><br>
| **Data Type** | **Key Word** | **Description**                                                                 |
|---------------|--------------|---------------------------------------------------------------------------------|
| String        | string       | A string of characters. Can consist of letters, numbers, and special characters |
| Integer       | int          | A whole number                                                                  |
| Double        | double       | A decimal number                                                                |
| Boolean       | bool     | Holds either the value "true" of "false"                                        |
| Character     | char         | A single character                                                              |
<br>

After writing the keyword that denotes the data type of our variable, we write the desired name of our variable and end the statement with a semicolon. It should look something like this...
```c++
string myString;
int myInt;
double myDouble;
bool myBool;
char myCharacter;
```
## Assignment 
After declaring a variable, we can assign a value to it by using the assignment operator "=". This can be done either in the same line as the declaration statement, or in a subsequent line. See examples below...
``` c++
string myString;
myString = "hello";
```
or
```c++
string myString = "hello";
```
NOTE: When assigning a value to a string variable, we surround the value in double quotes. When assigning a value to a character variable we surround the value with single quotes.

---
- [Printing to the Terminal and getting User Input](./printingAndUserInput.md)
- [Welcome Page](./welcome.md)

