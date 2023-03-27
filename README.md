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

![image](https://user-images.githubusercontent.com/119477784/227988377-c5ad90b3-d363-49c1-bcba-edec174e12ee.png)



## Result:

Thus the circulating the values of n variables are successfully executed
