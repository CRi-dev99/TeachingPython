# Lesson 9
## While loops

A while loop repeats code while a condition is true.

---

### Example:

    counter = 1

    while counter <= 5:
        print(counter)
        counter = counter + 1

will display:

    >>> 1
    >>> 2
    >>> 3
    >>> 4
    >>> 5

---

### Infinite loops
If the condition never becomes false, the loop will keep going.

#### Example:

    counter = 1

    while counter <= 5:
        print(counter)

This loop does not change counter, so it will not stop by itself.

## Try it yourself

- Print the numbers from 1 to 10 using a while loop
- Ask the user to enter a password until they enter the correct one
- Make a countdown from 5 to 1
- Try making an infinite loop, then stop the program

