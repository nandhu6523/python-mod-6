
## Method Overriding

### AIM  

To write a Python program Create a parent class Fish and define a class method type, then create a child class called Shark while overriding the type method so that objects instantiated from the Shark class use the overridden method.

### ALGORITHM

1. Begin the program.
2. Define class Fish with a method type() that prints "fish".
3. Define class Shark (inheriting from Fish) and override the type() method to print "shark".
4. Create an object obj_goldfish of class Fish.
5. Create an object obj_hammerhead of class Shark.
6. Call the type() method on both objects:
   obj_goldfish.type() prints "fish".
   obj_hammerhead.type() prints "shark".
7. Terminate the program.

### PROGRAM

```

class Fish:
    def type(self):
        print("fish")
class Shark(Fish):
    def type(self):
        print("shark")
obj_goldfish=Fish()
obj_hammerhead=Shark()

obj_goldfish.type()
obj_hammerhead.type()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/2b4ae314-fb29-4c79-81ce-2e26afb2d117)

### RESULT

Thus the python program for overriden method was created successfully.
