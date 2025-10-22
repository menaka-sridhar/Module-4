# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
import math<br>
class cse:<br>
def mech(self, radius):<br>
   area = math.pi * radius ** 2<br>
   return area<br>
r = float(input("Enter the radius of the circle: "))<br>
circle = cse()<br>
area = circle.mech(r)<br>
print("The area of the circle with radius", r, "is:", area)<br>


## Output
<img width="1428" height="383" alt="image" src="https://github.com/user-attachments/assets/10ac57eb-4009-46e4-9176-5bd51291019c" />

## Result
The code executed successfully.
