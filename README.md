# quicksort
Repeatedly partitions the input into low and high parts, and then recursively sorts each of those parts.  
To partition the input, quicksort chooses a pivot to divide the data into low and high parts.  
The pivot can be any value within the array being sorted, commonly the value of the middle array element.  
All values in the low partition are less than or equal to the pivot value, while all values in the high partition are greater than or equal to the pivot value.  Partitioning moves the values to their appropriate partition.

The quicksort function is called recursively on the low and high partitions until the entire array is sorted.

Assuming the pivot always divides the array into equal partitions (BEST CASE), the number of partition levels, L, is:  
$`\log_{2}N = L`$

Assuming the pivot always selects pivot with only one element in partition (WORST CASE), partition levels:  
L = N - 1

## Time Complexity
### Best Case
O(nlogn)  
Ω(nlogn)  
Θ(nlogn)  

### Average Case
O(nlogn)  
Ω(nlogn)  
Θ(nlogn)  

### Worst Case
O(n^2)  
Ω(n^2)  
Θ(n^2)  
