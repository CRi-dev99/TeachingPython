# Lesson 17
## Static typing

Python is dynamically typed.

This means you usually do not have to write the type of a variable.

Static typing uses type hints to show what type a value should be.

---

### Variable type hints

#### Example:

    name: str = "Paddy"
    age: int = 16
    height: float = 1.75
    is_student: bool = True

Type hints do not change how the program runs, but they make the code easier to understand.

---

### Function type hints

#### Example:

    def add(number1: int, number2: int) -> int:
        return number1 + number2

    print(add(3, 4))

will display:

    >>> 7

---

### Important
Python will still run this:

    age: int = "sixteen"

The type hint is a helpful note, not a strict rule by itself.

## Try it yourself

- Add type hints to variables for your name, age and favourite subject
- Add type hints to a function that multiplies two numbers
- Try putting the wrong type into a hinted variable
- Explain why type hints can help another programmer

