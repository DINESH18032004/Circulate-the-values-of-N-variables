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
#Developed by: DINESH KUMAR R
#RegisterNumber:212222110010
def circulate():
    l=eval(input())
    n=eval(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)   
 ```


## Output:

![1b](https://user-images.githubusercontent.com/119477784/226182630-13b659c5-e883-4b35-9195-e7c37ddb65ce.png)


## Result:

Thus the circulating the values of n variables are successfully executed
