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

As seen in the above example, 