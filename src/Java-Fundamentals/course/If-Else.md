# Java Branching: If, Else, Elif
The statements inside your code are generally executed from top to bottom, in the order that they appear. Control flow statements, however, break up the flow of execution by employing decision making, looping, and branching, enabling your program to conditionally execute particular blocks of code. This page describes the most important decision-making statements (if, else, elif). The [essential looping statements](./Loops.md) ([for](./Loops.md#for-loops), [while](./Loops.md#while-loops)) will be covered later. t

## If Statement

The Java `if` statement is used to conditionally run code depending on if a boolean condition is true. It checks a boolean condition: `true` or `false`. There are various types of if statement in Java.

> A condition in the context of control flow statements refers to any boolean expression (previously explained [here](./Boolean-And-Equality-Operators.md)) that evaluates to either `true` or `false`. Some examples include `2 > 3`, `x == 9`, `6 % 2 == 0`, and `x == 9 && y == 3`

Consider the following structure of an if statement:
```java
if (condition) {
    // Here we put whatever code we want to run if the condition is true
}
```
> If you need a refresher on boolean expressions, refer to [here](./Boolean-And-Equality-Operators.md)

Here's an example of the decision tree when using an if statement:
\
![If Statement Decision Making Graph](../../assets/decision_making.jpg)

Here are some examples of if statements:
```java
int x = 3
if (x > 9) { // This code will not be executed since x is equal to 3 and 3 is less than 9 
    System.out.println("X is bigger than 9!");
}
```
Here's an example that includes the use of [operator shorthand](./Operators-And-Math.md#operator-shorthand) to subtract y by 2:
```java
int y = 9
y-=2
if (y < 8) { // This code will be executed because y = 9, 9 - 2 = 7 and 7 is less than 8.
    System.out.println("Y is smaller than 8!");
}
```

Here's an example using the [or operator](./Boolean-And-Equality-Operators.md#the-or-operator):
```java
int x = 1
int y = 3
if (x < 2 || y > 20) { // This code will be executed as while y is not greater than 20, x is less than 2.
    System.out.println(" :) ");
}
```

## Else

