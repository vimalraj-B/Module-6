# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.


## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.


## 💻 Program
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
class Rectangle:
  def __init__ (self,a,b):
    self.__length = 5
    self.__breadth = 3
  def pt(self):
      
    print(self.__length)
    print(self.__breadth)
 
r=Rectangle(5,3)
r.pt()
```
## Output

<img width="290" height="191" alt="image" src="https://github.com/user-attachments/assets/bf5ba147-0185-48ea-82ee-50eee13bb1b2" />


## Result

Thus , the program was executed Successfully.
