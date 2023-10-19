# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program.
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5: 
Using concatenation operation display the entire list.
### Step 6: 
Stop the program.
## Program:
```
#Program to circulate N values.
#Developed by: Santhan Kumar
#RegisterNumber: 23004568
def circulate():
    list1 = eval(input())
    n = int(input())
    result = list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```

## Output:
![circulate](https://github.com/SANTHAN-2006/Circulate-the-values-of-N-variables/assets/80164014/2b92bfce-eb51-4a65-b84b-e7fb250d315c)
## Result:
Thus, program for circulating the N values executed successfully.
