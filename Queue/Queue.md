## Queue
It is a linear data structure similar to stack but follow **FIFO** (first in first out) principle to manipulate data elements.

### Types of queue
1. [[Simple Queue]]
2. [[Double ended Queue]] (Dequeue)
3. [[Circular Queue]]
4. Priority Queue

### Operations
1. **Enqueue**: Adds (or stores) an element to the end of the queue also known as rear end. The new element is always inserted from the rear end.
2. **Dequeue**: Removal of elements from the beginning of the queue . The new element is always inserted from the front end.
3. **Peek or front**: Acquires the data element available at the front node of the queue without deleting it.
4. **rear**: This operation returns the element at the rear end without removing it.
5. **isFull**: Validates if the queue is full.
6. **isEmpty**: Checks if the queue is empty.

### Application
1. It can used in job scheduling like printer spooling, processes scheduling in operating system, keyboard buffer.
2. It can used where we have single resource and multiple consumers.
3. It is also used to transfer data between peripheral devices and the cpu.

### Advantages
1. **Resource sharing**: Queues are very useful when a single service is used by multiple consumers.
2. **Concurrency**: It helps implement concurrency in OS.
3. **Efficient insert/delete**: Enqueue and Dequeue are performed in O(1) time.
4. 


