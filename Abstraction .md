#  Python OOP: Abstract Class & Method Example

## 🎯 AIM
Define the abstract base class named Polygon and also define the abstract method. This base class inherited by the various subclasses. Implement the abstract method in each subclass. Create the object of the subclasses and invoke the sides() method.

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `polygon`**:
   - Define an abstract method `sides()` with `@abstractmethod`.

3. **Create Subclass `triangle`**:
    having method sides and print("Triangle has 3 sides")

5. **Create Subclass `pentagon`**:
    having method sides and print("pentagon has 5 sides")

7. **Create Subclass 'hexagon'**:
    having method sides and print("hexagon has 6 sides") 

9. **Create Objects & Call Methods**:
   - Instantiate `triangle` and `pentagon` and 'hexagon'.
   - Call their `sides()` methods.

## 💻 Program

from abc import ABC,abstractmethod 
  
class Polygon(ABC):   
  
   @abstractmethod  
   def sides(self):   
      pass  
  
class Triangle(Polygon):   
    
    def sides(self):   
        print("Triangle has 3 sides")   
  
class Pentagon(Polygon):   
    
    def sides(self):
        print("Pentagon has 5 sides")

class Hexagon(Polygon):
    
    def sides(self):
        print("Hexagon has 6 sides")

class square(Polygon):   
  
   def sides(self):   
      print("I have 4 sides")   
  
t = Triangle()   

t.sides()  
  
s = square()   

s.sides()
  
p = Pentagon()   

p.sides()  
  
k = Hexagon()  

k.sides()


## Output

<img width="535" height="187" alt="image" src="https://github.com/user-attachments/assets/b3ffe5aa-1f46-4607-a9f0-a4efb04ec6c3" />


## Result
Thus the program is simulated sucessfully
