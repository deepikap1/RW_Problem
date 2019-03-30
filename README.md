# RW_Problem
A classical Reader-Writer Problem is a situation where a data structure can be read and modified simultaneously by concurrent threads. Only one Writer is allowed access the critical area at any moment in time. When no Writer is active any number of Readers can access the critical area. To allow concurrent threads mutually exclusive access to some critical data structure, a mutually exclusive object, or mutex, is used. As an implementation mutex is a special case of a more generic synchronisation concept – semaphore. A simple image of a semaphore is a positive number which allows increment by one and decrement by one operation. If a decrement operation is invoked by a thread on a semaphore whose value is zero, the thread blocks until another thread increments the semaphore. 
 # For Ubuntu 
 use these commands in terminal for compilation.
 # How to compile this code:
   $ gcc rw.c o rw -lpthread
 # how to run this code:
  $ ./rw
  
