# Lesson 19
## OOP

OOP means Object-Oriented Programming.

It is a way of organising code using classes and objects.

---

### Why use OOP?
OOP helps you keep related data and functions together.

For example, a Player object might store its name, health and score.

---

### Example:

    class Player:
        def __init__(self, name):
            self.name = name
            self.health = 100
            self.score = 0

        def take_damage(self, amount):
            self.health = self.health - amount

        def add_score(self, points):
            self.score = self.score + points

    player1 = Player("Paddy")
    player1.take_damage(20)
    player1.add_score(10)

    print(player1.health)
    print(player1.score)

will display:

    >>> 80
    >>> 10

---

### Objects are separate
Each object has its own data.

#### Example:

    player1 = Player("Paddy")
    player2 = Player("Sarah")

    player1.add_score(10)

    print(player1.score)
    print(player2.score)

will display:

    >>> 10
    >>> 0

## Try it yourself

- Create a Player class with name, health and score
- Make methods to change the health and score
- Create two different players
- Show that changing one player does not change the other player

