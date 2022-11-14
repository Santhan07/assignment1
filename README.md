# assignment1


1. Write a blog on the difference between document and window objects.

Document Object: 
      -The document object represent a web page that is loaded in the browser. 
      -By accessing the document object, we can access the element in the HTML page. 
      -With the help of document objects, we can add dynamic content to our web page.  
      -The document object can be accessed with a window.document or just document.

Syntax:
      document.property_name;

Properties of document Objects:
        The properties of document objects that are commonly used are listed in the below table:
                - activeElement:  It returns the currently active elements in the document.
                - body:  It returns the contents of the body element.
                - anchors:  It returns all <a> elements that have a name attribute.
                - cookie:  It returns the cookie of the current document.
                - URL:  It returns the complete URL of the document.
                - title:  It returns the title element of the document.
                - head:  It returns the head element of the document.
                - images:  It returns the collection of <img> elements in the document.

Methods of Document:

Syntax:
        document.method_name;
  
The lists of most commonly used methods are listed below:
                - addEventListener():  It is used to attach an event handler to the specified element.
                - close():  It is used to close the output stream.
                - createAttribute():  It is used to create an attribute node with the specified name and returns the attribute object.                
                - createElement():  It is used to create HTML element .
                - getElementById():  It returns the object of the given ID. If no object with that id exists then it returns null.
                - write():  It is used to write some content or javascript code in the document.

Window Object: 
	              - The window object is the topmost object of the DOM hierarchy. 
                - It represents a browser window or frame that displays the contents of the webpage.
                - Whenever a window appears on the screen to display the contents of the document, the window object is created. 

Syntax:
	window.property_name;

The properties of Window objects that are commonly used are listed in the below table:
	     - Closed:  It holds a Boolean value that represents whether the window is closed or not.
	     - console:  It returns a reference to the console object which provides access to the browser’s debugging console.
	     - controllers:  It returns the XUL controller objects for the current Chrome window.
	     - Document:  It returns a reference to the document object of that window.
	     - Location:  It contains the URL of the current window.
	     - Window:  It returns the current window or frame.

Methods of Window:

Syntax:
	window.method_name;

	The methods of Window objects that are commonly used are listed in the below table:

	    - alert():  It is used to display an alert box. It displays a specified message along with an OK button and is generally used to make sure that the information comes through the user.
	    - clearTimeout():  It clears the timeout which has been set by the setTimeout()function before that.
	    - close():  It is used for closing a certain window or tab of the browser which was previously opened.
	    - focus():  It is used to give focus to an element in the current window.
	    - open():  It is used to open a new tab or window with the specified URL and name.
	    - prompt():  It is used to display a dialog with an optional message prompting the user to input some text.
	- stop():  It is used to stop the window from loading resources in the current browsing context.
