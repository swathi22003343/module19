# EX-1BMERGE SORT

# DATE:

# AIM:
To write a Python program that implements Merge Sort to sort a list of float values.
# ALGORITHM:
STEP1:If the list has 1 or 0 elements, it is already sorted.

STEP2:Split the list into two halves.

STEP3:Recursively sort both halves using merge sort.

STEP4:Merge the two sorted halves into a single sorted list.

# PROGRAM:
```
DEVELPOED BY:SWATHI D
REGISTER NUMBER:212222230154
```
```
def Merge_Sort(S):
    if len(S)>1:
        mid=len(S)//2
        L=S[:mid]
        R=S[mid:]
        Merge_Sort(L)
        Merge_Sort(R)
        i=j=k=0
        while i<len(L) and j<len(R):
            if L[i]<=R[j]:
                S[k]=L[i]
                i+=1
            else:
                S[k]=R[j]
                j+=1
            k+=1
        while i<len(L):
            S[k]=L[i]
            i+=1
            k+=1
        while j<len(R):
            S[k]=R[j]
            j+=1
            k+=1
            
n=int(input())
S=[]
for i in range(n):
    S.append(float(input()))
print("Given array is")
for i in range(n):
    print(S[i],end=" ")
Merge_Sort(S)
print("\nSorted array is")
for i in range(n):
    print(S[i],end=" ")
```
# OUPUT:
![image](https://github.com/user-attachments/assets/0091c682-6574-4dc0-aee6-4bfbc64ff341)

# RESULT:
The program successfully implemented Merge Sort on the given float array and sorted the values in ascending order.
