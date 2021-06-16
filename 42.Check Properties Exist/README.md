Check Properties Exist
_________________________
* Typeof operator
    Syntax:- if(typeof object_name.key !== 'undefined')
    Ex:- if(typeof nokia.memory !== 'undefined){
        document.write("Available");
    }else{
        document.write("doesn't Exist);
    }

* In operator
    Syntax:- if('key' in object_name)
    Ex:- if('memory' in nokia) {
        document.write("Available");
    }
    else{
        document.write("doesn't Exist);
    }

* hasOwnProperty
    Syntax:- if(object_name.hasOwnProperty("key"))
    Ex:- if(nokia.hasOwnProperty("White")){
         document.write("Available");
    }
    else{
        document.write("doesn't Exist);
    }