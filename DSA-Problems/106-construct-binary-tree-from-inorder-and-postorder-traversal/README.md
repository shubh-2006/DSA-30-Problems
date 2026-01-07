<img width="112" height="20" alt="image" src="https://github.com/user-attachments/assets/6d336aec-2397-414b-9b17-8f4a0b1f992e" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Given two integer arrays inorder and postorder where inorder is the inorder traversal of a binary tree and postorder is the postorder traversal of the same tree, construct and return the binary tree.

 

Example 1:

<img width="277" height="302" alt="image" src="https://github.com/user-attachments/assets/ae4fbaf8-e0aa-4197-b58a-55012fc4495e" />


Input: inorder = [9,3,15,20,7], postorder = [9,15,7,20,3]

Output: [3,9,20,null,null,15,7]

Example 2:

Input: inorder = [-1], postorder = [-1]

Output: [-1]
 

Constraints:

1 <= inorder.length <= 3000

postorder.length == inorder.length

-3000 <= inorder[i], postorder[i] <= 3000

inorder and postorder consist of unique values.

Each value of postorder also appears in inorder.

inorder is guaranteed to be the inorder traversal of the tree.

postorder is guaranteed to be the postorder traversal of the tree.
