# Ex.No: 10  Pytest Python program for Fibonacci Series

### DATE:  09/05/2025                                                                   
### REGISTER NUMBER : 212222040033
### AIM:
To write a python program for Fibonacci Series and test the test cases using Pytest. 

### Algorithm:

Step 1: Write the python program for Fibonacci Series. 
Step 2: Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
Step 3: Write some test cases for to be tested and save it as “test_fib.py”. 
Step 4: Open command prompt and change the directory to where pytest and program is 
saved and type “pytest test_fib.py” and run it. 
Step 5: Stop the program.

### Program:
```
def fibR(n): 
    if n == 1 or n == 2: 
        return 1 
    return fibR(n - 1) + fibR(n - 2) 
# Test cases
def test_fib_1_equals_1(): 
    assert fibR(1) == 1 
def test_fib_2_equals_1(): 
    assert fibR(2) == 1 
def test_fib_6_equals_8(): 
    assert fibR(6) == 8  
test_fib_1_equals_1()
test_fib_2_equals_1()
test_fib_6_equals_8()
```
### Output:
![Screenshot 2025-05-28 102611](https://github.com/user-attachments/assets/0a084895-17e6-436f-9bff-d1661e645a9b)

### Result:
Thus, the python program for Fibonacci Series is tested using pytest and executed and output is verified successfully.

