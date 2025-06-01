# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program

```
class Rectangle:
    def __init__(self, length, breadth):
        self.__length = length 
        self.__breadth = breadth  

    def display_values(self):
        print(f"Length: {self.__length}, Breadth: {self.__breadth}")

rect = Rectangle(17,24)
rect.display_values()
```

## Output

![image](https://github.com/user-attachments/assets/6bf5036f-782a-4dfd-919d-1e58ba10f190)

## Result

Therefore,the given python programm is sucessufully verified.
