Assignment Week 9a | Calculating the Area of a Circle in Python3

> NAME: Jackson McClean
> 
> **Making the area of a circle program**: I used my good friends `touch` and `nano` to create and edit my program called `circlearea.py`. I also used `chmod +x` to make the program executable. Here is the program itself (with #'s indicating comments):

```
#!/usr/bin/python3 # My absolute path to python3

radius = float(input("Enter a number: ")) # Gives the user the ability to input a number for the radius

def circle_radius(radius): # Defines the circle radius as the user's input number
        return radius

print("The radius of the circle is:", radius) # Prints the radius number that the user inputs

Area = float((3.1415926535) * (radius) * (radius)) # Formula for the area of a circle (thank you Dr. Salerno!)

def circle_area(radius): # Defines the area of a circle and also calculates the area based on the user's radius input
        return Area

print("The area of the circle is:", Area) # Prints the circle's area based  on the user's radius input and calculated by the Area formula
```

For this assignment, I want the radius to be 12. Here's what the program looks like when 12 is entered as the radius:

```
./circlearea.py
Enter a number: 12
The radius of the circle is: 12.0
The area of the circle is: 452.389342104
```

![](https://media1.tenor.com/m/N4CS9Sjw_1IAAAAd/sad-spiderman.gif)
