# SaNsKruti
Assignment 3
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Greatest number is:", a)
elif b >= a and b >= c:
    print("Greatest number is:", b)
else:
    print("Greatest number is:", c)

    output 
    Enter first number: 5
Enter second number: 9
Enter third number: 3
Greatest number is: 9


num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

    output 
    Enter a number: 8
Even number


ch = input("Enter a character: ")

if ch.isupper():
    print("Uppercase letter")
elif ch.islower():
    print("Lowercase letter")
else:
    print("Not an alphabet")

    output 
    Enter a character: A
Uppercase letter
x = input("Enter something: ")

if x.isdigit():
    print("It is a number")
else:
    print("It is a character")

    output
    Enter something: 7
It is a number
