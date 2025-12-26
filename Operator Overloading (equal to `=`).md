# Python OOP: Operator Overloading (equal to `=`)

## 🎯 AIM
Write a python program to overload equality operator .

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `value`.

2. **Overload the `<` Operator**:
   - Define the `__eq__()` method with logic:
     - If `self.value = other.value`, print `"True"`
     - Else, print `"False"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `=` Operator**:
   - Use `(ob1 == ob2)` to trigger the overloaded behavior.


## 💻 Program

class A:
    
    def __init__(self,value):
        self.value=value
   
    def __eq__(self,other):
        return self.value==other.value
        
ob1 = A(2)

ob2 = A(4)

if ob1==ob2:
    
    print("equal")

else:

    print("Not equal")

## Output

<img width="319" height="126" alt="image" src="https://github.com/user-attachments/assets/ceb6b964-9077-40fc-9b21-bdf2d4c8dd6e" />


## Result
Thus, the program is simulated sucessfully
