# Time-Complexity

# 1.	Arrays:
•	Time Complexity:
•	Access: O(1)
•	Search: O(n)
•	Insertion/Deletion (at end): O(1)
•	Insertion/Deletion (at a specific index): O(n)
•	Space Complexity: O(n)
# 2.	Dynamic Arrays (ArrayList in Java):
•	Time Complexity:
•	Access: O(1)
•	Search: O(n)
•	Insertion/Deletion (at end): O(1) (amortized)
•	Insertion/Deletion (at a specific index): O(n)
•	Space Complexity: O(n)
# 3.	Linked Lists:
•	Time Complexity:
•	Access: O(n)
•	Search: O(n)
•	Insertion/Deletion (at beginning): O(1)
•	Insertion/Deletion (at end): O(1) (if using a reference to the tail)
•	Insertion/Deletion (at a specific node): O(1) (if the node is given)
•	Space Complexity: O(n)
# 4.	Stacks (java.util.Stack):
•	Time Complexity:
•	Access (top element): O(1)
•	Push (Insertion): O(1)
•	Pop (Deletion): O(1)
•	Space Complexity: O(n)
# 5.	Queues (java.util.LinkedList or java.util.ArrayDeque):
•	Time Complexity:
•	Access (front element): O(1)
•	Enqueue (Insertion): O(1)
•	Dequeue (Deletion): O(1)
•	Space Complexity: O(n)
# 6.	Hash Tables (HashMap in Java):
•	Time Complexity:
•	Average-case Access/Search/Insertion/Deletion: O(1) (constant time)
•	Worst-case Access/Search/Insertion/Deletion: O(n) (due to hash collisions)
•	Space Complexity: O(n)
•	
# 7.	Heaps (Binary Min/Max Heaps):
•	Time Complexity:
•	Access (Minimum/Maximum): O(1)
•	Insertion: O(log n)
•	Deletion: O(log n)
•	Space Complexity: O(n)
# 8.	Priority Queues (java.util.PriorityQueue):
•	Time Complexity:
•	Access (Minimum/Maximum): O(1)
•	Insertion: O(log n)
•	Deletion: O(log n)
•	Space Complexity: O(n)
# 9.	Binary Search Trees (BST):
•	Time Complexity:
•	Search: O(log n) on average, O(n) worst-case (for unbalanced trees)
•	Insertion: O(log n) on average, O(n) worst-case (for unbalanced trees)
•	Deletion: O(log n) on average, O(n) worst-case (for unbalanced trees)
•	Space Complexity: O(n)
# 10.	Balanced Binary Search Trees (e.g., AVL Trees, Red-Black Trees):
•	Time Complexity:
•	Search: O(log n)
•	Insertion: O(log n)
•	Deletion: O(log n)
•	Space Complexity: O(n)
# 11.	Graphs (Adjacency Matrix and Adjacency List representations):
•	Time Complexity:
•	Access (Edge): O(1) for Adjacency Matrix, O(degree of the vertex) for Adjacency List
•	Search (Traversal): O(V + E) (V: number of vertices, E: number of edges)
•	Insertion/Deletion (Edge): O(1) for Adjacency Matrix, O(degree of the vertex) for Adjacency List
•	Space Complexity: O(V + E) for both representations
# 12.	Tries:
•	Time Complexity:
•	Access/Search/Insertion/Deletion: O(k), where 'k' is the length of the key
•	Space Complexity: O(n * k), where 'n' is the number of keys and 'k' is the average key length
# 13.	B-Trees:
•	Time Complexity:
•	Search/Insertion/Deletion: O(log n) (for balanced B-trees)
•	Space Complexity: O(n)
# 14.	Skip Lists:
•	Time Complexity:
•	Search/Insertion/Deletion: O(log n) (expected time complexity)
•	Space Complexity: O(n)
# 15.	Java Collection Framework:
•	Java Collection Framework provides various classes/interfaces for data structures like ArrayList, LinkedList, HashSet, HashMap, TreeSet, TreeMap, etc., and their time and space complexities are based on the data structure they implement.
Please note that these complexities represent typical cases and that real-world performance can be influenced by various factors such as data distribution, data size, hardware, and specific implementations of the data structures and algorithms. Additionally, some advanced data structures have different time complexities depending on their specific use cases and optimizations.

