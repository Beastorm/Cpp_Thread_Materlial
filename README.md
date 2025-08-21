## Interview Questions on threads in C++:
 - Thread in C++
 - 5 Different ways to create threads in C++11
 - Life cycle of a thread
 - Join and detach with joinable()
 - Mutex and mutex lock
 - std::try_lock
 - Timed mutex
 - Recursive mutex
 - Shared mutex
 - std::lock
 - Lock guard
 - Unique lock and shared lock
 - Scoped lock
 - Condition variable and its usage
 - Deadlock
 - Thread or Process synchronization
 - std::promise and std::future
 - std::async
 - Producer and Consumer
 - Sleep vs wait
 - Is a static variable thread safe or not?
 - Binary semaphore
 - Mutex vs semaphore
 - Producer-Consumer Problem using a semaphore
 - Race condition
 - Thread pool
 - Object pool in multithreading
 - Oversubscription in multithreading
 - Atomic variables and related operations to this

## Thread Topics from basic to advanced in C++:
### Thread Management Guide:
 - Setting up the environment for the course
 - Introduction to parallel computing
 - Quiz: Parallel programming in general
 - Uses of parallel programming.
 - How to launch a thread
 - Programming exercise 1: Launching the threads
 - Joinability of threads
 - Join and detach functions
 - How to handle join in exception scenarios
 - Programming exercise 2: Trivial sale a ship model
 - How to pass parameters to a thread
 - Problematic situations may arise when passing parameters to a thread
 - Transferring ownership of a thread
 - Some useful operations on threads
 - Programming exercise 3: Sail a ship with work queues
 - Parallel accumulate - algorithm explanation
 - Parallel accumulate algorithm implementation
 - Thread local storage
 - Debugging an application in Visual Studio
 - Thread management

### Thread Safe Access to shared data and locking mechanisms:
 - Introduction to locking mechanisms
 - Concept of invarient
 - Critical Sections
 - Mutex Introduction
 - Mutex Class
 - Things to remember when using mutexes
 - Thread-safe stack implementation: introduction to the stack
 - Thread-safe stack implementation: implementation
 - Thread-safe stack implementation: race condition is inherited from the interface
 - Internally Synchronized Class
 - Lock Guard
 - Unique Lock
 - Timeouts and Mutexes
 - Multiple Reader, Single Writer
 - Shared Mutexes
 - Shared Data Initialization
 - Thread-local Data
 - Lazy initialization
 - Double-Checked Locking
 - Deadlock
 - Deadlock Practical
 - Deadlock Avoidance
 - Deadlock Avoidance Practical
 - Livelock
 - Livelock Practical

### Communication between threads using condition variables and futures:
 - Introduction to condition variables
 - Details about condition variables
 - Thread-safe queue implementation: introduction to queue data structure
 - Thread-safe queue implementation: implementation
 - Introduction to futures and async tasks
 - async tasks detailed discussion
 - Parallel accumulate algorithm implementation with async task
 - Introduction to package_task
 - Communication between threads using std::promises
 - Retrieving exception using std::futures
 - std::shared_futures

### Lock-based thread-safe data structures and algorithm implementation:
 - Introduction to lock-based thread-safe data structures and algorithms
 - Queue data structure implementation using a linked list data structure
 - thread-safe queue implementation
 - Parallel STL introduction
 - Parallel quick sort algorithm implementation
 - parallel for each implementation
 - Parallel find algorithm implementation with the package task
 - Parallel find algorithm implementation with async
 - Partial sum algorithm introduction
 - Partial sum algorithm parallel implementation
 - Introduction to Matrix
 - Parallel Matrix multiplication
 - Parallel matrix transpose
 - Factors affecting the performance of concurrent code

### C++20 Concurrency Features:
 - Jthread: Introduction
 - Jthread: Our version implementation
 - C++ coroutines: Introduction
 - C++ coroutines: resume functions
 - C++ coroutines: Generators
 - C++ Barriers

### C++ memory model and atomic operations:
 - Introduction to atomic operations
 - Functionality of std::atomic_flag
 - Functionality of std::atomic_bool
 - Explanation of compare_exchange functions
 - atomic pointers
 - General discussion on atomic types
 - Important relationships related to atomic operations between threads
 - Introduction to memory ordering options
 - Discussion on memory_order_seq_cst
 - Introduction to instruction reordering
 - Discussion on memory_order_relaxed
 - Discussion on memory_order_acquire and memory_order_release
 - Important aspects of memory_order_acquire and memory_order_release
 - Concept of transitive synchronization
 - Discussion on memory_order_consume
 - Concept of release sequence
 - Implementation of spin lock mutex

### Lock-free data structures and algorithms:
 - Introduction and some terminology
 - Stack recap
 - Simple lock-free thread-safe stack
 - Stack memory reclaim mechanism using thread counting
 - Stack memory reclaim mechanism using hazard pointers
 - Stack memory reclaim mechanism using reference counting

### Thread pools:
 - Simple thread pool
 - A thread pool that allows waiting on submitted tasks
 - Thread pool with waiting tasks
 - Minimizing contention on the work queue
 - Thread pool with work stealing

