JavaScript book, Ch. 10, “Error Handling & Debugging”

The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

In the interpreter, each execution context has its own vari ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's vari ables object.

If a JavaScript statement generates an error, then it throws an exception . At that point, the interpreter stops and looks for exception-handling code.

Error objects can help you find where your mistakes are and browsers have tools to help you read them.

1: DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.
2: HANDLE ERRORS GRACEFULLY You can handle errors gracefully using try, catch,
throw, and f i na1ly statements.
