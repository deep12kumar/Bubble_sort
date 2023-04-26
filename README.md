# Bubble_sort

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order. This algorithm is not suitable for large data sets as its average and worst-case time complexity is quite high.

![image](https://user-images.githubusercontent.com/125429608/234470125-0673c332-4e6b-40b3-9a23-9d63cf6de85d.png)

Input: arr[] = {6, 3, 0, 5}

First Pass: 

Bubble sort starts with very first two elements, comparing them to check which one is greater.
( 6 3 0 5 ) –> ( 3 6 0 5 ), Here, algorithm compares the first two elements, and swaps since 6 > 3. 
( 3 6 0 5 ) –>  ( 3 0 6 5 ), Swap since 6 > 0 
( 3 0 6 5 ) –>  ( 3 0 5 6 ), Swap since 6 > 5 

Second Pass: 

Now, during second iteration it should look like this:
( 3 0 5 6 ) –>  ( 0 3 5 6 ), Swap since 3 > 0 
( 0 3 5 6 ) –>  ( 0 3 5 6 ), No change as 5 > 3 
Third Pass: 

Now, the array is already sorted, but our algorithm does not know if it is completed.
The algorithm needs one whole pass without any swap to know it is sorted.
( 0 3 5 6 ) –>  ( 0 3 5 6 ), No change as 3 > 0 
Array is now sorted and no more pass will happen.
