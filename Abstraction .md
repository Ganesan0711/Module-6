
# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM
To create an abstract class named `Shape` with an abstract method `calculate_area()` and implement this method in two subclasses: `Rectangle` and `Circle`.

## 🧠 ALGORITHM
1. Import `ABC` and `abstractmethod` from the `abc` module.
2. Create an abstract class named `Shape`.
3. Define an abstract method `calculate_area()` inside the `Shape` class.
4. Create a subclass named `Rectangle` that inherits from `Shape`.
5. Initialize length and breadth with default values.
6. Override the `calculate_area()` method to calculate the rectangle area.
7. Create another subclass named `Circle` that inherits from `Shape`.
8. Initialize the radius with a default value.
9. Override the `calculate_area()` method to calculate the circle area.
10. Create objects of both subclasses and display their areas.

## 💻 PROGRAM

```python
from abc import ABC, abstractmethod
import math

class Shape(ABC):

    @abstractmethod
    def calculate_area(self):
        pass


class Rectangle(Shape):

    def __init__(self, length=10, breadth=5):
        self.length = length
        self.breadth = breadth

    def calculate_area(self):
        return self.length * self.breadth


class Circle(Shape):

    def __init__(self, radius=7):
        self.radius = radius

    def calculate_area(self):
        return math.pi * self.radius * self.radius


r = Rectangle()
c = Circle()

print("Area of Rectangle:", r.calculate_area())
print("Area of Circle:", round(c.calculate_area(), 2))
```

## 📤 OUTPUT

```text
Area of Rectangle: 50
Area of Circle: 153.94
```

## ✅ RESULT
Thus, the Python program to demonstrate an abstract class and abstract method using the `Shape`, `Rectangle`, and `Circle` classes was executed successfully.
