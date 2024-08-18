# Objects

An object is an instance of a class. 

While this may seem confusing, you can think of it like this:

You have a class called ```Animal```, which can store the name, weight, and species of a given animal. You might create an *instance* of the class ```Animal``` to represent your dog, Fido. 

### User-Defined Data Types

To declare a variable with a class as its type, use the same syntax that is used with primative types:

```java
type name;
```

Using the example of the ```Animal``` class,

```java
Animal fido;
```
>Even though class names are capitalized, variable names are still typically lowercase or camelCase.

### The ```new``` Operator

The ```new``` operator is used to create an instance of, or instantiate, a class.

This is how you would create an instance of class ```Animal``` using the constructor created in the previous lesson:

>To use a specific constructor, pass in arguments corresponding to the parameters of the desired constructor.

```java
new Animal(5, "Fido");
```

This creates an instance of the class ```Animal```, but does not do anything with it. You can assign an instance to a variable like this:

```java
fido = new Animal(5, "Fido");
```

### Objects and Methods

There are two types of methods in a class: static and non-static methods (regular methods).

Static methods use a new keyword, the ```static``` keyword. You may have noticed its inclusion in the method header for the ```main``` method. 

You declare a static method like this:

```java
static type name() {}
```

>Instance variables can also be static, and are declared like this ```private static int num;```.

The main difference between static and non-static methods is that static methods are associated with the class, and non-static methods are associated with the instance.

That means that static methods can only access information that is *not* associated with a particular instance. That means that they can't access non-static instance variables.

To access a static variable, you need to use the class name, and the dot operator:

```java
Test.method();
```

As you can see, the dot operator is used to access a field (instance/class variable), or to perform a method call on a class or object. //TODO CHECK

One possible use of a static method is to count the number of created instances of a class like this:

```java
public class Test {

    private static int count = 0;

    public Test() {
        count++; //same as count +=1;
    }

    private static void resetCount() {
        count = 0;
    }
}
```
Each time an instance of ```Test``` is created, the constructor is called and the variable ```count``` is increased by one.

To call the static method ```resetCount()```, 
