# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.


## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.



## 💻 Program
## Developed By : VIMALRAJ B
## Register Number : 212224230304
```
class A:
    def __init__(self,value):
        self.value=value
    def __lt__(self,other):
        return self.value<other.value
o=A(200)
b=A(30)
if o<b:
    print("ob1 is less than ob2")
else:
    print("ob2 is less than ob1")
```
## Output

<img width="566" height="247" alt="image" src="https://github.com/user-attachments/assets/723517fd-7c79-41ee-9ae3-7aa9f567325d" />


## Result

Thus , the program was executed Successfully.
