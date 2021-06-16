Arguments Object
--------------------
The arguments object contains an array of the arguments used when the function was called. The object contains an entry for each argument passed to the function, the first entry's index starting at 0. The arguments object is not an array. It is similar to an Array, but does not have any Array properties except length. 

function add(num1, num2) {
    //arguments[0] = 10
    //arguments[1] = 20
}
add(10,20);
