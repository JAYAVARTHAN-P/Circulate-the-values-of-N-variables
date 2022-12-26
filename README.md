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
Print the coding to get answer
## Program:
```
#Program to circulate N values.
#Developed by: Jayavarthan P
#RegisterNumber:22008689

def circulate():
     l=eval(input())
     n=int(input())
     l=l[n:]+l[:n]
     print("After circulating the values are:",l)
```


## Output:
![Circulate (1)](https://user-images.githubusercontent.com/121369281/209518447-1f7a4968-4ef3-44ef-9f72-b278e36d7bab.png)
![Circulate (2)](https://user-images.githubusercontent.com/121369281/209518459-bf829910-9da5-4bc6-be1e-d4ab76d091a0.png)


## Result:
