Rest vs Arguments
---------------------
There are three main difference between rest parameters and the arguments object:-

1. Rest parameters are only the ones that haven't been given a separate name, while the arguments object contains all arguments passed to the function.
2. The arguments object is not a real array,while Rest Parameters are Array instances,meaning methods like sort,map,forEach or pop can be applied on it directly.
3. The arguments object has additional functionality specific to itself(like the callee property).