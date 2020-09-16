# Explore the Tech!

In today's blog, I am going to discuss the topic of **JS debugging**, which is sub-topic related to **Javascript** programming. So, _let's get started!_

***Error Handling and Debugging***
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run. The JavaScript interpreter uses the concept of **execution contexts**. The following are execution contexts in JS:
* Global Context (_global scope_).
* Function Context (_function-level scope_).
* Eval Context.

Also, Each time a script enters a new execution context, there are two phases of activity:
1. Prepare: The new scope is created, variables, functions, and arguments are created, and the value of the this keyword is determined.
2. Execute: Now it can assign values to variables, reference functions and run their code, and execute statements.

In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object. Furthermore, if a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.

Another thing is **Error objects**, whcih can help you find where your mistakes are and browsers have tools to help you read them. The following are error types in programming:
* `Syntax Error`: This is caused by incorrect use of the rules of the language. It is often the result of a simple typo.
* `Reference Error`: This is caused by a variable that is not declared or is out of scope.
* `Eval Erorr`.
* `URI Error`.
* `Type Error`.
* `Range Error`.
* `Error`: the template (or prototype) from which all other error objects are created.
* `NaN`: not an error, (Not a Number).
