# Operators & Arithmetic
Operators represent basic mathematical operations. Addition, subtraction, division, multiplication, and one other we'll get to later. Java follows PEMDAS (Parentheses, Exponents, Multiplication & Division, Addition & Subtraction).

Consider the following example:
```java
double x = 6.0;
double y = 2.1;
double z = -1.5;
double three = (6 + 2) - 5; // 3
double xy = x * y; // 12.6
double b = y / z; // -1.4
```

### Operator Shorthand
Java also supports shorthand for altering a value itself
```java
int x = 3
x = x * 2
```
```java
int x = 3
x *= 2
```
Both of these snippets multiply x by 2. *= multiplies a variable by the number next to the equal sign, same for `/=`, `+=`, and `-=`, for division, addition, and subtraction respectively.

## Accidental Casting
It's important to be mindful of what data types you're working with when using the division operator. Consider the following:
```java
int x = 3
int y = 4
double z = y / x // 4/3 = 1.33~?
```
While the expected value of `z` is 1.33~, this is not the case. `z` a ends up having a value of 1. This is because since **both** `x` and `y` are of type `int`, it rounds to the nearest integer. To avoid this, make sure that at least one of the types you are dividing by is of type `double`

## Modulo
>Given two positive numbers a and n, a modulo n (often abbreviated as a mod n) is the remainder of the division of a by n, where a is the dividend and n is the divisor.

The Modulo operator is used to get the remainder of any given division. It's helpful to think of it as doing integer division, then returning the remainder. It is represented by the % sign. 
```java
5 % 3 // 2
9 % 2 // 1
3 % 3 // 0
25 % 5 // 0
// Try this one yourself!
23 % 6
```

## More Resources
[CodeDamn](https://codedamn.com/news/java/what-is-modulo-modulus-remainder-operator-in-java)