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
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![nvariables](https://user-images.githubusercontent.com/118447015/209439240-536532d0-b1b4-4d55-9bde-8759ae4ad63b.png)

![n variables](https://user-images.githubusercontent.com/118447015/209439251-a76d2f91-17ae-415e-ad58-8b2e2bae0db7.png)



## Result:
Thus Circulating The values N VAriable's are successfully executed
