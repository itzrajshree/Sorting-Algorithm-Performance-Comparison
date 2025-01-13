**Sorting Algorithm Performance Comparison**

Overview
This project compares the performance of three common sorting algorithms: Merge Sort, Quick Sort, and Heap Sort. The comparison is based on the number of inputs and the execution time of each algorithm in C.

The algorithms are implemented in C, and the performance metrics (execution time) are measured for varying input sizes to provide insights into the efficiency and speed of each sorting method.

**Algorithms Implemented**
Merge Sort
Merge Sort is a divide-and-conquer algorithm that splits the array into two halves, sorts them recursively, and then merges the sorted halves. It has a time complexity of 
𝑂(𝑛 log𝑛).

Quick Sort
Quick Sort is also a divide-and-conquer algorithm. It picks a pivot element, partitions the array around the pivot, and recursively sorts the subarrays. Its average time complexity is 𝑂(𝑛 log𝑛), but in the worst case, it can degrade to 𝑂(𝑛^2).

Heap Sort
Heap Sort is based on a binary heap data structure. It builds a max-heap from the array and then repeatedly extracts the maximum element to build the sorted array. The time complexity of Heap Sort is O(n logn).

**Objective**
The objective of this project is to compare the execution times of the three sorting algorithms for different input sizes. We will evaluate the time complexity and performance based on the number of elements sorted.

**Project Structure**
merge_sort.c: Implementation of the Merge Sort algorithm.
quick_sort.c: Implementation of the Quick Sort algorithm.
heap_sort.c: Implementation of the Heap Sort algorithm.
compare_sorts.jpg: A image of the graph, comparing the performance of Merge Sort, Quick Sort, and Heap Sort for different input sizes and execution time.
README.md: This README file.
