# Hello, World!

A "Hello, World!" is a simple program that outputs Hello, World! on the screen. Since it's a very simple program, it's often used to introduce a programming language to new programmers.

Let's explore how a Java "Hello, World!" program works:

```java
public class Main { 
  public static void main(String[] args) { 
    System.out.println("Hello World!"); 
  }
}
```

Let's go through this line by line:

1. `public class Main { [...] }`
   - In Java, every file contains one main class that has the same name as the file its in. We’ll talk about [classes](../../Object-Oriented-Programming/course/Classes.md) more in the future, but for now think of them as a container for parts of our code. Code between the opening and closing curly parenthesis is considered "part" of that class.
2. `public static void main(String[] args) { [...] }`
   - This is the *main method* Every application in Java contains a main method. When we run our program, the java compiler starts running our code from here.
3. `System.out.println("hello World");`
   - This is known as a **print statement**. It prints the text "Hello, World!" to standard output (your screen). The text inside the quotation marks is called a [String](./Variables.md#) in Java. We use `System.out.println("
  ")` to print whatever is inside the double quotes to the screen.

______________________________________________________________________

> How does the *main method* work? Good question. However, we will not discuss it in this article. After all, it's a basic program to introduce the Java programming language to you! We will learn the meaning of keywords like `public`, `static`, `void`, and [how methods work](./Functions.md) in later chapters.

In Java, every application begins with a class definition. In the above program, `HelloWorld` is the name of the class, and is defined on the first line. We’ll talk about classes more in the future, but for now think of them as a container for different parts of our code.

## Comments

Comments are intended for users reading the code to understand its purpose & functionality. They are completely ignored by the Java compiler.

There are 2 ways to create comments in Java:

1. Using `//` for single-line comments
   - ```java
     // Hello! This is a single-line comment and is great for short explanantions of code.
     ```
2. Using `/* ... */` for multi-line comments
   - ```java
     /* Hi! This is a comment that spans across
       multiple lines
       great for giving deeper explanations on why or how our code works.
     ```

Code snippets throughout this guide may use comments to provide further context or explain what's going on.

