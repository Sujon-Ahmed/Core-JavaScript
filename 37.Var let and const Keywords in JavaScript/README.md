var, let and const
_____________________

var ==> The scope of a variable declared with is it's current execution context, which is either the enclosing function or, for variables declared outside any function, global.

let ==> let allows you to declare variables that are limited in scope to the block, statement, or expression on which it is used.

const == > This declaration creates a constant whose scope can be either global or local to the block in which it is declared. Global constants do not become properties of the window object, unlike var variables. An initializer for a constant is required; that is, you must specify it's value in the same statement in which it's declares which can't be changed later.

