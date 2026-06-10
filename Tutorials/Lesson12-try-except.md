# Lesson 12
## Try except

Try except is used to handle errors.

It stops your program from crashing when something goes wrong.

---

### Example:

    number = input("Enter a number: ")

    try:
        number = int(number)
        print(number + 10)
    except:
        print("That was not a number")

If the user types 5, it will display:

    >>> 15

If the user types hello, it will display:

    >>> That was not a number

---

### Why use it?
User input can be unpredictable.

Try except lets your program react to bad input instead of stopping.

## Try it yourself

- Ask the user for their age and use try except when converting it to an integer
- Make a calculator that handles bad number input
- Try dividing by zero inside a try block
- Change the except message to something clearer

