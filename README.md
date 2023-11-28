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
Developed by: AJITH KUMAR A
RegisterNumber: 23002150 
*/
def sqroot():
    num1=int(input())
    num2=float(num1)
    for i in range(100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
sqroot()    
```

## Output:
![gcd of two number](gcd.png)
![image](https://github.com/Ajith1413/Square-root-of-a-number/assets/139842524/5498f1e7-cfba-4f29-9cc7-57662d7c04de)





## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
