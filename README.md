# array-and-linkedlist
Pseudocode
*Queue demo using array
*Queue demo using linklist
*Stack demo using array
*Stack demo using linklist



Stack
Displaying a value from the Stack (array)
-----------------------------------------
Procedure Pop
if Current is equal to Zero then
Output error that Stack is empty
Else
Output value from Stack at Current position
Subtract 1 from Current
Endif
End Procedure
===============================================================================================
QUEUES
=======
Array Queue[MAX]
Adding a Value
--------------------
Procedure Insert(Value)
If End is equal to MAX then
Output an error message that the Queue is full
Otherwise
Add 1 to End
Store data in Value into Queue at End position
Endif
End Procedure
'Go to next available element in Queue
'No more space in Queue
'Output (POP) a value in the Current element (LIFO).
'If there are no values in the Stack.
'Nothing to output.
'Put (Push) the data sent in Value parameter in the new element.
To track the End element of the Queue.
Maximum number of elements (or whatever value you like as the
number of elements in the Queue)
Declares an array of 5 elements for the Queue.Displaying value from Queue
----------------------------------
Procedure Display
If End is equal to Zero then
Output an error message that the Queue is empty
Otherwise
Display value at position Queue[1]
Start Loop from position 1 to End position
Copy data from Next element to Current element
Move to Next element
End Loop
EndIf
End Procedure
=====================================================================================================
Linked List
==========
Declaring a Linked List
-----------------------------
Integer : Data
Pointer: Next
Declaring variables
-----------------------
Pointer : Start
Start = NULL
Creating a New Node with above structure.
---------------------------------------------------
Procedure Create(Value)
If there is enough memory available then
Create New Node in memory
Point its Next pointer to NULL
If this is the first Node in the List then
Point Start to the Node
'Only create a Node if memory is available
'Creating a New Node for the Linked List
'Making a termination point for the Node
'There must be a starting point for the Linked List
'Point Start to New Node only if it is the very first one
'Nothing in the Linked List
'Always display first value (FIFO)
'Looping through all elements with values
'Moving data is step on its left to fill the gap in the 1 position
'No values to displayOtherwise
Go to memory location pointed by Start pointer Start Loop and run until Next points to NULL Go to the Node pointed by Next pointer
End Loop Point Next of last Node to the newly created Node
Put data in Value in new Node's Data Endif Otherwise Output error message that there is no more memory available
EndIf End Procedure
