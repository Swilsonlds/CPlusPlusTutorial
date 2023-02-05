# Printing to the Terminal and getting User Input
## Printing
In order to print to the terminal, we will use the keyword `cout` followed by `<<`, the object we would like to print, and ending with a semicolon. If we wanted to write the classic "Hello World!" program, we would write the following...
``` C++
#include <iostream>
using namespace std;

int main(){
    cout << "Hello World!";

    return 0
}
```

## Getting User Input
In order to gather input from the user, we will use the keyword `cin`. If we wanted to save a string passed in by the user to the variable `myString` and then print it to the console, we would use the following code...
```c++
#include <iostream>
using namespace std;

int main(){
    string myString;
    cin >> myString;
    cout << myString;

    return 0
}
```
- [Conditionals](./conditionals.md)
- [Welcome Page](./welcome.md)