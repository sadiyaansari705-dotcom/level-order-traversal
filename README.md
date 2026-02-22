Count Total Nodes in a Binary Tree (C Program)

This project demonstrates how to count the total number of nodes in a Binary Tree using Level Order Traversal (Breadth-First Search) in C.

🧾 Program Description

The program:

Defines a Node structure containing:

data

left pointer

right pointer

Dynamically creates a binary tree using malloc().

Uses an array-based queue to perform Level Order Traversal (BFS).

Counts and prints the total number of nodes in the tree.

🌳 Example Tree Used
        1
       / \
      2   3
     / \
    4   5
🔄 Approach Used

The program uses Level Order Traversal (Breadth-First Search):

Insert root node into a queue.

Traverse the tree level by level.

For each visited node:

Increase the counter.

Insert its left and right children into the queue (if they exist).

Continue until the queue becomes empty.

🧠 Concepts Used

Binary Tree

Breadth-First Search (BFS)

Queue (Array Implementation)

Dynamic Memory Allocation (malloc)

Pointers

Structures in C

📤 Sample Output
Total Nodes = 5
⏱ Time and Space Complexity

Time Complexity: O(n)

Space Complexity: O(n) (due to queue storage)

🚀 How to Run
🔹 Compile the Program
gcc main.c -o output
🔹 Run the Program
./output

(For Windows)

output.exe
📂 Project Structure
📁 count-nodes-binary-tree
 ├── main.c
 └── README.md
⚠️ Notes

The queue size is fixed at 50 nodes.

Memory is not freed using free().

Tree is manually constructed in the program.

🔧 Possible Improvements

Implement recursive node counting method.

Dynamically allocate queue size.

Add function to free tree memory.

Take user input to create tree dynamically.

Implement other traversals (Inorder, Preorder, Postorder).

👨‍💻 Author


B.Tech Student

If you want, I can also provide:

⭐ Recursive node counting version

⭐ Complete binary tree operations program

⭐ Menu-driven tree implementation

⭐ Short lab submission version
