# Arrays
An array is a list of variables. Essentially, it is a list of values. each value in an array has an **index**, which is a number that represents the location of the value within the array.

Consider the following example:
```java
int[] x = new int[] {2, 4, 6, 8, 10, 12};
```
This stores the numbers 2, 4, 6, 8, and 10 in the array `x`. The `int` at the beginning
tells the computer the data type of x, similar to normal variables. The `[]` tells the computer that x is an array, not a single value. 
> **Arrays can only be of one type**, so you can't store both Strings and Integers in one array, etc.


Here's an example of retrieving a specific value from the array above:
```java
int a = x[0]; // 2
int b = x[1]; // 4
int c = x[2]; // 6
int d = x[3]; // 8
int e = x[4]; // 10
```

The indices of an array start at 0 and increment from left to right. Here is a model of 

| Index| Value |
| ---  | ---   |
| 0 | 2        |
| 1 | 4        |
| 2 | 6        |
| 3 | 8        |
| 4 | 10       |

