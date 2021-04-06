# HTML Links & Introduction to CSS Layout

In html you this is how you add a link ` <a href="you copy the url into here">Name the link</a> `.

***CSS*** There are so many features to use in setting the layout

controlling the elements positions : `position:static` ,`position:relative` ,`position:absolute` ,`position:fixed` .

Overlapping elements: `z-index` .

Floating elements : `Float:left`. you can creat multi columns using this element.

Controling the size of your page and considering the users screen sizes and resolutions.

liquid layouts and grids, and the frameworks.

# Functions, Methods, and Objects

***Functions***
*What?* A Function is a group of statements that perform a task. *Why?* can be reusable and it splits the code into smaller tasks in order to be easily controlled. *How?* `Function Name(Parameter){code};` , and we can call it when needed.

When defining a variable inside the function /*Locally* it's not defied out side the function/*Globally* ; meaning you need to redefine it in order to use it. But the globally defined variables are defined inside the functions.

example:

```
function getVolume(length, width, height){
    var volume = length * width * height;
    return volume;
}
var tankSize = getVolume(3, 1, 1);
console.log(tankSize);
```

***Objects***
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. *Variables become PROPERITIES and functions become METHODS*.

# 6 Reasons for Pair Programming

***What?***
Pair programming, a technique common to many agile work environments it is the way we foster a collaborative environment while developing key industry skills.

***Why?***

1. Greater efficiency.
2. Engaged collaboration.
3. Learning from fellow students.
4. Social skills.
5. Job interview readiness.
6. Work environment readiness.

***How***
>While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

References :

* Ch.4 & Ch.15 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.3 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.
* [URL](https://www.codefellows.org/blog/6-reasons-for-pair-programming/) .