# EX 1C QUICKSORT
# DATE:
 # AIM:
To implement the Quick Sort algorithm using a randomly selected pivot in Python.

# ALGORITHM:

STEP1:Start the program


STEP2:Input the array to be sorted.

STEP3:Check if the length of the array is less than or equal to 1:

STEP4:Recursively apply the Quick Sort algorithm to the less and greater sub-arrays.

STEP5:Combine the sorted less, equal, and sorted greater sub-arrays.

STEP6:Return the combined array as the sorted result.

STEP7:Stop the program

# PROGRAM:
```
DEVELOPED BY:SWATHI D
REGISTER NUMBER:212222230154
```
```
import random
def qs(nums,l,r):
    if(r<=l):
        return
    a=i=l
    j=r
    pivot=nums[l]
    while i<=j:
        if nums[i]<pivot:
            nums[a],nums[i]=nums[i],nums[a]
            i+=1
            a+=1
        elif nums[i]>pivot:
            nums[j],nums[i]=nums[i],nums[j]
            j-=1
        else:
            i+=1
    qs(nums,l,a-1)
    qs(nums,j+1,r)
            

n=int(input())
nums=[int(input()) for i in range(n)]
pi=random.randrange(0,n)
nums[pi],nums[0]=nums[0],nums[pi]
qs(nums,0,n-1)
print(nums)
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/60a46348-bcbb-4fcf-9e3d-56b32fc56554)

# RESULT:
Thus, the program was successfully executed and the given array was sorted using Quick Sort with a random pivot.




