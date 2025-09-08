🧩 Problem:
Remove Linked List Elements — LeetCode #203
You're given the head of a singly linked list and a value val. You need to remove all nodes with that value and return the updated head.

🔍 Pattern Category:
🔗 Linked List – In-place Node Removal with Dummy Node
This falls under the broader category of Linked List Traversal and Modification, and more specifically, it uses the Dummy Node Technique to handle edge cases cleanly.

🧠 Solved via:
Pointer Manipulation + Dummy Node Setup
- You traverse the list using a pointer (temp or pre).
- You check the next node’s value.
- If it matches val, you skip it by adjusting the pointer.
- The dummy node ensures even the head can be removed without special logic.
This pattern is especially useful when:
- You need to delete nodes without knowing their previous node.
- The head itself might be deleted.
- You want to avoid messy conditional logic.




