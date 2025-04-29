

## Operator Overloading

### AIM  

To write a Python program to perform product of two complex number using binary '+' operator overloading.

### ALGORITHM

1. Start the Program.
2. Define a class complex with:
   Constructor __init__ to initialize two numbers a and b.
   Overload + operator (__add__) to multiply corresponding a and b values and return a tuple.
4. Create two objects Ob1 and Ob2 of complex class with given values.
5. Add the two objects using + operator, which actually multiplies their parts.
6. Print the result (a tuple of the two products).
7. End the Program.

### PROGRAM

```

class complex:
    def __init__(self,a,b):
        self.a=a
        self.b=b
    def __add__(self,other):
        return self.a*other.a,self.b*other.b
Ob1 = complex(1, 2)
Ob2 = complex(2, 3)
Ob3=Ob1 + Ob2
print(Ob3)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/0ff7839a-db2d-48f0-9266-ca34941e2fb8)

### RESULT

Thus the Python program to perform product of two complex number using binary '+' operator overloading was successfully created.

