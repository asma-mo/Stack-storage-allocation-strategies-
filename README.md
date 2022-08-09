# Stack-storage-allocation-strategies

introduction:
Storage allocation is the process of associating an area of storage with a variable so that the data item(s) represented by the variable can be recorded internally. When storage is associated with a variable, the variable is allocated.
The different ways to allocate memory are: 
1. Static storage allocation
2. Stack storage allocation
3. Heap storage allocation


What we are Implementing in this mini project is Stack.

Stack Allocation:
The allocation happens on contiguous blocks of memory. We call it a stack memory allocation because the allocation happens in the function call stack. The size of memory to be allocated is known to the compiler and whenever a function is called, its variables get memory allocated on the stack. And whenever the function call is over, the memory for the variables is de-allocated. This all happens using some predefined routines in the compiler. 
A programmer does not have to worry about memory allocation and de-allocation of stack variables.
* An activation record is pushed into the stack when activation begins and it is popped when the activation end.
* Activation record contains the locals so that they are bound to fresh storage in each activation record. The value of locals is deleted when the activation ends.
* It works on the basis of last-in-first-out (LIFO) and this allocation supports the recursion process


Aim:
to implement stack storage allocation strategies using C program.
Algorithm:
Step-1: Initially check whether the stack is empty
Step-2: Insert an element into the stack using push operation Step-3: Insert more elements onto the stack until stack becomes full Step-4: Delete an element from the stack using pop operation Step-5: Display the elements in the stack
Step-6:Stop the program by exit


