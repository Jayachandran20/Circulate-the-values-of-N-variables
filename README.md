# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the two values from the user
### Step 2: 
Assign the value of second variable to a temporary variable 
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
#Program to find the circulate the n variables using function concept
#Developed by: M.Jayachandran
#RegisterNumber: 22008847
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:

![nvar](https://user-images.githubusercontent.com/118447015/214823643-301b318b-df7f-4028-a51d-db6739453776.png)



## Result:
Thus Circulating The values N VAriable's are successfully executed
