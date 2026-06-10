# Lesson 10
## Nested ifs

A nested if is an if statement inside another if statement.

This is useful when you only want to check something after another condition is true.

---

### Example:

    age = 18
    has_ticket = True

    if age >= 18:
        if has_ticket == True:
            print("You can enter")
        else:
            print("You need a ticket")
    else:
        print("You are too young")

will display:

    >>> You can enter

---

### Indentation
Nested ifs need careful indentation.

The spaces at the start of the line show Python which code belongs inside each if statement.

## Try it yourself

- Check if someone is old enough to drive, then check if they have a licence
- Check if a username is correct, then check if the password is correct
- Change the example so has_ticket is False
- Try changing the indentation. What happens?

