## 1. Write a Python program to print the following string in a specific format (see the output).
### Sample String : "Twinkle, twinkle, little star, How I wonder what you are! Up above the world so high, Like a diamond in the sky. Twinkle, twinkle, little star, How I wonder what you are"

### Output :
```
Twinkle, twinkle, little star,
	How I wonder what you are! 
		Up above the world so high,   		
		Like a diamond in the sky. 
Twinkle, twinkle, little star, 
	How I wonder what you are
```
### Code
```
print("Twinkle, twinkle, little star,")
print("	       How I wonder what you are! ")
print("		         Up above the world so high,")
print("		         Like a diamond in the sky.")
print("Twinkle, twinkle, little star,")
print(" 	   How I wonder what you are")
```

## 2. Write a Python program to find out what version of Python you are using.
### Code

```
import sys
print("Python Version: ", sys.version)
```

## 3. Write a Python program to display the current date and time.
### Sample Output :
```
Current date and time :
2014-07-05 14:34:14
```
### Code
```
import datetime
print("Current Date and Time: ", datetime.datetime.now())
```

## 4. Write a Python program that calculates the area of a circle based on the radius entered by the user.
```
Sample Output :
r = 1.1
Area = 3.8013271108436504
```
### Code
```
print("Area of Circle Program!!")
radius = float(input("Input Radius: "))
area_of_circle = (22/7) * radius ** 2
print("Area of Circle = ", area_of_circle)
```
