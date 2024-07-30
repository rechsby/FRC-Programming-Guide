# Loops

Loops are frequently used in programming. Loops are handy because they save time programming and make our code easier to read and debug.

## While Loops

The while loop is the simplest loop and is used to repeat a part of the program repeatedly until the specified Boolean condition is false. As soon as the Boolean condition becomes false, the loop automatically stops.

Here is the structure of a while loop:

```java
while (condition) { // the condition that is evaluated
    // Do things here

    // Last line of the loop body is the one right before the }
}
```

First, the condition is evaluated. If the condition is true, then the loop body is executed. When the last line of the loop body is executed, the condition is *re-evaluated* (checked). This process continues until the condition is false. If the starting condition is false, the loop body is never executed and is skipped.

> If the condition never becomes false, we end up with a loop that goes on forever! (This is usually bad)

## For Loops

Another common loop is the for loop. The for is useful when you need to loop through a set number of items. Let's say we want to loop through a set of numbers to add them up.
Here is how you would do it:

```java
int number = 3;

for (int i = 0; i < 10; i++) { // <- Important line!
    number = number + i;

    // Once again, the last line of the loop body is the one right before the }
}




```

The line containing the `for` statement itself contains several statements, lets break them down:

1. ```java
    int i = 0;
   ```
   - This is run before the first iteration of the loop and sets the variable that the rest of the loop uses. This variable is usually named after a single letter such as `i` or `j`.
1. ```java
    i < 10;
   ```
   - This is a condition utilizing [equality operators](./Boolean-And-Equality-Operators.md#equality-operators). If this condition is true, the loop runs again, otherwise the program moves on. This is identical to the while loop's condition that we saw above.
1. ```java
    i++;
   ```
   - This part is run at the end of each iteration of the for loop, and in this specific example is utilizing [math shorthand](./Operators-And-Math.md#operator-shorthand) to increment `i` by 1

______________________________________________________________________

Finally you have the actual code which is run each iteration. Notice we reference the [variable](./Variables.md#variables) `i` in the code.

One detail worth noting is that the for loop and while loop can both acomplish the same tasks. It is just a clearer and more convenient way to do many tasks. Here is what the above for loop example would look like as a while loop:

```java
int number = 0;
int i = 0;
while (i < 10) { // the condition that is evaluated
    number = number + 1;

    i++; //or i = i + 1;
    // Last line of the loop body is the one right before the }
}
```

______________________________________________________________________

References:

[W3Schools While Loop](https://www.w3schools.com/java/java_while_loop.asp) \
[W3schools For Loop](https://www.w3schools.com/java/java_for_loop.asp)
