# Lesson 21
## Advanced data algorithms

An algorithm is a set of steps used to solve a problem.

Advanced data algorithms often work with lists, dictionaries and other data structures.

---

### Searching a list
Searching means finding an item in a list.

#### Example:

    names = ["Paddy", "Sarah", "John"]
    target = "Sarah"

    for name in names:
        if name == target:
            print("Found")

will display:

    >>> Found

---

### Finding the largest number

#### Example:

    numbers = [4, 9, 2, 7]
    largest = numbers[0]

    for number in numbers:
        if number > largest:
            largest = number

    print(largest)

will display:

    >>> 9

---

### Counting items
Dictionaries can be used to count how many times values appear.

#### Example:

    words = ["red", "blue", "red", "green", "blue", "red"]
    counts = {}

    for word in words:
        if word in counts:
            counts[word] = counts[word] + 1
        else:
            counts[word] = 1

    print(counts)

will display:

    >>> {'red': 3, 'blue': 2, 'green': 1}

## Try it yourself

- Search a list for a name entered by the user
- Find the smallest number in a list
- Count how many times each letter appears in a word
- Sort a list using sorted() and compare it to your own searching code

