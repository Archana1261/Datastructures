AIM OF THE EXPERIMENT: To perform linear search on a given array(iterative linear search)

DESCRIPTION:
1. We use linear search to find whether a number is present in an array or not.
2. If it is present,then at ehat location it occurs.
3. It is also known as sequential search.
4. We compare each element with the element to be searched until we find it or the list ends

STEP BY STEP PROCEDURE:
1. We have the array elements as{10,6,8,15,20,3,14,99,66,30}.
2. The first key element that we need to check is 66.
  .In the process of iteration we check if the element and the key value that we need to be searched is same or not
  .In the iteration 1 a[0] = 10 and the key value is 66. As both are not equal and the case fails.
  .In the iteration 2 a[1] = 6 and the key value is 6.As both are not equal and the case fails.
  .In the iteration 3 a[2] = 8 and the key value is 8.As both are not equal and the case fails.
  .similarly iteration continues until the element matches with the key value.
  .In iteration 9 a[8] = 66 which is equal to the required key value.
3. In the function the iteration takes place and the element with the index prints to the outout.
4. If all the iteration cases fails then it returns the search is unsuccessful.

output 1(if the input is 66): If the key value to be found is given as 66,then it prints the search is successful at position 8.

![output 1](linear_search.1.PNG)

output 2(if the input is 0) : If the key value to be found is 0,then it prints the search is unsuccessful.

![output 2](linear_search.2.PNG)
