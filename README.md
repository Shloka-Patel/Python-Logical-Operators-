# Python-Logical-Operators-
Logical Operators are used to combine difeerent conditions. 
<ol><li>A and B (Both conditions need to be true.) </li> <li>C or D (Only one condition needs to be true.) </li> <li> not E (The condition must be false.) </li></ol> 

Code representing the use of nested if, if/else/elif and logical operators. <br> 

```
print("Welcome to the rollercoaster!")
height = int(input("What is your height in cm? "))
bill = 0
if height >= 120:
    print("You can ride the rollercoaster!")
    age = int(input("What is your age? "))
    if age < 12:
        bill = 5
        print("Child tickets are $5.")
    elif age <= 18:
        bill = 7
        print("Youth tickets are $7.")
    else:
        bill=12
        print("Adult tickets are $12.")
        if (45<=age<=55):
          midlife_crisis = input("Are you dealing with midlife crisis: Y or N?")
          if (midlife_crisis=="Y"):
              bill=0
              print("Your total bill is 0.")
    wants_photo = input("Do you want a photo taken? Y or N. ")
    if wants_photo == "Y":
        bill += 3

    print(f"Your final bill is ${bill}")

else:
    print("Sorry, you have to grow taller before you can ride.")
```
