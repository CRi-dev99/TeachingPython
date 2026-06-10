# Lesson 14
## Ternary expressions

A ternary expression is a short way to write a simple if else statement.

---

### Normal if else

#### Example:

    age = 18

    if age >= 18:
        message = "Adult"
    else:
        message = "Not adult"

    print(message)

will display:

    >>> Adult

---

### Ternary expression
The same code can be written in one line.

#### Example:

    age = 18
    message = "Adult" if age >= 18 else "Not adult"

    print(message)

will display:

    >>> Adult

## Try it yourself

- Make a ternary expression that checks if a number is even or odd
- Make a ternary expression that checks if someone passed or failed a test
- Rewrite a normal if else statement as a ternary expression
- Decide when a ternary expression is harder to read than a normal if else

