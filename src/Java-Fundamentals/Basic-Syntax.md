# Basic Java Syntax
Welcome! Work your way through this documentation chronologically and skip over any parts you already feel comfortable with. More resources explaining specific topics in depth can be found at the bottom of the page.


## Introduction
Consider the following code:
```java
class Program {
    public static void main(String[] args) {
        // This is where the program starts
        System.out.println("Hello, world!");
    }
}
```
> There's a lot of symbols and words here you may not be familiar with yet, and that's ok! we'll work through it in the next few pages.

## Statements
A program is a set of instructions. In Java, we call each of these instructions **statements**. Each statement ends with a semicolon (;). 

In Java, statements are executed sequentially. In the above code, ```System.out.println("Hello, world!");``` was a statement.

## Comments
One part of the above program that is ignored entirely by the computer are comments. Comments are ignored completely by the computer and are used to explain code or give information.

There are 2 types of comments:

* Single-Line Comments
  * ```java
    // This is a single-line comment! It begins with 2 slashes.
    ```
  
* Multi-Line Comments
  * ```java
    /* This is a multi-line comment, 
        it starts with a /* and ends
        with */ 
    ```
