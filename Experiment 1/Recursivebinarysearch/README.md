AIM OF THE EXPERIMENT: To perform binary search on a given array.

DESCRIPTION:
1. Binary search works on sorted arrays.
2. Binary search begins by comparing an element in the middle of the array with the target value.
3. If the target value is matched with the element in the array,then it returns the position of the element in the array.
4. If the target value is less than the element,the search continues in the lower half of the array.
5. If the target value is greater than the element,the search continues in the upper half of the array.
6. By doing this the algorithm eliminates the halfin which the target value can not lie in each iteration.

STEP BY STEP PROCEDURE:
1. we have the array a[10] = {10,6,8,15,20,3,14,99,66,30}
2. By sorting the array we get a[10] = {3,6,8,10,14,15,20,30,66,99}
3. Consider a key element from the given array.
4. Here the low position is 0 and the high position is 9.
5. The mid value is mid = (low + high)/2.
6. We need to compare the key value and mid value by calling the user function.
7. Here 3 cases are there
    case 1: If the mid = key element then return mid position
    case 2: If key > mid then low = mid + 1.
    case 3: If key < mid then high = mid -1.
8. We have to continue this process until we find our key element.

output 1:(key element = 6)
•	STEP 1: first index = 0, last index = 9, mid index = 4 a[4] = 14 and a[4] > 6
•	STEP 2: first index = 0 , last index = 3 ,mid value = 1 a[1] = 6 and a[1] = 6 . And here the element matches with the key value and it returns the search is successful at position 1


![output 1](binary_search_recursion.1.PNG)

output 2:(key element = 14)
•	STEP 1: first index = 0, Last index = 9 mid value = 4 a[4] = 14 and a[4] = 14 . And here the element matches with the key value and it returns the search is successful at position 4

![output 2](binary_search_recursion.2.PNG)

output 3:(key element = 99)
•	STEP 1: first index = 0, last index = 9, mid value = 4 a[4] =14 and a[4] < 99. and here the first index = mid + 1
•	STEP 2: first index = 5 , last index = 9, mid value = 7 a[7] = 30 and a[7] < 99
•	STEP 3: first index = 8, last index = 9, mid value = 8 a[8] = 66 and a[8] < 99
•	STEP 4: first index = 9, last index = 9, mid value = 9 a[9] = 99 and a[9] = 99. And here the lement matches with the key element and it returns the search is successful at position 9. 


![output 3](binary_search_recursion.3.PNG)

