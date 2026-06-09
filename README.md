# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
### Step 2: 
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

## Program:
```
def circulate():
    a = ['a', 'b', 'c', 'd', 'e', 'f']
    n = int(input())
    a = a[n:] + a[:n]
    print("After circulating the values are:", a)

circulate()

```
## Output:

<img width="706" height="310" alt="image" src="https://github.com/user-attachments/assets/65749a34-da5a-4eb6-8375-5a4d9465e27f" />


## Result:

The program is excuted successfully
