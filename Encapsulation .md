
# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with private member variables `__length` and `__breadth`.

## 🧠 ALGORITHM

1. Define a class named `Rectangle`.
2. Declare two private attributes: `__length` and `__breadth`.
3. Use the `__init__()` constructor to initialize the private variables.
4. Define a method to display the private variables from inside the class.
5. Create an object of the `Rectangle` class.
6. Call the display method to print the values.

## 💻 PROGRAM

```python
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


r = Rectangle(10, 5)
r.display()
```

## 📤 OUTPUT

```text
Length: 10
Breadth: 5
```

## ✅ RESULT

Thus, the Python program to implement **Encapsulation using private member variables** `__length` and `__breadth` was executed successfully.
