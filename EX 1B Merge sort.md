# EX 1B Merge Sort
## DATE:
## AIM:
To write a python program to sort the first half of the list using merge sort.

## Algorithm
1. If the array has more than one element, split it into two halves.
2. Recursively apply merge sort on both halves.
3. Compare elements of both halves and merge them into a sorted array.
4. Copy any remaining elements from the left or right half.
5. Return the fully sorted array.
## Program:
```
/*
Program to implement Merge Sort
Developed by: 212222040064
Register Number: Jeya Krishna S J  
*/
```
```
/*
def merge_sort(inp_arr):
    if len(inp_arr) < 2:
        return inp_arr
    mid = len(inp_arr) // 2
    y = merge_sort(inp_arr[:mid])
    z = merge_sort(inp_arr[mid:])
    result = []
    
    i = 0
    j= 0
    
    while i < len(y) and j < len(z):
        if y[i] > z[j]:
            result.append(z[j])
            j+=1
        else:
            result.append(y[i])
            i+=1
    result += y[i:]
    result += z[j:]
    return result

n = int(input())
inp_arr= []

for i in range(n):
    inp_arr.append(int(input()))

print("Input Array:\n")
print(inp_arr)
inp_arr=merge_sort(inp_arr)

print("Sorted Array:\n")
print(inp_arr)
*/
```
## Output:
![image](https://github.com/user-attachments/assets/5d95b1e4-5931-4603-9ec0-46897c182160)
## Result:
The program successfully sorts the first half of the given array using merge sort. where only the first half is sorted, and the second half remains unchanged.
