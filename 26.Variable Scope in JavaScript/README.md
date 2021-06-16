Variable Scope
-------------------
javaScript has two scope:-
1. Global
2. Local

Global Scope
--------------------
A variable that is declared outside a function definition is a global variable, and it's value is accessible and modifiable throughout your program.
In a web browser, global variables are deleted when you close web window (or tab), but remain available to new pages loaded into the same window.

Ex:-
    var a = 10  // Global variable
    function add(b){
        return(a + b); // a is global variable
    }
    document.write(add(20));


Local Scope
-------------------
A variable that is declared inside a function definition is local. It's created and destroyed every time the function is executed, and it's can't be accessed by any code outside the function. Inside a function, if a variable has not been declared with var it is created as a global variable.

Ex:-
    function add(b){
        var a = 10;     // Local Variable
        return(a + b);
    }
    document.write(add(20));

    function add(b){
        a = 10;     // Global Variable
        return(a + b);
    }
    document.write(add(20));

If there is function inside a function the inner function can access outer function's variables but outer function can not access inner function's variables.
Function arguments (parameters) work as local variables inside function.

 function show(){
    var j = "J a Local variable of outer variable"; 
    document.write(j + "<br>");
    function fun(){
        var k = "K a Local variable of inner variable"; // If deleted var then j global variable
        document.write(k + "<br>");
        document.write(j + "<br>");
    }
    fun();
    document.write(k + "<br>");
}
show();