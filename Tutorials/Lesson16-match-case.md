# Lesson 16
## Match case

Match case is another way to make decisions in Python.

It is useful when you are checking one value against different options.

---

### Example:

    day = "Monday"

    match day:
        case "Monday":
            print("Start of the week")
        case "Friday":
            print("Almost the weekend")
        case "Saturday" | "Sunday":
            print("Weekend")
        case _:
            print("Normal day")

will display:

    >>> Start of the week

---

### Default case
The case _ part is used when none of the other cases match.

It works like else.

## Try it yourself

- Ask the user for a day of the week and print a message
- Make a menu where the user chooses option 1, 2 or 3
- Add a default case for an invalid choice
- Rewrite a match case program using if, elif and else

