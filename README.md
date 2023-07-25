# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
#Program to find the GCD for two numbers
#Developed by: ABISHAI K C
#RegisterNumber: 23001564   

def gcd():
    n1 = int(input())
    n2 = int(input())
    for i in range (n1,0,-1):
        if n1%i==0 and n2%i==0:
            print("GCD of two numbers is:",i)
            break
        else:
            pass       
```

## Output:
![gcd of two number](/gcd%20output.png)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
