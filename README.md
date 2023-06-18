# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the n values from the user
### Step 2: 
Circulate the values of n variables
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be circulated
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: shalini.k
#RegisterNumber:212222240095
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![image](https://github.com/shalinikannan23/Circulate-the-values-of-N-variables/assets/118656529/f0407fc6-c5b6-4be5-ae94-c9cf042a05e3)

## Result:
Thus circulating the values of n variables are successfully executed.
