# What Is A Variable?
A *variable* stores some kind of information. The information stored can be retrieved at
any time. You can store text, numbers or even true or false in a variable. For example:
```java
int x = 2;
```
This stores the number 2 in a variable called x. The `int` at the beginning just tells the
computer that the value you are assigning to the variable x is an integer (whole-number). The semicolon at the end is needed as creating (also known as *instantiating*) a variable is a statement.


## Data Types

Every variable has a data type. This data type tells the computer what it's storing. Without the data type, the computer has no idea if the value assigned to the variable is a number, text, or something else. For example:
```java
int x = 2;
```
The computer needs the int at the beginning of the line to understand that the value
assigned to x in an integer. All variables are given data types in this way. You just put the data
type before the name of the variable. 

To start, we are going to deal with 4 different data types:

* Strings
* Integers
* Doubles
* Booleans


### Strings
Strings are used to store text. You can use a string to store your name, job, favorite color, etc. When you define a string, you need to make sure to put quotation marks around it. Notice how ```String``` is capitalized, while the other data types are not.
```java
String myName = "Bob Ross";
```

### Integers
An integer is any whole-number. 0, 1, -2, 7, 456, and 8 are all integers, while 7.8, -12.5,
and 32.6 are not. In Java integers can be positive or negative, they just have to be whole
numbers. An integer is defined like this:
```java
int secret = 42;
```
### Doubles
Doubles are numbers, but they are more useful than integers. A double can be thought of as an integer that also supports decimal values. 0, 1, -2, and 7 are still acceptable values, but so are -3.1, 71.6 and 0.21. A double is defined like this:
```java
double finalGrade = -0.32
```

### Booleans
A boolean is a value that is either true or false. It can only be true or false,
nothing else. A boolean are defined like this:
```java
bool isHungry = true
```

## More Resources
[W3Schools](https://www.w3schools.com/java/java_data_types.asp)
[Tutorialspoint](https://www.tutorialspoint.com/java/java_variable_types.htm)
[Programiz](https://www.programiz.com/java-programming/variables-literals)