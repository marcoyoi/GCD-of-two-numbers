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
```py
# Program to find GCD of Two Numbers
# Developed By:Meyyappan.T
# Register no :23000788

def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1,smaller+1):
        if(n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)

```

## Output:
![GCD](https://github.com/marcoyoi/GCD-of-two-numbers/assets/128804366/82aae918-e530-4417-9947-b0e9d266ebcc)


## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
