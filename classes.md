# Classes
A class can be thought of as a blueprint for an object. A class will usually contain a series of attributes and methods. Attributes are variables that belong to a particular class, and methods are functions that belong to a particular class. In order to better illustrate the concept of classes, we will create a class to represent an animal in the real world. We begin creating a class by using the keyword `class`, after which we type out the name of our class, and a pair of curly braces. See example below...
```C++
class Animal{
}
```
Within the braces, the first thing we will add is our classes access specifier. This will determine at how and when the members of the class can be accessed. There are three different access specifiers...
1. Public: All members are accessible outside of the class
2. Protected: Members of the class cannot be accessed outside of the class, but may be inherited by other classes
3. Private: Member cannot be accessed outside of the class. No exceptions.

We add an access specifier by simply typing out one of the three options above and typing a colon afterward.
```C++
class Animal{
    public:
}
```
We can now add attributes and methods to our class. These are both implemented in the same manner that variables and functions are, the only exception being that these will be defined within a particular class, and can only be accessed by instances of our class. I'll add a handful of attributes and methods to our animal class in the example below...
```C++
class Animal{
    public:

    // Class attributes
    string name;
    int numberOfLegs;
    bool hasTail;
    string animalNoise;

    // Class methods
    void makeNoise(){
        cout << animalNoise << "!\n";
    }
    void printAttributes(){
        cout << name << "\n" << numberOfLegs << "/n" << hasTail;
    }
}
```
Our class is mostly done! As mentioned above, a class is really just a blueprint. If we want to create an Animal object, we would use the following line of code...
```C++
Animal myAnimal;
```
Now that we've instantiated our Animal class we can assign values to its attributes. This can be done using the syntax below...
```C++
myAnimal.name = "Dog";
myAnimal.numberOfLegs = 4;
myAnimal.hasTail = true;
```
Though there is nothing wrong with assigning values to an objects attributes as we did above, we can do this much quicker by using something called a constructor method. A constructor method allows us to assign our objects attribute values in the same line where we declared our object. In order to use this constructor method, we must first define it. We do this in the same location where we defined the other methods that belong to our class. The constructor method must share the same name as the class to which it belongs. See example below...
```C++
class Animal{
    public:

    // Class attributes
    string name;
    int numberOfLegs;
    bool hasTail;
    string animalNoise;

    // Class methods
    void makeNoise(){
        cout << animalNoise << "!\n";
    }
    void printAttributes(){
        cout << name << "\n" << numberOfLegs << "/n" << hasTail;
    }

    // Constructor method
    Animal(string nameInput, int numberOfLegsInput, bool hasTailInput, string animalNoiseInput){
        name = nameInput;
        numberOfLegs = numberOfLegsInput;
        hasTail = hasTailInput;
        animalNoise = animalNoiseInput;
    }
}
```
Now that we have a constructor method, we can easily assign values to an instance of our Animal class in the same line where we declare said instance of the class...
```C++
Animal myAnimal("Cat", 4, true, "meow");
```
We can access the attributes and methods that belong to our class by typing out the name of an instance of our class, then a period, and then the name of the attribute or method we would like to access.
## Inheritance
Inheritance is a concept of object oriented programming that allows us to create a class that "inherits" some of its attributes and methods from an existing class.

Lets create a class that inherits from our Animal class we created earlier.
```C++
class Dog: public Animal; {
  public:
    string dogBreed;
};
```
The class created in the example above will inherit all of the attributes and methods declared in the Animal class in addition to the "dogBreed" attribute that we declared in the "Dog" class.

---
[Welcome Page](./welcome.md)
