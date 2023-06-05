# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
First, we import the "math" module, which provides various mathematical functions.

### Step 2:
Then, we create two lists l1 and l2, each containing two values (x and y coordinates)
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
We assign the result of the calculation to the variable "distance".
### Step 5: 
Finally, we use the "print()" function to display the value of "distance" with two decimal places.
### PROGRAM:
```
#Developed by: NARESH.V
#RegisterNumber: 212222110027
import math
l1 = [4,2]
l2 = [10,6]
distance = math.sqrt((l2[0]-l1[0])**2+ (l2[1] - l1[1])**2)
print("{:.2f}".format(distance))
 ``` 


### OUTPUT:
![image](https://github.com/NARESHVB/DISTANCE-BETWEEN-TWO-POINTS/assets/119393642/7b411308-1f1d-4a51-aa34-2f2b56da731a)


### RESULT:
Program to find the distance between two points was successfully executed.
