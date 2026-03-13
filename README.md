📘 Simple Class and Object Example in Python

📌 Overview

This Python program demonstrates the basic concept of Object-Oriented Programming (OOP) using a class and object.

The program creates a Student class with a method that prints a message when called.

This example helps beginners understand how classes, objects, and methods work in Python.

⚙️ Source Code

class Student:
    def display(self):
        print("Hello I am a student")

s1 = Student()
s1.display()
🧠 How It Works
1️⃣ Create a Class
class Student:

A class is a blueprint for creating objects.

Here, Student represents a type of object.

2️⃣ Define a Method
def display(self):

display() is a method inside the class.

self refers to the current object that calls the method.

3️⃣ Print a Message
print("Hello I am a student")

This line prints a message when the method is executed.

4️⃣ Create an Object
s1 = Student()

s1 is an object (instance) of the Student class.

It is created using the class constructor.

5️⃣ Call the Method
s1.display()

The object s1 calls the display() method.

The message inside the method is printed.

▶️ Output
Hello I am a student
🔑 Key Concepts Demonstrated

Classes

Objects (Instances)

Methods

self keyword

Basic Object-Oriented Programming

⏱️ Time Complexity

O(1) — The program performs a constant number of operations.

🚀 Possible Enhancements

You can improve the class by adding student details like name and age.

Example:

class Student:
    def __init__(self, name):
        self.name = name

    def display(self):
        print("Hello I am", self.name)

s1 = Student("Pranay")
s1.display()

Output:

Hello I am Pranay
📚 Learning Outcomes

After understanding this program, you will learn:

How to create a class

How to create objects

How methods work inside classes

Basic structure of Object-Oriented Programming in Python
👨‍💻 This program is a beginner example for learning OOP concepts in Python.
