#### Queues
-  *Enqueue* - adds data to the “back” or end of the queue
- *Dequeue* - provides and removes data from the “front” or beginning of the queue
- *Peek* - reveals data from the “front” of the queue without removing it
-  Queues process data First In, First Out (FIFO)
- Implemented using a linked list 
  - Head Node- front of queue
  - Tail Node- back of queue
- *Bounded Queue*- a queue that has a limit on the amount of data that can be placed into it
- *Queue Overflow*- attempting to enqueue data onto an already full queue 
- *Queue Underflow*- attempting to dequeue data from an empty queue
- Traversal or modification to other nodes within the linked list is disallowed
- Since both ends of the queue must be accessible, a reference to both the head node and the tail node must be maintained.