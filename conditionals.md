# Conditionals
Conditionals are statements that ensure that a block of code is executed only when a particular condition is met. Before getting into the details of how conditionals work in C++, it would be beneficial to know the logical and comparison operators for the language. See the tables below...
<br><br>

## Comparison Operators
| **Operator** | **Operator Name**        |
|--------------|--------------------------|
| ==           | Equals                   |
| !=           | Does not Equal           |
| >            | Greater than             |
| >=           | Greater than or equal to |
| <            | Less than                |
| <=           | Less than or equal to    |

<br>

## Logical Operators
| **Operator** | **Operator Name** |
|--------------|-------------------|
| &&           | And               |
| \|\|         | Or                |
| !            | Not               |
<br>
## `if` Statement
As stated above, an if statement will execute a block of code only if a particular condition is met. We write an `if` statement using the following structure...
```C++
if (Condition) {
    // Code that will be executed if condition is true
}
```
## `else if` Statement
`else if` statements are used only after `if` statement. They will execute only if the conditions of the first `if` statement are not met. We write an `else if` statement in the same way we write an `if `  statement, except we include the key word `else` before the keyword `if`...
```c++
else if (Condition) {
    // Code that will be executed if condition is true
}
```
## `else` Statement
The `else` statement is used after the `if` and `else if` statements. No conditions are outlined within the `else` statement. Instead, the code within the `else` block will be executed if none of the conditions in the `if` and `else if` statements above it are met. See example below...
```C++
if (Condition) {
    // Code that will be executed if condition is true
}

else if (Condition) {
    // Code that will be executed if the condition outlined in the original if statement is NOT met, and the condition outlined in the else if statement IS met. 
}

else {
    // Code that will be executed if neither the condition in the if statement nor the condition in the else if statement are met.
}
```
---
- [Loops](./loops.md)
- [Welcome Page](./welcome.md)