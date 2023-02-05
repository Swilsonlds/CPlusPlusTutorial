# Loops 
a loop is a block of code that will continue to execute until the exit condition is met.

## `while` loop
A while loop is a block of code that will continue to execute until the condition stated in the `while` statement is false. Below is an example...
```C++

int myInt = 0;

while (myInt < 5){
    cout << "The number is still smaller than 5";
    myInt++;
}
```
The code within the while block above will execute exactly 5 times, and then proceed to the next line of the code after the while block.
<br> <br>
## `do while` loop
A `do while` loop is similar to the standard `while` loop except it will execute the code within the `do while` block once before checking to see if the exit condition is met. Here is what a `do while` block looks like...
```C++
int myInt = 6;

do {
    cout << "Your number is smaller than 5";
}
while(myInt < 5)
```
The code block will only be run once because after running the code block the first time, the program will see that the exit conditions have been met and exit the loop.
<br><br>

## `for` loop
A `for` loop is used when you want a block of code to be executed a specific number of times. There are three statements that must be included in the parentheses after the `for` keyword. Each of these statements will be separated by a semicolon. The purpose of each statement will be described below...

1. First statement: Used to initialize the loop control variable
2. Second statement: The loops exit condition.
3. Third statement: Code that is executed at the end of each loop iteration (often used to increment the loop control variable)

Here is an example...
```C++
for (int i = 0; i < 5; i++) {
    cout << "This will print 5 times";
}
```
<br>

## `for` each loop
`for` each loops are used to iterate through each element of a container data structure. For the example below, we will be using a `vector`. 
### `vector`
A `vector` is similar to `arrays` in other languages, except that the length of a `vector` will grow dynamically as more elements are added to it. Each vector can only contain elements that are all the same data type. You can create a `vector` using the following code...
```C++
vector<int> myVector{ 1, 2, 3, 4, 5};
```
Now, if we wanted to print out each element of the vector above using a `for` each loop, we would use the following code...
```C++
for(int x: myVector) {
    cout << x;
}
```
---
- [Functions](./functions.md)
- [Welcome Page](./welcome.md)
