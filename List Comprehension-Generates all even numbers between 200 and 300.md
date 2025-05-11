# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**

---

## 💻 PROGRAM:
```
class Program:
    def __init__(self):
        self.a = 200
        self.b = 2
        self.c = 300

    def display(self):
        even_numbers = [i for i in range(self.a, self.c + 1, self.b) if i % 2 == 0]
        print(even_numbers)

p = Program()
p.display()
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/cdd2fba9-28a2-420c-97cc-0276522c8024)

## RESULT:
Thus,the program is executed successfully
