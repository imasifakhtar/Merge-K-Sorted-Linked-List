# Merge K Sorted Linked List Using Min Heap Visualization

This solution is based on the MIN HEAP approach used to solve the problem ‘merge k sorted arrays.

A Min-Heap is a complete binary tree in which the value in each internal node is smaller than or equal to the values in the children of that node. Mapping the elements of a heap into an array is trivial: if a node is stored at index k, then its left child is stored at index 2k + 1 and its right child at index 2k + 2.

- Create a min-heap and insert the first element of all the ‘k’ linked lists.
- As long as the min-heap is not empty, perform the following steps:
    * Remove the top element of the min-heap (which is the current minimum among all the elements in the min-heap) and add it to the result list.
    * If there exists an element (in the same linked list) next to the element popped out in previous step, insert it into the min-heap.
- Return the head node address of the merged list.
## Screenshots

* Home:
![App Screenshot](https://i.ibb.co/vcbyrTH/merge01.png)


* Result Page:
![App Screenshot](https://i.ibb.co/g6HrZtS/merge02.png)
