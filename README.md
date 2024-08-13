# Bounded-Buffer-Problem
a Java Multithreading program to solve the Multiple  Producer and Multiple consumers Problem, Also known as the Producer-Consumer problem. there is a buffer of n slots, and each buffer can store one unit of data.– There are multiple Producers and multiple  Consumers. The producers try to insert data and the consumers try to remove data. 
The solution must be free from Deadlock and starvation

The Solution
------------
There is a buffer With capacity N can store data items, The places 
used to store the data items inside the bounded buffer are called 
slots(N), each slot is capable of storing one unit of data. 
We have 2 Process (Producer and consumer) each of them 
operating on the buffer. 
A producer tries to insert data 
into an empty slot of the buffer 
and consumer tries to remove 
data from a filled slot in the 
buffer
Without proper 
synchronization the 
following errors may 
occur: 
 The producer tries to insert data when the buffer is full 
 The consumer tries to consume date from empty slot 
 The producer and consumer insert and remove data in the same time 
 2 producer writes into the same slot 
 2 consumer reads the same slot   
_________________________________________________________________________________

![Bounded-Buffer-Problem-OS-Operating-System](https://github.com/user-attachments/assets/cca1bcc0-4ebe-4743-8e5a-1ecf27ce2996)

For dore details read The documention.


