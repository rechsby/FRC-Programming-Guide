# Classes

A class is Java's fundamental unit of storing code. Everything you write in Java will be inside of some kind of class, or similar structure. 

Essentially, a class in java is used to represent **something**, similarly to how an ```int``` represents a number and a ```String``` represents a string of text. A class may be used to represent an animal, a game piece, or even a robot.

You've probably seen this line at least once, at the top of your main file:

```java
public class Main {
```
Don't worry about what public means for now, but if you're interested it's explained later.

This statement defines a class called Main.

> Class names must be unique within a package (folder), and are typically capitalized.

A class can contain three things: instance variables, methods, and special methods called construtors.

## Instance Variables ##

Instance variables are variables that are declared within a class, but outside of any methods or functions. 

You may or may not have learned the difference between a variable declaration and a variable initialization. 

Declaration is when you tell Java to create a variable, but do not give it a value:

```java
int x;
```
Initialization is when you assign the variable a value. You should not use the variable before this time.

```java
x = 10;
```

Instance variables are variables that are declared at the top of a class, right after the class declaration.

```java
public class Animal {
    private String name;
    private int age;
    private Animal child;
    
    ...
}
```

Instance variables will be initialized later, in the constructor, which will be explained later.

## Methods ##

Methods are the name given to functions in Java.

Any method within a class can access the instance variables of that class.

We'll cover more about methods later.

## Constructors ##

The Constructor of a class is what is used to create an instance of a class.

> If you don't know what an instance is, don't worry about it. It will be explained in the next section.

Constructors are written like this, and are called when an instance of a class is created.

They have no return type, and instead of a name, they use the name of the class.

```java
public Animal(int a, String n) {
    //initialize instance variables
    age = a;
    name = n;
}
```

You can have multiple constructors with the same name in a class, as long as they have different signatures (the headers are different), because of method overloading.

This is often used when sometimes you would like some instance variables to contain certain default values.

>If you don't need a constructor to do anything, you don't have to write one. All classes in java have an implicit, or implyed, constructor with no arguments which does nothing.










