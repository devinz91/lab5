Lab 5 Answers

Why does LinkedStack not require an explicit constructor?
Because the program is using the implementation from the IStack interface.

What is the time and (extra) space complexity of each of the LinkedStack methods, as well as ReverseLines.main?
push, peak, pop and empty are all O(1) and reverseLines and asList are O(n). 

How else (not using Node) could we have implemented LinkedStack in such a way that it is still based on a linked list but the asList method uses constant time and space?
We could have used {list = new LinkedList<>();} That would make it so it has constant time and space. 


Is it better for push and pop to return the item or the stack itself? Briefly discuss the pros and cons of each design.
It is better to return the items individually. For the pros of the returning items, it takes less time and you are only interested in the top data. The pros for returning the stack is you get to see the whole stack but the con for that is it takes longer when you don't need to see every entry.   