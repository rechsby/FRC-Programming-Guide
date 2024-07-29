# Arrays
An array is a list of variables. Essentially, it is a list of values. each value in an array has an **index**, which is a number that represents the location of the value within the array.

Consider the following example:
```java
int[] x = new int[] {2, 4, 6, 8, 10, 12};
```
This stores the numbers 2, 4, 6, 8, and 10 in the array `x`. The `int` at the beginning
tells the computer the data type of x, similar to normal variables. The `[]` tells the computer that x is an array, not a single value. 
`new int[]` tells the computer to create a new array of type `int`. Then inside the curley brackets we can put our values seperated by commas.


> **Arrays can only be of one type**, so you can't store both Strings and Integers in one array, etc.


## Retrieving Values From An Array

Here's an example of retrieving a specific value from the array above:
```java
int a = x[0]; // 2
int b = x[1]; // 4
int c = x[2]; // 6
int d = x[3]; // 8
int e = x[4]; // 10
```

The indices of an array **start at 0** and increment from left to right. Here is a model of the index-value pairs inside the array.

| Index| Value |
| ---  | ---   |
| 0 | 2        |
| 1 | 4        |
| 2 | 6        |
| 3 | 8        |
| 4 | 10       |


## Setting Array Values
>**An Arrays length cannot be changed**, however we can change the value of specific indices

assuming the array:
```java
double[] x = new double[] {-1.32, 5.65, 3};
```
We can change the values by doing almost the reverse of how we retrieved a value from an array
```java
double[] x = new double[] {-1.32, 5.65, 3};
x[0] = 3.14;
x[1] = 1.59;
x[2] = 2.65;
```

## Retrieving The Length Of An Array
Retrieving the length of an array can be done by using the `.length` modifier. 

Consider the following example:

```java
String[] message = new String[] {"hi,", "welcome", "to", "555!"};

int x = message.length; // 4
```



## More Resources

[W3Schools](https://www.w3schools.com/java/java_arrays.asp)\
[StackOverflow](https://stackoverflow.com/questions/5570882/how-to-use-java-util-arrays)\
[Programiz](https://www.programiz.com/java-programming/arrays)