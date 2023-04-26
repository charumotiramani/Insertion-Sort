# Insertion-Sort
Insertion sort is based on the idea that one element from the input elements is consumed in each iteration to find its correct position i.e, the position to which it belongs in a sorted array.

It iterates the input elements by growing the sorted array at each iteration. It compares the current element with the largest value in the sorted array. If the current element is greater, then it leaves the element in its place and moves on to the next element else it finds its correct position in the sorted array and moves it to that position. This is done by shifting all the elements, which are larger than the current element, in the sorted array to one position ahead
# Characteristics of Insertion Sort:
1.This algorithm is one of the simplest algorithm with simple implementation.  
2.Basically, Insertion sort is efficient for small data values.  
3.Insertion sort is adaptive in nature, i.e. it is appropriate for data sets which are already partially sorted.

# Algorithm
The simple steps of achieving the insertion sort are listed as follows -  
Step 1 - If the element is the first element, assume that it is already sorted. Return 1.  
Step2 - Pick the next element, and store it separately in a key.  
Step3 - Now, compare the key with all elements in the sorted array.  
Step 4 - If the element in the sorted array is smaller than the current element, then move to the next element. Else, shift greater elements in the array towards the right.  
Step 5 - Insert the value.  
Step 6 - Repeat until the array is sorted.

![image](https://he-s3.s3.amazonaws.com/media/uploads/46bfac9.png)
