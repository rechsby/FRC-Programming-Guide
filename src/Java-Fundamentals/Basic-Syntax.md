# Hello, World!

A "Hello, World!" is a simple program that outputs Hello, World! on the screen. Since it's a very simple program, it's often used to introduce a programming language to new programmers.

Let's explore how a Java "Hello, World!" program works:

```java
public class HelloWorld { 
  public static void main(String[] args) { 
    System.out.println("Hello World!"); 
  }
}
```
Let's go through this line by line:

1. `public class HelloWorld { ... }`
    * In Java, every file contains one main class that has the same name as the file its in. We’ll talk about classes more in the future, but for now think of them as **a container for parts of our code.** Code between the opening and closing curly parenthesis is considered "part" of that class.
2. `public static void main(String[] args) { ... }`
    * This is the *main method* Every application in Java contains the main method. When we run our program, the java compiler starts running our code from here.
3. `System.out.println("hello World");`
    * This is known as a print statement. It prints the text "Hello, World!" to standard output (your screen). The text inside the quotation marks is called a [String](./Variables.md#) in Java.
--- 
>How does the main method work? Good question. However, we will not discuss it in this article. After all, it's a basic program to introduce the Java programming language to you! We will learn the meaning of keywords like `public`, `static`, `void`, and how methods work in later chapters.

In Java, every application begins with a class definition. In the above program, `HelloWorld` is the name of the class, and is defined on the first line. We’ll talk about classes more in the future, but for now think of them as a container for different parts of our code.


## Comments

In Java, any line starting with `//` is a comment. Comments are intended for users reading the code to understand the intent & functionality of the program. It is completely ignored by the Java compiler.