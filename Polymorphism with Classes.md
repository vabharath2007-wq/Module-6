# # Python OOP: Polymorphism with Classes

## 🎯 AIM
Create a Parent class bird and inherit two child classes sparrow and ostrich from the bird class with the same method flight(). create oject for each class and call the methods of the class which will print the name of the bird that is flying.

## 🧠 ALGORITHM

1. create a class bird having methods intro and flight.
2. create a class sparrow inheriting bird class and have the method flight.
3.  create a class ostrich inheriting bird class and have the method flight.
4.  call the bird class to initiale the methods.
5.  call the sparrow class to initiale the methods.
6.  call the ostrich class to initiale the methods.

## 💻 Program

class Bird:
    
    def intro(self):
        print("There are many types of birds.")
	
    def flight(self):
        print("Most of the birds can fly but some cannot.")

class sparrow(Bird):
    
    def flight(self):
        print("Sparrows can fly.")
	
class ostrich(Bird):
    
    def flight(self):
        print("Ostriches cannot fly.")
        
	
b = Bird()

b.intro()

b.flight()

s = sparrow()

s.intro()

s.flight()

o = ostrich()

o.intro()

o.flight()

## Output

<img width="930" height="232" alt="image" src="https://github.com/user-attachments/assets/578a825f-b14e-4f01-8ff2-e7818441bc3c" />


## Result
Thus the program is simulated sucessfully
