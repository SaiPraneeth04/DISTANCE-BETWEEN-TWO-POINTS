# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
import math package
### Step 2: 
take input using variable for 1 st number
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
formula: distance = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
### Step 5: 
print distance in two decimal
### PROGRAM:
```python
#Program to find the distance between two points.
#Developed by: Sai Praneeth K
#RegisterNumber:22005263
import math
l1 = [4,2]
l2 = [10,6]
d = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(d))
```


### OUTPUT:
![MODEL](/sai(distance).png)


### RESULT:
By this program we able to find the distance between two points
