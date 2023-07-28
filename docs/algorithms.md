# Awesome List of Algorithms every Programmer should know

## Table of Contents

1. **Sorting Algorithms**

   - Bubble Sort
   - Selection Sort
   - Insertion Sort
   - Quick Sort
   - Merge Sort
   - Heap Sort
   - Counting Sort
   - Radix Sort

2. **Search Algorithms**
   - Linear Search
   - Binary Search

3. **Graph Algorithms**
   - Depth-First Search (DFS)
   - Breadth-First Search (BFS)
   - Dijkstra's Algorithm
   - A* Search Algorithm
   - Floyd-Warshall Algorithm
   - Prim's Algorithm
   - Kruskal's Algorithm

4. **String Algorithms**
   - Naive String Search
   - Rabin-Karp Algorithm
   - Knuth-Morris-Pratt (KMP) Algorithm
   - Z Algorithm
   - Boyer-Moore Algorithm

5. **Tree Algorithms**
   - Binary Tree Traversal (In-order, Pre-order, Post-order)
   - Binary Search Tree Operations (Insertion, Deletion, Search)
   - AVL Tree (Balanced Binary Search Tree)
   - Segment Tree
   - Fenwick Tree (Binary Indexed Tree)

6. **Dynamic Programming**
   - Longest Common Subsequence
   - Shortest Path Faster Algorithm (SPFA)
   - Travelling Salesman Problem
   - 0/1 Knapsack Problem
   - Edit Distance

7. **Greedy Algorithms**
   - Activity Selection Problem
   - Huffman Coding
   - Job Sequencing Problem

8. **Hashing Algorithms**
   - Direct Addressing
   - Open Hashing (Separate Chaining)
   - Closed Hashing (Open Addressing)

9. **Cryptography Algorithms**
   - Caesar Cipher
   - RSA Algorithm
   - Diffie-Hellman Key Exchange
   - AES Encryption

10. **Geometric Algorithms**
    - Line Intersection
    - Convex Hull (Graham's Scan Algorithm)
    - Closest Pair of Points

## Sorting Algorithms

| Sorting Algorithm | Description | Time Complexity (Best) | Time Complexity (Average) | Time Complexity (Worst) | Inventor |
| --- | --- | --- | --- | --- | --- |
| Bubble Sort | It's a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order. | O(n) | O(n²) | O(n²) | - |
| Selection Sort | This algorithm divides the list into a sorted and an unsorted region. It repeatedly selects the smallest (or largest) element from the unsorted region and moves it to the end of the sorted region. | O(n²) | O(n²) | O(n²) | - |
| Insertion Sort | It's a simple sorting algorithm that builds the final sorted list one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort. | O(n) | O(n²) | O(n²) | - |
| Quick Sort | It's an efficient sorting algorithm that uses the divide-and-conquer technique to divide a list into two sub-lists. | O(n log(n)) | O(n log(n)) | O(n²) | Tony Hoare |
| Merge Sort | It's an efficient sorting algorithm that uses the divide-and-conquer technique to divide a list into two sub-lists. | O(n log(n)) | O(n log(n)) | O(n log(n)) | John von Neumann |
| Heap Sort | It's a comparison-based sorting algorithm. It divides its input into a sorted and an unsorted region, and it iteratively shrinks the unsorted region by extracting the largest element and moving that to the sorted region. | O(n log(n)) | O(n log(n)) | O(n log(n)) | J. W. J. Williams |
| Counting Sort | It's a sorting algorithm that sorts the elements by counting the number of occurrences of each unique element, and then writing those counts out to output. | O(n + k) | O(n + k) | O(n + k) | Harold H. Seward |
| Radix Sort | It's a non-comparative sorting algorithm that sorts data with integer keys by grouping keys by the individual digits which share the same significant position and value. | O(nk) | O(nk) | O(nk) | - |

Note:

- n is the number of items to sort
- k is the range of data
- nk is the number of digits or bits needed to represent the largest number in the list to sort.

## Search Algorithms

Sure, here is a markdown table detailing the information about the search algorithms you mentioned:

| Search Algorithm | Description | Time Complexity (Best) | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity | Inventor |
| --- | --- | --- | --- | --- | --- | --- |
| Linear Search | It's a simple search algorithm that checks every element in the list until it finds the target value. | O(1) | O(n) | O(n) | O(1) | - |
| Binary Search | It's an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one. | O(1) | O(log n) | O(log n) | O(1) | -

Note:

- n is the number of items in the list
- O(1) space complexity means that the space required by the algorithm is constant, i.e., it does not change with the size of the input.

## Graph Algorithms

| Graph Algorithm | Description | Time Complexity | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- |
| Depth-First Search (DFS) | An algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root and explores as far as possible along each branch before backtracking. | O(V + E) | O(V) | Topological Sorting, Detecting cycle, Path Finding | -
| Breadth-First Search (BFS) | An algorithm for traversing or searching tree or graph data structures. It starts at the tree root and explores all of the neighbor nodes at the present depth prior to moving on to nodes at the next depth level. | O(V + E) | O(V) | Shortest Path in simple graph, Peer to Peer Networks | -
| Dijkstra's Algorithm | An algorithm for finding the shortest paths between nodes in a graph, which may represent, for example, road networks. | O((V+E) log V) | O(V) | Shortest paths in graph, GPS Navigation | Edsger W. Dijkstra |
| A* Search Algorithm | A pathfinding algorithm widely used in pathfinding and graph traversal, the process of plotting an efficiently traversable path between multiple points, called nodes. | O(E) | O(V) | Pathfinding in Maps, AI in Games | Peter Hart, Nils Nilsson, Bertram Raphael |
| Floyd-Warshall Algorithm | An algorithm for finding shortest paths in a weighted graph with positive or negative edge weights (but with no negative cycles). | O(V³) | O(V²) | All pairs shortest path, Network Routing Protocols | Robert Floyd |
| Prim's Algorithm | A greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. | O(E log V) | O(V) | Network design, Approximation algorithms | Vojtěch Jarník, Robert C. Prim |
| Kruskal's Algorithm | A greedy algorithm in graph theory that finds a minimum spanning tree for a connected weighted graph. | O(E log E) | O(V + E) | Network design, Approximation algorithms | Joseph Kruskal |

Note:

- V is the number of vertices
- E is the number of edges
- O(V) space complexity means that the space required by the algorithm is proportional to the number of vertices in the graph.

## String Algorithms

| String Algorithm | Description | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- | --- |
| Naive String Search | A simple and straightforward method for string matching. It checks all characters from the start of the text to the end for the pattern. | O(n) | O(mn) | O(1) | Simple text pattern searching | - |
| Rabin-Karp Algorithm | A string searching algorithm that uses hashing to find any one of a set of pattern strings in a text. | O(n + m) | O(nm) | O(m) | Plagiarism detection, Software for finding a given word in a document | Richard M. Karp, Michael O. Rabin |
| Knuth-Morris-Pratt (KMP) Algorithm | An algorithm that searches for occurrences of a "word" within a main "text string". It uses observations about the word to skip sections of the text, resulting in a linear time complexity. | O(n) | O(n) | O(m) | Search patterns in texts, DNA sequence analysis | Donald Knuth, Vaughan Pratt, James H. Morris |
| Z Algorithm | An algorithm which pre-processes the pattern P into an array and then uses this array to avoid unnecessary comparisons in searching. | O(n) | O(n) | O(n + m) | String matching problems | -
| Boyer-Moore Algorithm | An efficient string searching algorithm that skips sections of the text, resulting in a faster average-case performance. It is particularly effective for long patterns or large alphabets. | O(n/m) | O(mn) | O(m) | Text editor "find" features, Virus scanning | Robert S. Boyer, J Strother Moore |

Note:

- n is the length of the text
- m is the length of the pattern
- O(1) space complexity means that the space required by the algorithm is constant, i.e., it does not change with the size of the input.

## Tree Algorithms

| Tree Algorithm | Description | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- | --- |
| Binary Tree Traversal (In-order, Pre-order, Post-order) | Algorithms for visiting each node in a tree data structure, exactly once. They differ in the order in which nodes are visited. | O(n) | O(n) | O(n) | Parsing trees, Expression handling, Sorting | - |
| Binary Search Tree Operations (Insertion, Deletion, Search) | Algorithms for managing a sorted binary tree data structure. It allows for fast lookup, addition, and removal of items. | O(log n) | O(n) | O(n) | Database indexing, Priority queues | - |
| AVL Tree (Balanced Binary Search Tree) | A self-balancing binary search tree, and it was the first such data structure to be invented. In an AVL tree, the heights of the two child subtrees of any node differ by at most one. | O(log n) | O(log n) | O(n) | Database indexing, Memory management | G. M. Adelson-Velsky and E. M. Landis |
| Segment Tree | A tree data structure for storing intervals or segments. It allows querying which of the stored segments cover a given point. | O(log n) | O(log n) | O(n) | Range minimum query, Range sum query, Range add query | - |
| Fenwick Tree (Binary Indexed Tree) | A data structure providing efficient methods for calculation and manipulation of the prefix sums of a table of values. | O(log n) | O(log n) | O(n) | Cumulative frequency tables, Range sum queries | Peter M. Fenwick |

Note:

- n is the number of nodes in the tree
- O(n) space complexity means that the space required by the algorithm is proportional to the number of nodes in the tree.

## Dynamic Programming

| Dynamic Programming Problem | Description | Time Complexity | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- |
| Longest Common Subsequence | Given two sequences, this algorithm finds the longest subsequence present in both of them. | O(mn) | O(mn) | Bioinformatics (DNA sequence alignment), Version control systems | -
| Shortest Path Faster Algorithm (SPFA) | An improvement of the Bellman-Ford algorithm which computes single-source shortest paths in a weighted directed graph. | O(kE) | O(V) | Routing protocols, AI in games | Fanding Duan |
| Travelling Salesman Problem | Given a list of cities and the distances between each pair of cities, this problem is to find the shortest possible route that visits each city exactly once and returns to the origin city. | O(n² * 2ⁿ) | O(n * 2ⁿ) | Logistics, DNA sequencing, Manufacturing of printed circuit boards | -
| 0/1 Knapsack Problem | Given weights and values of n items, this problem is to put these items in a knapsack of capacity W to get the maximum total value in the knapsack. | O(nW) | O(nW) | Resource allocation, Budgeting, Construction and project management | -
| Edit Distance | Given two strings str1 and str2 and operations (insert, remove, replace), this problem is to convert str1 into str2 with minimum number of operations. | O(mn) | O(mn) | Spell checking, DNA sequence alignment | Vladimir Levenshtein |

Note:

- n is the number of items or nodes
- m is the length of the string or number of characters
- E is the number of edges in the graph
- V is the number of vertices in the graph
- W is the capacity of the knapsack
- k is the average number of times each node is relaxed.

## Greedy Algorithms

| Greedy Algorithm | Description | Time Complexity | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- |
| Activity Selection Problem | Given a set of activities with start and finish times, the problem is to select the maximum number of activities that can be performed by a single person, assuming that a person can only work on a single activity at a time. | O(n log n) | O(n) | Scheduling problems, Resource allocation | - |
| Huffman Coding | An algorithm used for lossless data compression. The frequency of occurrence of various characters in the data is used to build a prefix tree where the most frequent character gets the smallest code and the least frequent character gets the largest code. | O(n log n) | O(n) | Data compression, JPEG image compression | David A. Huffman |
| Job Sequencing Problem | Given an array of jobs where every job has a deadline and associated profit if the job is finished before the deadline. It is also given that every job takes a single unit of time, so the minimum possible deadline for any job is 1. The problem is to find the maximum profit subset of jobs that can be done considering the deadlines. | O(n²) | O(n) | Scheduling problems, Resource allocation | - |

Note:

- n is the number of items or nodes
- O(n) space complexity means that the space required by the algorithm is proportional to the number of items or nodes.

## Hashing Algorithms

| Hashing Algorithm | Description | Time Complexity (Average) | Time Complexity (Worst) | Space Complexity | Use Case |
| --- | --- | --- | --- | --- | --- |
| Direct Addressing | A technique that uses an array where each index corresponds to a key in the universe of possible keys. The value at that index in the array is the value associated with the key. | O(1) | O(1) | O(u) | When the universe of keys is reasonably small |
| Open Hashing (Separate Chaining) | A method for handling collisions. In this method, each bucket is independent, and has some sort of list of entries with the same index. | O(1) | O(n) | O(n) | When the distribution of keys is non-uniform |
| Closed Hashing (Open Addressing) | A method for handling collisions. In this method, all elements are stored in the hash table itself. When a table slot is filled, the next (or the next after that, if it is also full, etc.) slot is used. | O(1) | O(1) | O(n) | When space is at a premium and slight overhead in time is acceptable |

Note:

- n is the number of keys
- u is the size of the universe of keys
- O(1) time complexity means that the time required by the algorithm is constant, i.e., it does not change with the size of the input.
- O(n) space complexity means that the space required by the algorithm is proportional to the number of keys.

## Cryptography Algorithms

| Cryptography Algorithm | Description | Key Size | Use Case | Inventor |
| --- | --- | --- | --- | --- |
| Caesar Cipher | A type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet. | Not applicable (shift value used as key) | Basic encryption, Learning purposes | Julius Caesar |
| RSA Algorithm | An algorithm used in public key cryptography that is based on the presumed difficulty of factoring large integers, the factoring problem. | 1024 to 4096 bits (commonly 2048 bits) | Secure data transmission, Digital signatures | Ron Rivest, Adi Shamir, and Leonard Adleman |
| Diffie-Hellman Key Exchange | A method of securely exchanging cryptographic keys over a public channel. | 1024 to 2048 bits (commonly 2048 bits) | Secure key exchange over public channels, Secure communications | Whitfield Diffie and Martin Hellman |
| AES Encryption | A symmetric encryption algorithm that uses the same key for both the encryption and decryption processes. | 128, 192, or 256 bits | Secure data storage, Secure communications | Vincent Rijmen, Joan Daemen |

Note:

- The key size is the size of the key used in the cryptographic algorithm. Larger key sizes are more secure, but also slower.

## Geometric Algorithms

| Geometric Algorithm | Description | Time Complexity | Space Complexity | Use Case | Inventor |
| --- | --- | --- | --- | --- | --- |
| Line Intersection | An algorithm to find the point at which two lines intersect, if they do. | O(1) | O(1) | Computer graphics, Geographic Information Systems (GIS) | - |
| Convex Hull (Graham's Scan Algorithm) | An algorithm for computing the convex hull of a finite set of points in the plane with time complexity O(n log n). | O(n log n) | O(n) | Collision avoidance, Shape analysis, Image recognition | Ronald Graham |
| Closest Pair of Points | An algorithm to find the closest pair of points in a set of points in the Euclidean plane. | O(n log n) | O(n) | Geographic Information Systems (GIS), Computer graphics, Pathfinding | -

Note:

- n is the number of points
- O(1) time complexity means that the time required by the algorithm is constant, i.e., it does not change with the size of the input.
- O(n) space complexity means that the space required by the algorithm is proportional to the number of points.
