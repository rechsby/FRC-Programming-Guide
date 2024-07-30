# Functions

Functions are repeatable, modular blocks of code used to accomplish specific tasks. We can define our own methods that will optionally take input(s), do something with it, and optionally *return* an output.

To better explain how to read & write functions, lets look at the following example:

```java
int addTheseNumbers(int a, int b) {
    return (a+b);
}

System.out.println(addTheseNumbers(1, 8));

```

There's a lot of information to dissect in the above example but for now let's look at the first line:

- `int addTheseNumbers(int a, int b) { [...] }`

This is known as the **function declaration** and it tells the compiler the name of the function alongside its inputs and outputs.

- `int`
  - A function declaration starts with a [data type](./) that specifies what type of value the function will return back to us.
- `addTheseNumbers`
  - This is the name of the function, which we'll use to refer to it in our code.
- `(int a, int b)`
  - This part of the line is very important, and where a lot of beginners get confused.

> If the beginning of a function declaration has to be a data type, then how can we have a function that returns nothing? Good question. If we want to specify that the function returns *no* data, then we use the keyword `void` *instead* of a data type such as `int` or `boolean`

