# Lesson 4
## Variable conversion and types

Every value in Python has a type.

The main types you have seen so far are string, integer, float and boolean.

---

### Checking a type
You can use the type() function to check the type of a value.

#### Example:

    age = 16
    print(type(age))

will display:

    >>> <class 'int'>

---

### Type casting
Type casting means changing a value from one type into another type.

- int() changes a value into an integer
- float() changes a value into a float
- str() changes a value into a string
- bool() changes a value into a boolean

#### Example:

    age = input("Enter your age: ")
    age = int(age)
    print(age + 1)

If the user types 16, it will display:

    >>> 17

---

### Strings and numbers
The string "2" and the integer 2 are different.

#### Example:

    print("2" + "2")
    print(2 + 2)

will display:

    >>> 22
    >>> 4

## Try it yourself

- Ask the user for two numbers and add them together
- Print the type of a value before and after casting it
- Try to cast "hello" into an integer. What happens?
- Try to cast 5.9 into an integer. What happens?

