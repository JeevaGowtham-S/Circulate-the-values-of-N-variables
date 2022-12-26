# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Import def circulate
### Step 2: 
Prepare the lists from each linear equations and assign in np.array() 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Add coding to input value
### Step 6: 
Print he coding to get answer
## Program:
```
#Program to circulate N values.
#Developed by:jeeva gowtham s
#RegisterNumber:22008760)
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![expected](/image/expected.png)
![got](/image/got.png)
## Result:
Thus the python program to circuate the n variables using funtion concept is obtained.