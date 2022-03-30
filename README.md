# BubbleSort

### Implemented the Bubble Sort algorithm that takes an array of integers and sorts them from smallest to largest.

### In the bubbleSort() method, we have a while loop that runs the swapping logic until the array is fully sorted. Inside the while loop, we have a for loop that iterates through the array and checks whether adjacent elements are out of order. If so, we swap the first instance of two adjacent elements that are out of order. The swapping is done using a helper function. If we swapped, we signal to the while loop that we may need another look through the array, so the loop runs once again. The loop stops running after there are no two adjacent elements that are out of order.