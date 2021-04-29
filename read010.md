# call stack

is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

* When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

* When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack.

* The call stack maintains a record of the position of each stack frame. It knows the next function to be executed (and will remove it after execution). This is what makes code execution in JavaScript synchronous.

        What if the operation or function we want to perform needs some time (seconds) to complete its task? Will the Call Stack stop for that long in order to get to the next mission? Fortunately, JavaScript knows very well how to perform such asynchronous operations with great efficiency.

* if we have an asynchronous method like setTimeout () function will normally be sent to the Call Stack, and the latter will quickly understand that it is an asynchronous function and thus take the return back from it () => console.log ('') And assign it to the Web API It counts the time period of 2000ms until it re-transmits, not directly to Call Stack, but to a kind of waiting room known as the Tail or Queue.

* Immediately after assigning setTimeout to the Web API it is passed directly to the next function console.log ('World') function on line 3, regardless of what the modes in the asynchronous process in the second line become.

* that means, by the time the two-second duration is calculated, 2000ms, the third line of the script has already been executed. Then the Call Stack becomes empty after he has completed all the work assigned to him up to the hour.

* This is where Event Loop gets into the game and does its job which is simply connecting the Queue to the Call Stack.

* When the Call Stack is empty, the Event Loop looks at the Callback Queue to see if there are some tasks waiting in line and takes the first task and gives it to the Call Stack in order to carry out its orders, and so on.
