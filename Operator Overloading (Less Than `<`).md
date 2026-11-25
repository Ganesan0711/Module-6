
# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the less than (`<`) operator using a custom class.

## 🧠 ALGORITHM

1. Create a class named `A`.
2. Define the `__init__()` constructor to initialize the object with a value `a`.
3. Define the `__lt__()` method to overload the less than (`<`) operator.
4. If `self.a < o.a`, return `"ob1 is less than ob2"`.
5. Otherwise, return `"ob2 is less than ob1"`.
6. Create two objects named `ob1` and `ob2` with values.
7. Use `print(ob1 < ob2)` to call the overloaded operator.
8. Display the result.

## 💻 PROGRAM

```python
class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"


ob1 = A(10)
ob2 = A(20)

print(ob1 < ob2)
```

## 📤 OUTPUT

```text
ob1 is less than ob2
```

## ✅ RESULT

Thus, the Python program demonstrating **operator overloading using the less than (`<`) operator** was executed successfully.
