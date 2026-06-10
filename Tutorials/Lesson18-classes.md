# Lesson 18
## Classes

A class is a blueprint for creating objects.

An object can store data and have functions that belong to it.

---

### Creating a class

#### Example:

    class Student:
        def __init__(self, name, age):
            self.name = name
            self.age = age

    student1 = Student("Paddy", 16)

    print(student1.name)
    print(student1.age)

will display:

    >>> Paddy
    >>> 16

---

### Methods
A method is a function inside a class.

#### Example:

    class Student:
        def __init__(self, name):
            self.name = name

        def say_hello(self):
            print("Hello, my name is " + self.name)

    student1 = Student("Paddy")
    student1.say_hello()

will display:

    >>> Hello, my name is Paddy

## Try it yourself

- Create a class called Dog with a name and age
- Create two objects from the same class
- Add a method that prints a sentence about the object
- Try printing an attribute that does not exist. What happens?

