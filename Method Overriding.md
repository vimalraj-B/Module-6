# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
class Fish:
       def info(self):
           print("fish")
class Shark(Fish):
    def info(self):
        print("shark")
f=Fish()
s=Shark()
f.info()
s.info()
```
## OUTPUT

<img width="326" height="209" alt="image" src="https://github.com/user-attachments/assets/e9e37c1a-b41f-4a75-8656-3e976e97de80" />


## RESULT

Thus , the program was executed Successfully.
