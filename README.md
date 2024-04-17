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
/*
Program to find the gcd of two number using function.
Developed by: 
RegisterNumber:  
*/
#FINDING THE GREATEST COMMON DIVISOR OF THE TWO NUMBERS
#DEVELOPED BY: KISHORE NARAYANAN S R
#REGISTER NUMBER: 212223110023
def gcd():
    num1,num2 = int(input()),int(input())
    if num1>num2:
        small=num2
    else:
        small=num1
    for i in range(1,small+1):
        if (num1%i==0) and (num2%i==0):
            gcdd=i
    print("GCD of two numbers is:",gcdd)
```

## Output:
![Screenshot 2024-04-17 082215](https://github.com/KISHORENARAYANANSR/GCD-of-two-numbers/assets/148202102/d0864ac5-374d-42a8-87cc-48a8e42ebbd9)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
