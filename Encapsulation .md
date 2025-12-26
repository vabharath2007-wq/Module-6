# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM
To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__width`.

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__width`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__width`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

## 💻 Program

class rectangle:
    def __init__(self,length,width):
        self.__length=length
        self.__width=width
        
    def display(self):
        print(self.__length)
        print(self.__width)
        
    def get_length(self):
        return self.__length
        
    def get_width(self):
        return self.__width
        
r=rectangle(5,3)

r.display()

## Output

<img width="295" height="127" alt="image" src="https://github.com/user-attachments/assets/beb228fa-ccb6-41b8-a647-9afd3dbaf674" />


## Result
Thus the program is simulated sucessfully
