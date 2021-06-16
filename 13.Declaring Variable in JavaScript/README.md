Declaring Variable in JavaScript
--------------------------------------
1. Variable can contain combination of letters, digits, underscores(_), and dollar sign($).
2. Must begin with a letter A-Z or a-z or underscore(_) or dollar sign($)
3. A variable name can not start with a number(0-9).
4. Must not contain any space characters.( )
5. JavaScript is case-sensitive
6. Can't use reserved keywords.

Ex:-  Valid variable
        name
        Cab123
        Rup$
        New_Delhi

Ex:- Non Valid variable
        58show
        Still City
        var

A variable declared without a value will have the value undefined.
These all are undefined value
----------------------------------------
    var roll;
    var name;
    var price;

Initializing Variable
-------------------------
Method 01                   Method 02                      Method 03
------------              --------------                 -------------
var roll;               var roll = 923364;              roll = 923364;
roll = 923364;

var name;               var name = "Sujon Ahmed";       name = "Sujon Ahmed";
name = "Sujon Ahmed";

var price;              var price = 123.6;              price = 123.6; 
price = 123.6;

Different
---------------
var x = 10, y = 20, z = 30;
var f_name = "Sujon", l_name = "Ahmed";
var name = "Sujon Ahmed", roll = 923364;
---------------
var name = "Sujon Ahmed",
    roll = 923364,
    address = "Still City";


Boolean Variable
-------------------
var answer = true;
var result = false;

======================================================================================
Notes: var not important!
        => Strings are written inside double or single quotes.
        => Numbers are written without quotes.
        => If you put a number of quotes, it will be treated as a text string.
=======================================================================================

Re-declaring Variable
-----------------------
If you re-declare a JavaScript variable, it will not lose it's value.
var name = "Sujon Ahmed";
var name;

1. The statements are executed, one by one, in the same order as they are written.
2. JavaScript programs (and JavaScript statements) are often called JavaScript code.
3. Semicolons separate JavaScript statements.
4. Ending statements with semicolon is not required, but highly recommended.
5. JavaScript ignores multiple spaces.
6. Use line break (Enter Key)

