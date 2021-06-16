Objects
_________
An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects.

Ex:-
    var fess={
        Sujon: 100,     //Properties
        Sumon: 200,     //Properties
        Riman: 300      //Properties
        total: function(){ return(100+200+300);}    // Method
    }

Type of Objects
_________________
1. User-defined Objects - These are custom objects created by the programmer to bring structure and consistency to a particular programming task.

2. Native Objects - These are provided by the JavaScript language itself like strong, Number, Boolean, Function, Date, Object, Array, Math, RegExp, Error as well as object that allow creation of user-defined objects and composite types.

3. Host Objects - These objects are not specified as part of the JavaScript language but that are supported by most host environments, typically browsers like window, navigator.

4. Document Objects - These are part of the Document Object Model (DOM), as defined by the W3C. These objects presents present the programmer with a structured interface to HTML and XML documents. Access to the document objects is provided by the browser via the document property of the window object (window.document).

Declaration and Initialization of Object
___________________________________________
* Using Object Literal
    Syntax:- var object_name = {key1:value1, key2:value2, key+_n:value_n, key:function};
    Ex:- var fess ={Sujon:100, Riman:200, Sumon:300, total: function({return(100+200+300);})};

    Multi_Line Ex:-
    var fess ={
        Sujon:100,
        Riman:200,
        Sumon:300,
        total: function(){return(100+200+300);}
    };

* Using Object Constructor
    Syntax:- var object_name = new Object();
    Ex:- var fess = new Object();
    fess['Sujon'] = 100;
    fess['Riman'] = 200;
    fess['Sumon'] = 300;
    document.write(fess['Sujon']);

Accessing properties
______________________
A property is an object some piece of named data it contains. These are accessed with dot operator applied to an object alternative to the dot operator is the array[] operator.
Syntax:- object_name.property_name

Accessing Methods
_____________________
Object members that are functions are called methods.These are accessed with dot operator applied to an object alternative to the dot operator is the array[] operator.
Syntax:- object_name.method_name
Ex:-
    var fess ={
        Sujon:100,
        Riman:200,
        Sumon:300,
        total: function(){return(100+200+300);
        }
    };
    document.write(fess.total());

Adding Properties/Method
__________________________
    Syntax:- Object_name.Property_name = value;
            Object_name['Property_name'] = value;
    Ex:- fess.Rafi = 500;
        fess.['Rafi'] = 500;

Delete Properties
______________________
Delete operator is used to delete instance properties.
Syntax:- delete object_name.property_name
    Ex:- delete fess.Sujon;
After removal with delete operator, The property has undefined value.
