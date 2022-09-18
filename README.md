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
# Program to find the square root for the given number(newton's method) using function.
# Developed by: sandhiya.R
# RegisterNumber: 22001197

t= int(input())
x=1
for i in range(10):
    x=0.5*(x+t/x)
print("Square root of the number:",x)

```
## Output:
![sqroot](https://user-images.githubusercontent.com/113497571/190888896-960f416a-62be-4093-8eff-756fd5647a5b.png)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
