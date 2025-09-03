## Loops in Python: downward pyramid pattern of stars

## 🎯 Aim
To write a Python program to print the downward pyramid pattern of stars

## 🧠 Algorithm
1. Read an integer rows from the user (number of pattern rows).
2. Loop i from rows + 1 down to 1 (decreasing order).
3. Inside the loop, run another loop j from 0 to i - 2 to control the number of stars in each row.
4. Print "* " for each j, staying on the same line.
5. After the inner loop finishes, move to the next line using print(" ").

## 🧾 Program
~~~
rows = int(input())
for i in range(rows + 1, 0, -1):
    for j in range(0, i - 1):
        print("*", end=' ')
    print(" ")
~~~
## Output
<img width="496" height="622" alt="image" src="https://github.com/user-attachments/assets/052a3d3d-4021-43ba-a225-3923f03deda0" />



## Result
Thus the output is verified.
