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
4. Use for() and if() loop to find the GCD of the two numbers

## Program:

#GCD of a number using function
#Developed by: ponguru aasrith sairam
#Register number: 23007809

num1=int(input())
num2=int(input())
def gcd():
    for i in range(num1,0,-1):
        if num1%i==0 and num2%i==0:
            gcd=i
            break
    print(f"GCD of two numbers is: {gcd}")


## Output:

![WhatsApp Image 2023-07-24 at 18 38 50](https://github.com/AasrithSairam/GCD-of-two-numbers/assets/139331438/ad02cbd1-4ba4-46bb-b787-b4f10639300f)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
