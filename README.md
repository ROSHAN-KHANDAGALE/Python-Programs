# W3Resources (Basic Python Part - I)
### 1. Write a Python program to print the following string in a specific format (see the output).
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

### 2. Write a Python program to find out what version of Python you are using.
### Code

```
import sys
print("Python Version: ", sys.version)
```

### 3. Write a Python program to display the current date and time.
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

### 4. Write a Python program that calculates the area of a circle based on the radius entered by the user.
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

### 5. Write a Python program that accepts the user's first and last name and prints them in reverse order with a space between them.
### Code
```
first_name = input("Input First Name: ")
last_name = input("Input last name: ")
print(last_name, first_name)
```

### 6. Write a Python program that accepts a sequence of comma-separated numbers from the user and generates a list and a tuple of those numbers.
## Sample data : 3, 5, 7, 23
```
Output :
List : ['3', ' 5', ' 7', ' 23']
Tuple : ('3', ' 5', ' 7', ' 23')
```
### Code
```
values = input("Input some values followed by commans: ")
list_value = values.split(",")
print(List: list_value)
print(Tuple: tuple(list_value))
```

### 7. Write a Python program that accepts a filename from the user and prints the extension of the file.
### Sample filename : abc.java
```
Output : java
```
### Code
```
file_name = input("Enter file name with its extension: ")
ext_split = file_name.split(".")
print("File Extension is:", ext_split[-1])
```

### 8. Write a Python program to display the first and last colors from the following list.
### Sample data: color_list = ["Red","Green","White" ,"Black"]
### Code
```
color_list = ["Red", "Green", "White", "Black"]
print(color_list[0], color_list[-1])
```

### 9. Write a Python program to display the examination schedule. (extract the date from exam_st_date).
### Sample Input: exam_st_date = (11, 12, 2014)
```
Sample Output : The examination will start from : 11 / 12 / 2014
```
### Code
```
exam_st_date = (11, 12, 2014)
print("The examination will start from: ", exam_st_date[0], "/", exam_st_date[1], "/", exam_st_date[2])
```

### 10. Write a Python program that accepts an integer (n) and computes the value of n+nn+nnn.
### Sample value of n is 5
### Expected Result : 615
### Code
```
n = int(input("Enter n value: "))
n1 = int("%s" % n)
n2 = int("%s%s" % (n, n))
n3 = int("%s%s%s" % (n, n, n))
print(n1 + n2 + n3)
```

### 11. Write a Python program to print the documents (syntax, description etc.) of Python built-in function(s).
### Sample function : abs()
```
Expected Result :
abs(number) -> number
Return the absolute value of the argument.
```

### 12. Write a Python program that prints the calendar for a given month and year.
#### Note : Use 'calendar' module.
### Code
```chatinput
import calendar

month = int(input("Enter month: "))
year = int(input("Enter Year: "))
cal = calendar.month(year, month)
print(cal)
```

### 13. Write a Python program to print the following 'here document'.
### Sample string : 
```
a string that you "don't" have to escape
This
is a ....... multi-line
heredoc string --------> example
```

### 14. Write a Python program to calculate the number of days between two dates.
### Sample dates : (2014, 7, 2), (2014, 7, 11)
### Expected output : 9 days
### Code
```chatinput
from datetime import date

date1 = date(2014, 7, 29)
date2 = date(2014, 8, 3)
print("Remaining days: ", abs(date1 - date2))

```
