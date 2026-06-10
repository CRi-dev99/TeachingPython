# Lesson 3
## Input()

The input() function is used to take in user input.

User input is any data a user enters into a program.

---

### Input() usage
Anything inside the brackets will be displayed before the user types their answer.

    name = input("Enter your name: ")
    print(name)

If the user types Paddy, it will display:

    >>> Enter your name: Paddy
    >>> Paddy

---

### Important
The input() function always gives you a string, even if the user types a number.

#### Example:

    age = input("Enter your age: ")
    print(type(age))

If the user types 16, it will display:

    >>> str

## Try it yourself

- Ask the user for their name and print it
- Ask the user for their favourite colour and print it
- Ask the user for their age and print the type of the answer
- Try putting nothing inside the input brackets. What happens?

