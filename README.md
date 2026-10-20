# Singly Linked List – Important Tips

## 1. Understand the Structure
- A Singly Linked List consists of nodes.
- Each node contains two parts:
  - `data`: Stores the value.
  - `next`: Stores the reference to the next node.
- The last node always points to `None`.
- The `head` points to the first node.

## 2. Important Tips
- Always check whether the linked list is empty before performing operations.
- When inserting at the beginning, update `head` to the new node.
- When inserting at the end, traverse until `current.next == None`.
- When deleting the first node, update `head = head.next`.
- When deleting a node, carefully update the previous node's `next` reference.
- Never lose the reference to the remaining linked list while modifying pointers.
- Remember that indexing starts from `0`.

## 3. Common Edge Cases
Always test these situations:

- Empty linked list.
- Linked list containing only one node.
- Insertion at the beginning.
- Insertion at the end.
- Deletion of the first node.
- Deletion of the last node.
- Searching for an existing value.
- Searching for a value that does not exist.

## 4. Time Complexity

| Operation | Time Complexity |
|---|---|
| Access by index | O(n) |
| Search | O(n) |
| Insert at beginning | O(1) |
| Insert at end | O(n) |
| Delete at beginning | O(1) |
| Delete at end | O(n) |

## 5. Interview Tips
- Understand how pointers/references work.
- Practice reversing a linked list.
- Learn how to find the middle node using slow and fast pointers.
- Learn how to detect a cycle using Floyd's Cycle Detection Algorithm.
- Practice finding the nth node from the end.

