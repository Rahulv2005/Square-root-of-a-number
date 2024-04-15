# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
/*
Program to find the square root for the given number(newton's method) using function.
Developed by:Rahul. V 
RegisterNumber: 212223240132 
*/
# Program to find the square root for the given number(newton's method) using function.
# Developed by: KAMESH R R
# RegisterNumber : 212223230095
def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
```

## Output:
![image](https://github.com/Rahulv2005/Square-root-of-a-number/assets/152600335/f243b136-9c07-43bd-b08e-e0395a0d1a75)
![image](https://github.com/Rahulv2005/Square-root-of-a-number/assets/152600335/bfa6debf-2ae7-4b5f-b18c-f954c942fe06)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
