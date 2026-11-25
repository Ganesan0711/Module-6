
# 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two classes, `Beans` and `Mango`, and a generic function that accepts any object and displays its type (Fruit or Vegetable) and color using polymorphism.

## 🧠 ALGORITHM

1. Create a class named `Beans`.
2. Define the `type()` method to print `"Vegetable"`.
3. Define the `color()` method to print `"Green"`.
4. Create a class named `Mango`.
5. Define the `type()` method to print `"Fruit"`.
6. Define the `color()` method to print `"Yellow"`.
7. Define a generic function named `func(obj)`.
8. Call `obj.type()` and `obj.color()` inside the function.
9. Create objects of both `Beans` and `Mango` classes.
10. Pass both objects to the `func()` function.
11. Display the output.

## 💻 PROGRAM

```python
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


def func(obj):
    obj.type()
    obj.color()


obj_beans = Beans()
obj_mango = Mango()

func(obj_beans)
func(obj_mango)
```

## 📤 OUTPUT

```text
Vegetable
Green
Fruit
Yellow
```

## ✅ RESULT

Thus, the Python program demonstrating **Polymorphism using Beans and Mango classes** was executed successfully.
