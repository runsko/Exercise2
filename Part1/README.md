# Mutex and Channel basics

### What is an atomic operation?
> An operation not allowing interrupts, as other threads sees it as a single operation.

### What is a semaphore?
> A type of flag used to limit access to a shared resource. Counting and Binary semaphores. wait() decreases the flag, and signal() increases the flag.

### What is a mutex?
> A kind of semaphore which also icludes ownership. This limits the call to signal() and wait() to the one process currently "owning" the thread.

### What is the difference between a mutex and a binary semaphore?
> The ownership principle

### What is a critical section?
> A code segment which need to be executed as an atomic operation

### What is the difference between race conditions and data races?
 > *Your answer here*

### List some advantages of using message passing over lock-based synchronization primitives.
> *Your answer here*

### List some advantages of using lock-based synchronization primitives over message passing.
> *Your answer here*
