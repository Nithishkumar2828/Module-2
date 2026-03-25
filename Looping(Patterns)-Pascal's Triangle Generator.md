# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
n = int(input())
for i in range(n):
    for s in range(n-i-1):
        print(" ",end="")
    a = 1
    for j in range(i+1):
        print(a,end=" ")
        a = a* (i-j) // (j +1)
    print()

```

## Output

<img width="691" height="685" alt="image" src="https://github.com/user-attachments/assets/595a9a82-9e05-4247-adc8-23b7b5286f32" />

## Result
Thus the python program to generate Pascals's triangle has beem executed successfully.


