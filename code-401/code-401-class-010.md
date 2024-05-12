 **Reading Notes | 10 MAY 2024**

# Class 010

### *Stacks & Queues:*
WHY: Stacks and queues are foundational data structures, crucial in programming due to their simple yet efficient data organization. They provide well-defined methods to add or remove elements, making them versatile for tasks such as managing memory, processing data in a specific sequence, or implementing algorithmic functions.

WHAT:

Stacks: Linear data structures following a Last In First Out (LIFO) or First In Last Out (FILO) approach. Nodes reference only the next node, with operations like Push (adding an element), Pop (removing the top element), Peek (viewing the top element without removal), and IsEmpty (checking if the stack is empty).

Queues: Linear data structures following a First In First Out (FIFO) or Last In Last Out (LILO) approach. Nodes have operations such as Enqueue (adding an element at the rear), Dequeue (removing the front element), Peek (viewing the front element without removal), and IsEmpty (checking if the queue is empty).

HOW:

Stack Operations:

Push: Adds a node at the top by setting the new node’s next reference to the current top and updating the top reference to this new node.
Pop: Removes the top node by setting the top reference to the next node, ensuring no lingering references for garbage collection.
Peek: Returns the value of the top node without modifying its next reference.
IsEmpty: Returns a boolean indicating whether the stack's top reference is null.
Queue Operations:

Enqueue: Adds a node to the rear by setting the current rear’s next reference to the new node and updating the rear reference to this new node.
Dequeue: Removes the front node by setting the front reference to the next node, ensuring no lingering references for garbage collection.
Peek: Returns the value of the front node without modifying its next reference.
IsEmpty: Returns a boolean indicating whether the queue’s front reference is null.