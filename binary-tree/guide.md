

https://leetcode.com/tag/binary-tree/discuss/1212004/Binary-Trees-study-guide



**Prerequisites** that you should be familiar with before : *Recursion, stack, queue*



A basic instinct for solving DFS based questions is to do a recursive call and for all BFS(level order traversal) is to make queue and iterate, but also think upon how to iterate in DFS(Hint think on stack) and recurse in BFS based.



First of all you should look at **traversal problems**:



1. [Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal)
2. [Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal)
3. [PostOrder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal)
4. [Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal)



A variation for LevelOrder can be: [ZigZag level order traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) and [Binary Tree Level Order Traversal II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)
Solving these questions will help you get familiarized with basic btree dfs and bfs traversals.



**Intuition for Level Order Traversal** iteratively using queue:



- Construct a queue of type: TreeNode `queue<TreeNode* > q`, initially push the given root in it.
- Iterate through the queue until empty:
  - Store the current size of queue `tempSize`, this will be the size of the current level of the tree.
  - Now we need to traverse this level so iterate for `tempSize>=0` :
    - Pop the current element and apply the needed operation for the same and if left or right child exist then pass them to the queue.



Now, some basic Binary Tree problems that will help your thinking process:



1. [Same Tree](https://leetcode.com/problems/same-tree/)
2. [Symmetric Tree](https://leetcode.com/problems/symmetric-tree/)
3. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
4. [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)
5. [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/)
6. [Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees)
7. [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)
8. [Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt)
9. [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)



**Binary Search Tree:** Use the property of BST judiciously (the left subtree will always contain nodes with value less than root's value and right subtree will contain nodes with value greater than root's value)



1. [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree)
2. [Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/)
3. [Minimum Absolute Difference in BST](https://leetcode.com/problems/minimum-absolute-difference-in-bst/)
4. [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/)
5. [Delete Node in a BST](https://leetcode.com/problems/delete-node-in-a-bst/)
6. [Trim a Binary Search Tree](https://leetcode.com/problems/trim-a-binary-search-tree)
7. [Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree)
8. [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst)
9. [All Elements in Two Binary Search Trees](https://leetcode.com/problems/all-elements-in-two-binary-search-trees)



**Path problems:** You are given root, you have to perform operations on a path, (path is root to leaf). Think upon the type of traversal you will apply when going from root to leaf:



1. [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths/)
2. [Path Sum](https://leetcode.com/problems/path-sum)
3. [Path Sum II](https://leetcode.com/problems/path-sum-ii)
4. [Sum root to leaf numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
5. [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
6. *[Path Sum III](https://leetcode.com/problems/path-sum-iii)
7. *[Pseudo-Palindromic Paths in a Binary Tree](https://leetcode.com/problems/pseudo-palindromic-paths-in-a-binary-tree)
   *Last two problems here are utmost important



Next is, given a combination of preorder, postorder and inorder traversals, you need to **construct a binary tree/BST**:
Hint: Observe in each traversal method, position of root and head of right and left subtrees



1. [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal)
2. [Construct Binary Tree from Inorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal)
3. [Construct Binary Tree from Preorder and Postorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal)
4. [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree)
5. [Construct Binary Search Tree from Preorder Traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal)



**View problems:** Try thinking for left, bottom and top too!
[Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view)



**Lowest Common Ancestor problems:** You are given two nodes and you have to return their ancestor at as least depth possible, these are problems are a must todo:



1. [Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree)
2. [Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree)
3. [Lowest Common Ancestor of Deepest Leaves](https://leetcode.com/problems/lowest-common-ancestor-of-deepest-leaves)



**Validate trees:**



1. [Validate Binary Tree Nodes](https://leetcode.com/problems/validate-binary-tree-nodes/)
2. [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)



Some **miscellaneous** problems that you should definitely look through:



1. [Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list)
2. [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes/)
3. [Maximum Width of Binary Tree](https://leetcode.com/problems/maximum-width-of-binary-tree)
4. [Check Completeness of a Binary Tree](https://leetcode.com/problems/check-completeness-of-a-binary-tree)
5. [Cousins in Binary Tree](https://leetcode.com/problems/cousins-in-binary-tree)
6. [Maximum Difference Between Node and Ancestor](https://leetcode.com/problems/maximum-difference-between-node-and-ancestor)
7. [Number of Good Leaf Nodes Pairs](https://leetcode.com/problems/number-of-good-leaf-nodes-pairs)
8. [Smallest Subtree with all the Deepest Nodes](https://leetcode.com/problems/smallest-subtree-with-all-the-deepest-nodes/)
9. [All Nodes Distance K in Binary Tree](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/)
10. [Find a Corresponding Node of a Binary Tree in a Clone of That Tree](https://leetcode.com/problems/find-a-corresponding-node-of-a-binary-tree-in-a-clone-of-that-tree/)
11. [Vertical Order Traversal of a Binary Tree](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/)



I will be updating this list on finding more important questions or any pattern that I find.