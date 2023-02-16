# jsruntimemodel
Javascript runtime

JavaScript has a runtime model based on the event loop & consists of several key components:

The task queue: This is a list of tasks that need to be executed by the JavaScript engine. Tasks can be added to the queue through various mechanisms, such as function calls, timers, and user events.

The event loop: This is the mechanism that manages the execution of tasks in the queue. It continually checks the queue for tasks that need to be executed, and runs them one by one.

The call stack: This is a data structure that stores the execution context of each function that is currently being executed. When a function is called, its execution context is added to the top of the call stack. When the function returns, its execution context is removed from the top of the stack.

The microtask queue: This is a separate queue that is used to store microtasks, which are small tasks that are executed before the event loop moves on to the next iteration. Microtasks are often used to handle promises and async/await operations.

The heap: This is a memory space where objects and variables are allocated. The heap is used to store the data that is needed for the execution of tasks and events.

The garbage collector: This is a process that is responsible for freeing up memory by removing objects and variables that are no longer being used. The garbage collector runs periodically to clean up the heap and make sure that memory is being used efficiently.
