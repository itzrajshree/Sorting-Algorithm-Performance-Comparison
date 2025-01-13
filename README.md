# **Sorting Algorithm Performance Comparison**

## Overview
This project compares the performance of three common sorting algorithms: **Merge Sort**, **Quick Sort**, and **Heap Sort**. The comparison is based on the number of inputs and the execution time of each algorithm in C.

The algorithms are implemented in C, and the performance metrics (execution time) are measured for varying input sizes to provide insights into the efficiency and speed of each sorting method.

---

## **Algorithms Implemented**

### **Merge Sort**
Merge Sort is a divide-and-conquer algorithm that splits the array into two halves, sorts them recursively, and then merges the sorted halves. It has a time complexity of \( O(n \log n) \).

### **Quick Sort**
Quick Sort is also a divide-and-conquer algorithm. It picks a pivot element, partitions the array around the pivot, and recursively sorts the subarrays. Its average time complexity is \( O(n \log n) \), but in the worst case, it can degrade to \( O(n^2) \).

### **Heap Sort**
Heap Sort is based on a binary heap data structure. It builds a max-heap from the array and then repeatedly extracts the maximum element to build the sorted array. The time complexity of Heap Sort is \( O(n \log n) \).

---

## **Objective**
The objective of this project is to compare the execution times of the three sorting algorithms for different input sizes. We will evaluate the time complexity and performance based on the number of elements sorted.

---

## **Project Structure**

- `merge_sort.c`: Implementation of the Merge Sort algorithm.
- `quick_sort.c`: Implementation of the Quick Sort algorithm.
- `heap_sort.c`: Implementation of the Heap Sort algorithm.
- `compare_sorts.jpg`: An image of the graph comparing the performance of Merge Sort, Quick Sort, and Heap Sort for different input sizes and execution times.
- `README.md`: This README file.

---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
