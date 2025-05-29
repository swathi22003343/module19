# EX 1A RECURSIVE FUNCTION

# DATE:

# AIM:
To write a Python program using a recursive function to reverse a given string
# ALGORITHM:
STEP1:Start the program.

STEP2:Define a recursive function reverse_string(s).

STEP3:Read a string from the user.

STEP4:Call the recursive function with the string.

STEP5:Display the reversed string.

STEP6:End the program.

# PROGRAM:
```
def rev(s):
    if(len(s)<1):
        return s
    return s[-1]+rev(s[:-1])
    
s=input()
print(rev(s))
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/599ff73a-bccf-4bf1-9aaa-bf05b2619e3f)

# RESULT:
The program was successfully executed and reversed the string using recursion.It produced the correct output for the given input.


