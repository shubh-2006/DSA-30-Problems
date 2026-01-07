<img width="112" height="20" alt="image" src="https://github.com/user-attachments/assets/c55988b9-d92a-4158-8c68-c7edc98f5207" />

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

You are given the head of a singly linked-list. The list can be represented as:

L0 → L1 → … → Ln - 1 → Ln

Reorder the list to be on the following form:

L0 → Ln → L1 → Ln - 1 → L2 → Ln - 2 → …
You may not modify the values in the list's nodes. Only nodes themselves may be changed.

 

Example 1:

<img width="422" height="222" alt="image" src="https://github.com/user-attachments/assets/64a2cfc0-019c-49d6-8a25-a7fa4c95d603" />



Input: head = [1,2,3,4]

Output: [1,4,2,3]

Example 2:

<img width="542" height="222" alt="image" src="https://github.com/user-attachments/assets/ef1a5836-9ac4-4596-b61d-32683fb7a01b" />


Input: head = [1,2,3,4,5]

Output: [1,5,2,4,3]
 

Constraints:

The number of nodes in the list is in the range [1, 5 * 104].

1 <= Node.val <= 1000
