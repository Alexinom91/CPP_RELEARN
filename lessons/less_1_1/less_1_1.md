# How to structure a program

### Every C++ program must have a fuction named 'main' (all lower case letters).

#### To write correct and readable code, you should follow some basic rules:

- Use consistent indentation.
- Name variables and fuction clearly.
- Add comments to explain non-obvious parts.
- Keep functions short and focused.
- Avoid repeating code (use functions or loops instead).

## Dissecting Hello world!

```cpp
#include <iostream>

int main()
{
    std::cout<<"Hello world!";
    return 0;
}
```
Line 1 is a special type of line called pre processor directive. This `cpp #include` means that we want to use `cpp iostream` contents in our code, it's a standard library of C++ since 1983. `cpp iostream` allows us to read and write from/to console. We must have this line in order to use `std::cout` on line 5. 

Line 2 is blank, and it is also ingnored by the compiler. This line exist only to make the program more readable to humans.

Line 3 tells the [compiler](https://en.wikipedia.org/wiki/Compiler) that we are going to define a function called `cpp main`. As you learned above, every C++ program must have a main function or it will fail to [link](https://en.wikipedia.org/wiki/Linker_(computing)). This function will produce a value whose type `cpp int`(an integer).

Line 4 and 7 tells to the compiler which part of the code is inside of the `cpp main` function.

Line 5 is the statement of the `cpp main`, which tells to us that we are going to display the text `Hello world!` on the console, by using the function `cpp std::cout` and redirecting everything with those operators `cpp <<`. 

Line 6 return a statements that communicates to the operative system that everything in the program worked properly.


## I need to clarify

This is the documentation for the first example of my code.  
It is intended to be the most self-explanatory example.  
The rest of the code will be explained in detail in my book.