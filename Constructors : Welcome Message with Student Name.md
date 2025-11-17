# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python programto implement a  constructor for class Student, all we need to do is to pass actual values to the arguments name and rollno.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```python
class Student:
    def __init__(self, name, roll):
        self.name = name
        self.roll = roll

    def show(self):
        print("Name: ", self.name)
        print("Roll no.: ", self.roll)

name = input()
roll = int(input())
s1 = Student(name, roll)
s1.show()
```
## Output
<img width="492" height="244" alt="image" src="https://github.com/user-attachments/assets/a33cfb6a-65f1-472c-8b57-6501bc5688d0" />



## Result
Thus, To write a Python program to implement a  constructor for class Student, all we need to do is to pass actual values to the arguments name and rollno is verified.
