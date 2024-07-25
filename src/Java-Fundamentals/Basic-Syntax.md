# Basic Java Syntax
Welcome! Work your way through this documentation chronologically and skip over any parts you already feel comfortable with. More resources explaining specific topics in depth can be found at the bottom of the page.


## Introduction
We'll be using this code to explain the next few topics:
```java
class Program {
    public static void main(String[] args) {
        // This is where the program starts
        System.out.println("Hello, world!");
    }
}
```
Let's start at ```System.out.println("Hello, world!");```. This is a *function* (More on these later!) that prints a string to the screen. Strings will be covered in more detail later, right now you just need to know that text is stored in quotation marks

### For Example:
```java
"hello!"
```

## Statements
A program is a set of instructions. In Java, we call each of these instructions *statements*. Each statement ends with a semicolon (;). 

In Java, statements are executed sequentially. In the above code, ```System.out.println("Hello, world!");``` is a statement.

## Comments
One part of the above program that is ignored by the computer are comments. Comments are not processed as an instruction and are used to give details about our code.

There are 2 types of comments:

* Single-Line Comments
  ```java
    // This is a single-line comment! It begins with 2 slashes.
  ```
  
* Multi-Line Comments
  ```java
    /* This is a multi-line comment, 
        it starts with a /* and ends
        with */ 
  ```

Comments will be used throughout to specify further context.