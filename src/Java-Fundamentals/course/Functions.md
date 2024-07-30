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

* `int addTheseNumbers(int a, int b) { [...] }`
  
This is known as the **function declaration** and it tells the compiler the name of the function alongside its inputs and outputs.

* `int`
  * A function declaration starts with a [data type](./) that specifies what type of value the function will return back to us.
* `addTheseNumbers`
  * This is the name of the function, which we'll use to refer to it in our code.
* `(int a, int b)`
  * This part of the line is very important, and where a lot of beginners get confused.



> If the beginning of a function declaration has to be a data type, then how can we have a function that returns nothing? Good question. If we want to specify that the function returns *no* data, then we use the keyword `void` *instead* of a data type such as `int` or `boolean`


First, the `int` part of the line specifies what [datatype](./Variables.md#data-types) (if any) the function will return, in this case, an integer. The next part of the line specifies the name of the function which in this case is `addTheseNumbers`.


The next part of the line names the method, in this case, the method is called
addTheseNumbers. The part of the line between the brackets, where it says (int a, int b) tells
the method what inputs it takes. This method takes two integer arguments. All of this sets up
the method. The part of the method between, the parentheses ({} these symbols) tells the
computer what to do whenever the method is called. In this case, all the method will do is add
the two integer inputs. The return keyword tells the computer that the integer that this method
outputs is a+b.