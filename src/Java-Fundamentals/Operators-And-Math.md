# Operators
Operators represent basic mathematical operations. Addition, subtraction, division, multiplication, and one other we'll get to later. Java follows PEMDAS (Parentheses, Exponents, Multiplication & Division, Addition & Subtraction)

Consider the following example:
```java
double x = 6.0;
double y = 2.1;
double z = -1.5;
double three = (6 + 1) - 5; // 3
double xy = x * y; // 12.6
double b = y / z; // -1.4
```


## Accidental Data Casting
It's important to be mindful of what data types you're working with when using the division operator. Consider the following:
```java
int x = 3
int y = 4
double z = y / x // 4/3 = 1.33~?
```
While the expected value of `z` is 1.33~, this is not the case. `z` a ends up having a value of 1. This is because since **both** `x` and `y` are of type `int`, it rounds to the nearest integer. To avoid this, make sure that at least one of the types you are dividing by is of type `double`