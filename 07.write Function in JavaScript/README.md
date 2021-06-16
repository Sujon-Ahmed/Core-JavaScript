document.write()
This function is used to write arbitrary HTML and content into page. If we use the function after an HTML document is fully loaded, will delete all existing HTML. It is used only for testing purpose.
Ex:-
	document.write("Hello World");
	document.write(variable);
	document.write(4+2);
	document.write("Hello World. <br>");
	document.write("Hello World.<br>" + variable + "<br>");