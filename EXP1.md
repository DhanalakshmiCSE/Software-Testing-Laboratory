# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE: 13/03/2025                                                                          
### REGISTER NUMBER : 212222040033

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
## do_while:
```
def display(): 
    start = input("Enter a positive value for START: ") 
    end = input("Enter a positive value for END: ") 
    if start.isnumeric() and end.isnumeric(): 
        while True: 
            start = int(start) 
            end = int(end) 
            print(start, end=' ') 
            if start < end: 
                start += 1 
            else: 
                break 
    else: 
        print("Enter a valid positive number.") 
display()
```
## while_do:
```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric(): 
    start = int(start) 
    end = int(end) 
    while start <= end:   
        print(start) 
        start += 1 
else: 
    print("Enter a valid positive number.")
```
## switch:
```
def switch(): 
    switcher = { 
        0: "even", 
        1: "odd" 
    } 
    n = input('Enter a value for N: ') 
    try: 
        n = int(n) 
        print(switcher[n % 2]) 
    except ValueError: 
        print("Enter a valid number.") 

switch()
```
## if else:
```
def compare(): 
    a = input("Enter a value for A: ") 
    b = input("Enter a value for B: ") 
    try: 
        a = int(a) 
        b = int(b) 
        if a > b: 
            print("A is greater than B") 
        elif a < b: 
            print("B is greater than A") 
        else: 
            print("A is equal to B") 
    except ValueError: 
        print("Enter a valid number.")


compare()
```
## for:
```
def iterate(): 
    string=input("Enter a string: ")
    for i in string: 
        print(ord(i),end=" ") 
iterate()
```
### Output:
![Screenshot 2025-05-23 201023](https://github.com/user-attachments/assets/955b6c8a-860b-4e88-bda8-9271f1dd1bdc)
![Screenshot 2025-05-23 201646](https://github.com/user-attachments/assets/bb53c015-74f0-4319-a69c-7ed71fa16daa)
![Screenshot 2025-05-23 201830](https://github.com/user-attachments/assets/f4f82807-81ef-4f2c-bd3e-20930ac54d24)
![Screenshot 2025-05-23 202243](https://github.com/user-attachments/assets/f21b5faf-e722-4a62-9caf-5de1504a715f)
![Screenshot 2025-05-23 202427](https://github.com/user-attachments/assets/689c18b8-3b7f-4c93-abd7-45ddfea11f88)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


