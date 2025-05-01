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

```python
import math
class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"The area of the circle with radius {radius} is: {area:.2f}")
radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)

```

## Output

![image](https://github.com/user-attachments/assets/0cca1d59-abca-449d-b382-8aa9a3b173c1)

## Result
Hence the program is executed successfully.
