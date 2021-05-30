# RUBEGOLDBERGMACHINE
A Rube Goldberg Machine is a complex device that performs simple tasks in indirect and convoluted ways. We were to create a virtual Rube Goldberg  Machine with ADTs like Dynamic Arrays, Queue, Stack, and Binary tree. Our program can support any number of entries. The data is read from a file and initially stored in a queue. It is then passed on to stacks and linked lists for  further operations to be executed The data structures we selected are:  1. Arrays  2. Queue  3. Stack  4. Binary tree 
Working of the program: 
Each ADT is concerned we have the following functions: 

LinkedList: 
A linked list is a linear data structure, in which the elements are not stored at contiguous memory locations. It is a data structure consisting of a collection of nodes that together represent a sequence. It consists of nodes where each node contains a data field and a reference(link) to the next node in the list. This structure allows for efficient insertion or removal of elements from any position in the sequence during iteration.

LinkedList(): A constructor that initializes the head to NULL,  changeHead(): Used to change the head to a given pointer, setData(): It will save new data(name, age, dob) in a new node, firstNode(): Used for creating the first node, Prepend(): Adds a new node in the front of the list, Append(): Adds a new node at the end of the list, Pop(): Removes an element from the list, popFirst(): Used to pop the head from the list, sizeVal(): Returns the size of the list, HeadVal():  Returns a pointer to the head of the list. 
Stack:
 Stacks are Abstract Data Types that operate in a last in first out (LIFO) or first in last out (FILO) type of arrangement. The elements are inserted to the top and are deleted from the top as well. The simplest example to understand stacks is a pile of plates (stacked one another). The plate which is on top (last added to stack) is the first to be removed.

Push(): Pushes a new element in the stack. There are two push functions, one will take the data as an argument and add it to a new node, another will take a node as an argument, and at it to the stack. Pop(): Pops the topmost element in the stack,  sizeVal(): Returns the size of the stack, HeadVal(): Returns a pointer to the head of the stack. 

Time Complexity:
Push: O(1)
Pop: O(1)

Queue: 
Queues are Abstract Data Types that operate in a first in first out (FIFO) type of
arrangement. Elements are inserted at the back(end) and are deleted from the front.

Enqueue(): Used to add a new element in the queue. There are two enqueue functions, one will take the data as an argument and add it to a new node, another will take a node as an argument and at it to the queue, Dequeue(): Used to remove a queue element, sizeVal(): Returns the size of the queue, HeadVal(): Returns a pointer to the head of the queue, Disp(): Prints the queue. 

Time Complexity: 
Dequeue: O(1)
Enqueue: O(1)

BinaryTree: 
A tree whose elements have at most 2 children is called a binary tree. Since each element in a binary tree can have only 2 children, we typically name them the left and right child.
Each node contains three components:
Pointer to the left subtree
Pointer to the right subtree
Data element
The topmost node in the tree is called the root. An empty tree is represented by the NULL pointer.
newNode(): Creates a new tree node, traversePreOrder(): Recursive  function for preorder traversal, traverseInOrder(): Recursive function for inorder  traversal, traversePostOrder(): Recursive function for postorder traversal,
InsertNode(): Inserts a new node. 

Time Complexity for traversals: O(n)
Complexity function T(n) — for all problem where tree traversal is involved — can be defined as:
T(n) = T(k) + T(n – k – 1) + c
Where k is the number of nodes on one side of the root and n-k-1 on the other side.

Other functions include: Partition(): Partitions the list taking the last element as the pivot, quickSortRecur(): Quick sort function using recursion, quickSort(): The main function for quicksort which calls the quickSortRecur function. This is a wrapper over the recursive function. 

Time Complexity:
Quick Sort: O(n2 )
How to use our program? 
1. Firstly, the input given by the user is read from a file and stored in a  queue. The user is asked to press any key to read the data. Once this is initiated, the data is then displayed and hence the input is successfully stored. 
2. To dequeue each element from the queue the user is asked to press any key this will proceed with the program. Accordingly, the dequeued data is displayed. To continue the processing the user is then asked to press any key. 
3. Now reversing the order of the data in the queue is done by dequeuing each element and pushing them onto a stack. The user is asked to press any key to dequeue and push the elements to stack. The user should press any key for the reverse order of the stack to be printed. 
4. After the reversed data is printed, the user is asked to press any key to pop off and requeue data one after the other. The popped elements are then printed.
5. To continue the operations, when the user again presses any key, the data from the queue is placed into an unordered binary tree. The contents of the tree are then printed in Pre-Order. 
6. The user is then asked to press any key, which results in printing the contents of the tree in the Post-Order. 
7. The user will be then asked to press any key to pull the contents from the tree and push it to a Linked–List using In-Order traversal. The contents of linked lists are then printed. 
8. The user is asked to press any key to sort the contents of the list using a quick sort and printing it according to the birth year. 9. The contents of the list are printed and the user is asked to press any key to continue the processing. At this point, the user is done with the processing. 
10. The user is asked to press 0 to final exit the program after all processing is done successfully.


Prason Sood (RA1911003010059)
