Many Function Arguments
-------------------------
If a function is called with too many Arguments, these Arguments can be reached using the Arguments object which is a built-in.

function add(a,b){
    document.write("A :" + a + "B :" + b);
    document.write("C : " + arguments[2] + "D :" + arguments[3]);
}
add(10,20,30,40);