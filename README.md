# holbertonschool-binary_trees
Objectives
What is a binary tree
What is the possible gain in terms of time complexity compared to linked lists
what are the depth, the height, the size of a binary tree
What are the different traversal methods to go through a binary tree
What is a complete, a full, a perfect, a balanced binary tree
General requirements
Global variables are not allowed
C standard library is allowed
No more than 5 functions per file
Header file should be called binary_trees.h
Typedef data structures provided: binary_tree_t
Data Structures to Use for Project
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
