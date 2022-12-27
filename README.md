# MultiThreading_8_cores
using Ubuntu, C++
A thread is a unit of execution within a process that can be scheduled by the operating system. By using multiple threads, a program can perform multiple tasks concurrently, which can make it more efficient and responsive.
For example, a program that needs to perform a long-running task, such as downloading a large file from the internet, can create a new thread to perform the task in the background while the main thread continues to run and respond to user input. This allows the program to remain responsive to the user while the long-running task is being performed.
Overall, multithreading can make it easier to write programs that can perform multiple tasks concurrently and can improve the performance and responsiveness of those programs.
This implementation creates a new thread to sort each half of the array, and then waits for both threads to complete before merging the two sorted halves.
This approach can be effective for sorting large arrays, as it allows the CPU to perform multiple tasks concurrently and can improve the overall performance of the sorting algorithm. However, it is important to note that the overhead of creating and managing threads can reduce the overall performance if the array is small or if there are not enough CPU cores to fully utilize all of the threads.
# Steps For Implementation:
define the number of threads and size of array for elements in an array.
# merge function for merging two parts

 n1 is size of left part and n2 is size
    // of right part
    storing values in left part
    storing values in right part
    merge left and right in ascending order
# merge sort function
 calculating mid point of array
  calling first half
  calling second half
  merging the two halves
  
 # thread function for multi-threading
 calculating low and high
 evaluating mid point
 # Driver Code
 generating random values in array
 t1 and t2 for calculating time for
    // merge sort
    creating 8 threads
    joining all 4 threads
    merging the final 8 parts
    displaying sorted array
    time taken by merge sort in seconds
