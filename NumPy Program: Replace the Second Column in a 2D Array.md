# NumPy Program: Replace the Second Column in a 2D Array
## Name: SANJEV R M
## Reg No: 212223040186
## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
~~~
import numpy as np
orig=np.array(eval(input()))
new=np.array(eval(input()))
print("Printing Original array")
print(orig)
modif=np.delete(orig,1,axis=1)
print("Array after deleting column 2 on axis 1")
print(modif)
result=np.insert(modif,1,new,axis=1)
print("Array after inserting column 2 on axis 1")
print(result)
~~~

## Output
![image](https://github.com/user-attachments/assets/794f9923-8a71-471e-9ac6-14fc4a94f668)

## Result
Thus, the program has been executed successfully.
