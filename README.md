# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
## Step 1: 
First step is to define the function
## Step 2: 
Get l,n input from the user
## Step 3: 
Get the value from the user for the number of rotation
## Step 4: 
Using the slicing concept rotate the list
## Step 5: 
Print the result.
## Program:
``` Python
#Program to circulate N values.
#Developed by:Raja.R 
#RegisterNumber:22004914
def circulate():
    a=eval(input())
    n=eval(input())
    l=a[n:]+a[:n]
    print("After circulating the values are:",l)
```
## Output:
!['output'](/Screenshot%20from%202023-01-07%2022-11-34.png)
## Result:
The Circulate of n variable is executed successfully.