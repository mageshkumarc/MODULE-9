# 🧮 List Comprehension:Transpose of Matrix 

## 🎯 AIM:
To write a Python program to compute the **transpose** of a matrix using **list comprehension**.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `r` and `c` to represent the number of rows and columns of the matrix.
3. Get the values of `r` and `c` from the user.
4. Define a function `create(r, c)` to create the matrix by reading the elements from the user.
5. Use **list comprehension** to calculate the transpose of the matrix.
6. Print the transposed matrix.
7. **Stop**

---

## 💻 PROGRAM:
```
def create(r, c):
    print("Enter the matrix elements row by row:")
    matrix = []
    for i in range(r):
        row = list(map(int, input().split()))
        matrix.append(row)
    return matrix

r = int(input("Enter number of rows: "))
c = int(input("Enter number of columns: "))

matrix = create(r, c)
transpose = [[matrix[j][i] for j in range(r)] for i in range(c)]

print("\nOriginal matrix:")
for row in matrix:
    print(' '.join(map(str, row)))

print("\nTransposed matrix:")
for row in transpose:
    print(' '.join(map(str, row)))
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/6458ba23-178f-400c-a3ea-eea6bb6e34a3)

## RESULT:
Thus,the program is executed successfully

