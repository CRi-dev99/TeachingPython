# Lesson 5
## If, elif and else statements

If statements let your program make decisions.

They run code only if a condition is true.

---

### If

#### Example:

    age = 18

    if age >= 18:
        print("You are an adult")

will display:

    >>> You are an adult

---

### Else
The else part runs when the if condition is false.

#### Example:

    age = 15

    if age >= 18:
        print("You are an adult")
    else:
        print("You are not an adult")

will display:

    >>> You are not an adult

---

### Elif
Elif means else if.

It lets you check another condition.

#### Example:

    mark = 65

    if mark >= 80:
        print("Distinction")
    elif mark >= 50:
        print("Pass")
    else:
        print("Fail")

will display:

    >>> Pass

## Try it yourself

- Ask the user for their age and check if they are old enough to drive
- Make a program that checks if a number is positive, negative or zero
- Make a program that checks if a password is correct
- Try forgetting the colon after an if statement. What happens?

