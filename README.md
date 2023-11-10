# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function to circulate variables.
### Step 2: 
Assign the given values in a list.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Assign a variable for the new list after slicing and print the variable.
### Step 6: 
End of the program.

## Program:
```
#Program to circulate N values.

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
    
#Developed by: KOUSALYA A.
#RegisterNumber: 212222230068
```

## Output:
![image](https://github.com/Kousalya22008930/Circulate-the-values-of-N-variables/assets/119389108/711898d4-40b9-4aa3-a168-2f25394ab7fb)

## Result:
To Circulate the value of n variables using python was executed successfully.


