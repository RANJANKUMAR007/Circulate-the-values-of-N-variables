# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Initalsie a list
### Step 2:
Assing the values of a variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:  
Print both the values it would be interchanged

### Step 6:
End the program
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
### OUTPUT:
![alt text](<Screenshot 2024-04-06 081146.png>)

## Result: 
Thus the program has been executed successfully
