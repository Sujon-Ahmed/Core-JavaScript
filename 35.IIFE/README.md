Immediately Invoked Function Expression (IIFE)
----------------------------------------------
IIFE (Immediately Invoked Function Expression) is a JavaScript function that runs as soon as it is defined.
It is a design pattern which is also known as Self-Executing Anonymous Function and contains two major parts. The first is anonymous function with lexical scope enclosed within the Grouping Operator (). This prevents accessing variables within the IIFE idiom as well as polluting the global scope.
The second part is creating the immediately executing function expression (), through which the JavaScript engine will directly interpret the function.
Ex:-
    (function() {document.write("Hello World!");})();
    (function(a, b) {document.write(a+ " " +b);})(10,20);

Rules
--------
1. Avoid Creating Global variable and Functions
2. As it doesn't define variable and function globally so there will be no name conflicts
3. Scope is limited to that particular function.
