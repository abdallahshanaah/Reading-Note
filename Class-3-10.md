# Call stack
call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions 

* When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
* Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
* When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
* If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.
and example of it .
and how it help 
# Types of error messages
1. Reference errors
console.log(foo) // Uncaught ReferenceError: foo is not defined
2. Syntax errors
JSON.parse( {'foo': 'bar'} ) // Uncaught SyntaxError: Unexpected token o in JSON at position 1
3. Range errors
var foo= []
foo.length = foo.length -1 // Uncaught RangeError: Invalid array length
4. Type errors
var foo = {}
foo.bar // undefined
foo.bar.baz // Uncaught TypeError: Cannot read property 'baz' of undefined
and **Debugging** and how it help to get handling errors .