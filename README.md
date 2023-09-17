# Insertion Sort Algorithm
The insertion sort algorithm is a simple sorting algorithm that works by dividing the input array into two parts: a sorted subarray and an unsorted subarray. It repeatedly takes elements from the unsorted subarray and inserts them into their correct positions in the sorted subarray.

## Implementation
The insertionSort function takes an array arr as input and returns a sorted array using the insertion sort algorithm. It starts by iterating through the array from the second element (i = 1) to the last element. For each element, it compares it with the previous elements in the sorted subarray and shifts them to the right if they are greater than the current element. Finally, it inserts the current element into its correct position in the sorted subarray.