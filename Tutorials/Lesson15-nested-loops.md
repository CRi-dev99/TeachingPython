# Lesson 15
## Nested loops

A nested loop is a loop inside another loop.

The inner loop runs fully each time the outer loop runs once.

---

### Example:

    for row in range(3):
        for column in range(3):
            print("Row", row, "Column", column)

will display:

    >>> Row 0 Column 0
    >>> Row 0 Column 1
    >>> Row 0 Column 2
    >>> Row 1 Column 0
    >>> Row 1 Column 1
    >>> Row 1 Column 2
    >>> Row 2 Column 0
    >>> Row 2 Column 1
    >>> Row 2 Column 2

---

### Grid example

#### Example:

    for row in range(3):
        for column in range(3):
            print("*", end="")
        print()

will display:

    >>> ***
    >>> ***
    >>> ***

## Try it yourself

- Print a 5 by 5 square of stars
- Print a triangle of stars
- Use nested loops to print every pair of numbers from 1 to 3
- Change the size of the grid using a variable

