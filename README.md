# Queue-using-array
Queue using Array Introduction : A queue in C is basically a linear data structure to store and manipulate the data elements. It follows the order of First In First Out (FIFO). In queues, the first element entered into the array is the first element to be removed from the array. A queue is open at both ends. One end is provided for the insertion of data and the other end for the deletion of data. A real-world example of queue can be a single-lane one-way road, where the vehicle enters first, exits first. More real-world examples can be seen as queues at the ticket windows and bus-stops.

Operations Associated with a Queue in C:

enqueue(): It inserts elements to the end of the queue. dequeue(): Removes the element from the frontal side of the queue. Front: Pointer element responsible for fetching the first element from the queue Rear: Pointer element responsible for fetching the last element from the queue

Algorithm: Declare and set the variable front and rear to -1 initially when queue is empty.

Declare the functions : Enqueue , dequeue , Display.

Give the options to user in main function to either choose the operation enqueue , dequeue, display ,exit and call the function’s accordingly.

Define the functions:

Enqueue:

Check if the rear ==(size_of_array- 1); If True : print overflow Else If front == -1 , set front = 0. Increment the value of rear and insert the data input from user into the array[rear].

Dequeue:

Check if (front==-1) or (front> rear ), if true print underflow Else if ( front==rear) Set front and rear back to -1 i.e empty queue . Else set (front=front+1 )

Display:

If front==-1 , print queue is empty Else print the array queue using a for loop with counter variable initially set to front incrementing value upto rear . Applications of Queue Data Structure • CPU Scheduling • Disk Scheduling • Asynchronous data transfer between processors such as File IO, etc. • Breadth-First Search Algorithm (BFS)
![image](https://user-images.githubusercontent.com/125783965/230833235-fef438ba-2061-44eb-a253-863fec499f5e.png)
