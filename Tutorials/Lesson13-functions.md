# Lesson 13
## Functions

A function is a reusable block of code.

You can write the code once, then call it whenever you need it.

---

### Creating a function
You create a function using def.

#### Example:

    def say_hello():
        print("Hello")

    say_hello()

will display:

    >>> Hello

---

### Parameters
Parameters let you send values into a function.

#### Example:

    def greet(name):
        print("Hello " + name)

    greet("Paddy")

will display:

    >>> Hello Paddy

---

### Return
Return sends a value back from a function.

#### Example:

    def add(number1, number2):
        return number1 + number2

    result = add(3, 4)
    print(result)

will display:

    >>> 7

## Try it yourself

- Make a function that prints your name
- Make a function that takes a name and greets the person
- Make a function that adds two numbers and returns the answer
- Call the same function more than once

