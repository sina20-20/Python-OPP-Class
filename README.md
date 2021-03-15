# Python Object-Oriented Programming
## Welcome to this part.


In This lession,i am going to talk about below topics as below:

Python Classes and Objects
The __init__() Method
Example: Add Two Complex Numbers
Why object-oriented programming?
Task: Perimeter of Triangle

# Python Classes and Objects
Think of a class as a blueprint of a house. It contains all the details about the floors, doors, windows etc. Based on these descriptions we build the house. The actual physical house is the object.


class Student:
    pass

student1 = Student()
student2 = Student()

Here, student1 and student2 are objects of the Student class.

Now, we are going to start adding different attributes to these object instance.


class Student:
    def check_pass_fail(self):
        if self.marks >= 40:
            return True
        else:
            return False

student1 = Student()
student1.name = "Harry"
student1.marks = 85

did_pass = student1.check_pass_fail()
print(did_pass)
