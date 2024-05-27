# 4-Gallon-Bucket-Problem
The objective of this project is to develop a program that can solve the problem of 2 kids fetching 4 gallons of water from a stream, using only an unmarked 3-gallon bucket, and an unmarked 5-gallon bucket, in less than 15 steps.


deque (double-ended queue)
a data structure provided by the collections module in Python, optimized for fast adding and removing operations from both ends. deque is particularly useful in scenarios requiring quick insertions and deletions of elements, especially for implementing data structures like queues and stacks.


In this project, we use the Breadth-First Search (BFS) algorithm to explore all possible configurations of the water buckets. BFS typically employs a queue to manage the states waiting to be explored. With deque, we can efficiently remove the current state from the front of the queue (using the popleft() method) and add new states to the back of the queue (using the append() method). This ensures the FIFO (First In, First Out) characteristic of BFS.
