# Python Object-Oriented Programming
## Welcome to this Class


In This lession, i am going to talk about below topics as below:

#Python Classes and Objects:
The __init__() Method
Example: Add Two Complex Numbers
Why object-oriented programming?
Task: Perimeter of Triangle

# Python Classes and Objects
Think of a class as a blueprint of a house. It contains all the details about the floors, doors, windows etc. Based on these descriptions we build the house. The actual physical house is the object.

class Student:

Here, student1 and student2 are objects of the Student class.

Now, we are going to start adding different attributes to these object instance.

Let's now see how we can define methods inside a class.



class Student:
    def check_pass_fail(self):
        if self.marks >= 40:
            return True
        else:
            return False

student1 = Student()
did_pass = student1.check_pass_fail()


As shown in the following figure, the same object name can be present in multiple namespaces as isolation between the same name is maintained by their namespace.
print(did_pass)

------------------------------------------

Here, the check_pass_fail() method is defined inside the Student class

Now, any object created from the Student class can access this method.

We have called this method without passing any arguments, however, the method definition takes one argument named self.

Whenever we define methods for a class, we need to use self as the first parameter. This self represents the object calling it. In our example, self refers to the student1 object, and self.marks refers to the marks attribute of student1.


The __init__() Method

Adding attributes to the object manually after defining it is not a good practice.

Python offers a much more elegant and compact way of defining attributes right while instantiating the object. For that, we use the init method.

If you are coming from other languages like C++ or Java, the Python __init__() method closely resembles constructors.



Python is a high-level, general-purpose and a very popular programming language. Python programming language (latest Python 3) is being used in web development, Machine Learning applications, along with all cutting edge technology in Software Industry. Python Programming Language is very well suited for Beginners, also for experienced programmers with other programming languages like C++ and Java.


