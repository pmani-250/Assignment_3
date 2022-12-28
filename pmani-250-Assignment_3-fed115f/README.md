# Assignment_3
# Question 1

If you worked in group, please, kindly list all of the group member names below.

# Question 2

Write a program that does the following (the links in the notes provide useful information):

1.  The program shall be invoked as ./threads "number" where "number" is the number of threads.  For example, ./threads 10 will create 10 threads.

2. The program will then create the specified number of threads and each thread will then generate 100 random numbers in range of 0 -- 100000 and insert them into the same shared binary search tree that is shared between all threads.

3.  All threads should be allowed to insert the numbers at the same time while ensuring proper synchronization using pthread mutexes (i.e., no two threads will be modifying the tree at the same time).

4. While the created threads are busy inserting numbers, the main thread waits for the other threads to terminate.  Once all threads terminate the main thread will print all numbers in the binary tree. Correctly printed numbers should be in order (as that is the point of the binary search tree).

# Grading:
Program Compiles: 5'
  
Correct Implementation of binary search tree: 20'
  
Correct implementation of threads and synchronization logic: 75'
  

# Submission:
Please submit below a tar file containing your code and README file documenting the names of all team members, instructions on how to run your program, and anything special about your program. Please name your file as a3_<yourname>.tar

# NOTES: You may find the following links useful:
1. Pthreads: https://www.cs.cmu.edu/afs/cs/academic/class/15492-f07/www/pthreads.html. 
Links to an external site.
Also, please check our lectures and samples for pthreads and synchronization.
2. Binary Search Trees: https://www.programiz.com/dsa/binary-search-tree
Links to an external site.
3. Random number generation in C/C++:  https://www.cplusplus.com/reference/cstdlib/rand/
Links to an external site.
