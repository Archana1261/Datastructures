#AIM OF THE EXPERIMENT: To find an element in array using linear search with recursion.

##DESCRIPTION: We have to write a c peogram to find whether the element is present in an array or not by using Reclinearsearch function and to find out the position of the element in the array.

### STEP BY STEP PROCEDURE:
1. Declare the function Reclinearsearch with 4 input parameters and return position of an element which is searched by the user.
2. Create an array and input the elements of the array and scan the value of the key element to be found.
3. The idea is to compare the key with the first elementin a[].If the element is found at first position return it.
4. Else recur for the remaining array and the key value.
4. If the element is found it prints the value of the index at which key element is found.otherwise,it prints the element is not found.

output 1(if the input is 66) : When the user inputs the key value to be searched as 66,then the out put is obtained as the search is successful at position 8.

![output 1](linear_search_recursion.1.PNG)

output 2(if the input is 0) : When the user inputs the key value to be searched as 0,then the out put is obtained as the search is unsuccessful.

![output 2](linear_search_recursion.2.PNG)
