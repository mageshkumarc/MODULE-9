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
class Generate:
    def __init__(self, first,d,last):
        self.first = first
        self.d = d
        self.last=last
    def Ap_generate(self):
        L=[i for i in range(self.first,self.last+1,self.d)]
        return L


Series = Generate(200,2,301)

print(Series.Ap_generate())
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/ef53065c-2b1a-48bc-b351-b28cfb16b88d)
![image](https://github.com/user-attachments/assets/ad7f1b9d-ece9-492e-85e5-6556629c9b5f)
![image](https://github.com/user-attachments/assets/383ee3da-e42c-435b-9a17-51e3d28d515e)


## RESULT:
Thus,the program is executed successfully
