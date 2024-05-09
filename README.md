#ALAB-Event-Loop-308-A-1-1: Practical Use of the Event Loop and Call Stack


This project introduces JavaScript developers to practical event loop implementations and call stack concepts. It highlights common issues developers may face due to these core features in JavaScript. Through this lab, learners will experiment with JavaScript's call stack, implement trampolines to handle recursive functions and manipulate the event loop for deferred execution.

## Objectives

- Calculate the maximum stack size.
- Use trampolines to handle stack overflow issues caused by recursion.
- Use deferred execution within the event loop to allow browser rendering between calculations.

- ## Lab Exercises

### Part 1: Stack Overflow

- **Goal**: Determine the maximum size of the JavaScript call stack.
- **Approach**: A recursive function calls itself to artificially trigger a stack overflow, with a counter to track the number of calls made before the overflow occurs.

### Part 2: Trampolines

- **Goal**: Implement a trampoline to handle recursive functions that need to execute many times without causing stack overflow.
- **Approach**: A trampolined function to flatten deeply nested arrays is developed, demonstrating the effective use of this technique to prevent stack overflow.

### Part 3: Deferred Execution

- **Goal**: Manipulate the event loop to defer task execution, allowing the browser to remain responsive and render updates to the UI.
- **Approach**: Uses `setTimeout` to schedule tasks in the event queue, ensuring the browser can render outputs between executions.
