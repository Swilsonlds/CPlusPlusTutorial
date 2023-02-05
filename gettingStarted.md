# Getting Started
## Creating the File
Create a file with a name of your choice, ending with the extension suffix ".cpp". It should look something like this...
```c++
myProgram.cpp
```

## Header Files
Before we start writing our C++ program, we must first import the `iostream` 
class. This class allows the program to output to the terminal, and receive input 
from the user in the terminal. You can import the `iostream` class by including the 
following code at the top of your program.
``` c++
#include <iostream>
```
We will also want to add the following line of code to the top of the program.
```c++
using namespace std;
```
This statement allows us to use all of the content found within the C++ standard libraries within our program. Including this statement is thought to be bad practice as it can lead to naming collisions between user defined elements of the program and elements that are included in the standard libraries.
<br><br>
Since the programs contained within this tutorial will be fairly short and simple, it in unlikely that we will encounter any such naming collisions.

## Main Function
The main function is the starting point of our program. We write the main function as follows...
```c++
int main(){
    // Code to be executed goes here
    return 0
}
```
Though it is not necessary, it is good practice to have the main function return a 0. When a 0 is returned, it indicates that the function was executed successfully. If a 1 is returned instead, an error occurred somewhere in the program.

## Putting it all Together
After performing all of the steps above, our program should look like this...
```C++
#include <iostream>
using namespace std;

int main(){
    // Code to be executed goes here
    return 0;
}
```
---

- [Variables](./variables.md)
- [Home](./welcome.md)