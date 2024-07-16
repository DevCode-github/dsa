## Linked list
It is a linear data structure that stores data in nodes, that are connected by pointers. Unlike array linked list are not stored in contiguous memory location.

### Characteristics  (vs)  [[Array]]
- **Data Structure:** Non-contiguous
- **Memory Allocation:** Dynamic
- **Insertion/Deletion:** Efficient
- ***Access:*** Sequential

### Operations
- **Creation**: Creating a new linked list or adding a new node to an existing list.
- **Traversal**: Iterating through the list and accessing each node.
- **Insertion**: Adding a new node at a specific position in the list.
- **Deletion**: Removing a node from the list.
- **Search**: Finding a node with a specific value in the list.

### Types of Linked List
1. Singly Linked List
2. Doubly Linked List
3. Circular Linked List
4. Circular Doubly Linked List
5. Header Linked List

### Advantage
1. **Dynamic size**: The linked list can grow in size, without any need for preallocating memory.
2. **Efficient insert/delete operation**: Insertion and deletion are efficient compared to array, since it does not require shifting of elements.
3. **No wasted memory**: Memory is allocated as needed, in contrast to array which unused allocated space.
### Disadvantage
1. **Memory overhead**: Each element requires a extra memory to store a reference or pointer to the element.
2. **Sequential access**: It does not allow random access, one have to traverse the list to find the specific element.
3. **Performance issue**: In contrast to array that has contiguous memory, linked list nodes are scattered all over memory and can lead to performance issue for large data sets.