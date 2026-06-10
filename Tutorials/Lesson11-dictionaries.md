# Lesson 11
## Dictionaries

A dictionary stores data using keys and values.

Lists use positions. Dictionaries use names.

---

### Example:

    student = {
        "name": "Paddy",
        "age": 16,
        "year": 5
    }

    print(student["name"])

will display:

    >>> Paddy

---

### Changing a dictionary
You can add or change values using their key.

#### Example:

    student = {
        "name": "Paddy",
        "age": 16
    }

    student["age"] = 17
    student["subject"] = "Computer Science"

    print(student)

will display:

    >>> {'name': 'Paddy', 'age': 17, 'subject': 'Computer Science'}

## Try it yourself

- Make a dictionary for yourself with name, age and favourite subject
- Print one value from the dictionary
- Change one value in the dictionary
- Add a new key and value to the dictionary
- Try to print a key that does not exist. What happens?

