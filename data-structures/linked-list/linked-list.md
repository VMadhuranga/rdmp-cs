1. **What is a linked list?**

   <details>
   <summary>Reveal</summary>

   A linked list is a collection of elements. Each element is called a node and has two fields: one to store the data and the other to store the memory address of the next node. In a linked list, the first node is called head, the last node is called tail, and the last node's next node field refers to null. This is also called a singly linked list.

   </details><br />

1. **What are the features of a linked list?**

   <details>
   <summary>Reveal</summary>

   - Linked lists are dynamically sized.
   - A linked list's elements don't have to be the same type.
   - A linked list's elements can be stored anywhere in memory; they don't have to be consecutive.
   - In a linked list, inserting and deleting elements is faster than an array, but accessing elements is slower than an array.

   </details><br />

1. **What are the common operations that we can perform on linked list?**

   <details>
   <summary>Reveal</summary>

   - Access nodes
   - Insert nodes
   - Delete nodes
   - Update nodes
   - Traverse a linked list

    </details><br />

1. **How to insert a node at the start of a linked list?**

   <details>
   <summary>Reveal</summary>

   - Create a new node
   - Make new node refer to the current head node
   - Change head to new node

   </details><br />

1. **How to insert a node at the end of a linked list?**

   <details>
   <summary>Reveal</summary>

   - Create a new node
   - Make tail node refer to the new node
   - Make new node refer to null

   </details><br />

1. **How to insert a node at the middle of a liked list?**

   <details>
   <summary>Reveal</summary>

   - Create a new node
   - Make new node refer to the node at insertion place
   - Make previous node of node at insertion place refer to the new node

   Algorithmic complexity of inserting node at start, middle and end from linked list is O(1)

   </details><br />

1. **How to delete a node at the start of a liked list?**

   <details>
   <summary>Reveal</summary>
    
   Change head to the second node.

   </details><br />

1. **How to delete a node at the end of a liked list?**

   <details>
   <summary>Reveal</summary>

   Make the second last node refer to null.

   </details><br />

1. **How to delete a node at the middle of a liked list?**

   <details>
   <summary>Reveal</summary>

   - Take the node before the node to be deleted.
   - Make it refer to the node after the node to be deleted.

   Algorithmic complexity of deleting node at start, middle and end from linked list is O(1)

   </details><br />

1. **How to traverse linked list?**

   <details>
   <summary>Reveal</summary>

   - Start with head node
   - Read memory address of the next node
   - Visit the next node
   - Repeat until last node reached
   - To check last node reached just check the next node field refer to null

   Algorithmic complexity of traversing a linked list is O(n)

   </details><br />

1. **How to access element from linked list?**

   <details>
   <summary>Reveal</summary>

   - Start with head node
   - Traverse until node we need to access reached

   Algorithmic complexity of accessing a node from linked list is O(n)

   </details><br />

1. **What are the types of linked list**

   <details>
   <summary>Reveal</summary>

   - Singly linked list
   - Doubly linked list
   - Circular linked list
   - Doubly Circular linked list

   </details><br />

1. **What is singly linked list**

   <details>
   <summary>Reveal</summary>

   Look What is linked list

   </details><br />

1. **What is doubly linked list**

   <details>
   <summary>Reveal</summary>

   Doubly linked list similar to singly linked list but each node have additional field which refers to previous node
   and head node's previous node field refers to null

   </details><br />

1. **What is circular linked list**

   <details>
   <summary>Reveal</summary>

   Circular linked list similar to the singly linked list but tail node's next node field refers to the head node instead of null

   </details><br />

1. **What is doubly circular linked list**

   <details>
   <summary>Reveal</summary>

   Doubly circular linked list similar to the doubly linked list but head node's previous node field refers to the tail node and tail node's next node field refers to the head node

   </details><br />
