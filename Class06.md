# Objects

As in [class 04](Class-04.md), object is defined to be a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. *Variables become PROPERITIES and functions become METHODS*.

Here is an example:

![example](img/Screenshot(34).jpg).

# DOM

The *Document Object Model* specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window, **Using DOM tree** , meaning; structuring the html into a tree using attribute nodes (tags) and text nodes(text inside tags)

**How to access and update the dom tree ?**

1- Accessing elements' nodes and traversing between them.
2- Updating the nodes, work with the html content and update the attribute values.
3- DOM queries are methods to find elements in the DOM tree,(you can return a a single value or multiple values).
4- For repeated actions , looping through each node in the nodelist (by storing the nodelist in an array).
5- You can select elements in relation to another elements using these properities ( `parentNode`, `nextSibling`, `previousSibling`, `firstChild`, `lastChild` ).
6- Updating and accessing nodes depends on what the node contains/ using html, markup, their attributes & DOM manipulation.Each way has it's advantages and disadvantages. so again depends on the node's container.

Notes : 

* If you add HTML to a page using i nnerHTML (or several jQuery methods), 
you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, 
an attacker could gain access to your users' accounts. 
* Browsers offer tools for viewing the DOM tree . 


References :

* Ch.3 & Ch.5 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.