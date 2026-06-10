# Lesson 20
## Recursion

Recursion is when a function calls itself.

It is useful for problems that can be broken into smaller versions of the same problem.

---

### Example:

    def countdown(number):
        print(number)

        if number > 1:
            countdown(number - 1)

    countdown(5)

will display:

    >>> 5
    >>> 4
    >>> 3
    >>> 2
    >>> 1

---

### Base case
A recursive function needs a base case.

The base case is the condition that stops the recursion.

Without a base case, the function will call itself forever.

---

### Factorial example
Factorial means multiplying a number by every whole number below it.

#### Example:

    def factorial(number):
        if number == 1:
            return 1
        else:
            return number * factorial(number - 1)

    print(factorial(5))

will display:

    >>> 120

## Try it yourself

- Make a recursive function that counts down from 10
- Change the countdown so it stops at 0
- Find the base case in the factorial example
- Try removing the base case. What happens?

