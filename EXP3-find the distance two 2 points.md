# EXP 3.

## Ram and Shyam were walking on a bridge. During their conversion, they were in need to find the length of the bridge. Write a program to find the distance of the bridge from one point to another point (display with 2 decimal points) second point coordinates- [10,6] and first point coordinates [4,2]

d=√((x_2-x_1)²+(y_2-y_1)²) 

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Using import math function,do the calculations.
### Step 2: 
Take the two coordinates as l1 and l2.
### Step 3: 
Substitute the values in the distance formula

√((x_2-x_1)²+(y_2-y_1)²)

### Step 4: 
using the print function, display the distance between the two points.
### Step 5: 
End the program.
### PROGRAM:

```
import math 
l1 = [4,2]
l2 = [10,6]
d = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print(f"{d:.2f}")
```

### OUTPUT:

![image](https://github.com/Kavin1311/PYTHON-PROGRAMMING-19AI301/assets/145695724/1e6c2a4c-92cd-416e-9638-2ce057f7c51b)

### RESULT:
The distance between the two points is sucessfully executed and displayed.





