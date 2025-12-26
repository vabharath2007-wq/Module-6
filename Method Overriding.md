# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj1`.
4. Create an instance of the `Shark` class named `obj2`.
5. call the type method in fish using obj1.
6. call the type method in shark using obj2.

## 💻 PROGRAM:

class Fish:
    
    def type(self):
        print("fish")

class Shark(Fish):
    
    def type(slef):
        print("shark")

obj1=Fish()

obj2=Shark()

obj1.type()

obj2.type()

## OUTPUT

<img width="344" height="137" alt="image" src="https://github.com/user-attachments/assets/775f8900-57af-4138-ac21-293e5702882c" />


## RESULT
Thus the program is simulated sucessfully
