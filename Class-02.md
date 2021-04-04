# HTML Text
### Describing the structure of html :

* There are 6 levels o headings in html , h1-6 the bigger the number the smaller the header .

```
 <h1>main header </h1>
 <h2>a smaller header </h2>
 <h6>the smallest header </6>
```
* 

 | Tags      |  Use or Idication |
 |-----------|-------------------|
 | `<p></p>` | Paragraph         |
 | `<b></b>` | Bold              |
 | `<br></br>`| To start a new line |
 | `<hr></hr>`| To make a horizontal rule as a break |
 | `<strong></strong>` | Important content, SHOWN BOLD |
 | `<em><e/m>` | Emphasis, SHOWN IN ITALIC |
 | `<blockquote></blockquote>` | To quote a paragraph |
 | `<q></q>` | To quote a sentence within the paragraph |
 | `<abbr></abbr>` | Indicates abbreviation or acronym |
 | `<cite></cite>` | Citation |
 | `<dfn></dfn>` | Defining instance |
 | `<adress></adress>` | Adress |
 | `<del></del>` & `<ins></ins>`| Delete & Insert |
 | `<s></s>` | No longer accurate or relevant | 

* White space collapse : we benifit from this to easily follow the code.

# CSS
## What , Why & How ?.
*Cascading Style Sheet*, we use css to style our website simply by selecting the elements and declare them. We can add css by:
+ Internally within the opening tag eg. `<p style= color:"red";>paragraph</p>`.
+ Internally  using `<style></style>` eg. `<p> <style>{ color:red;} </style> </p>`.
+ Adding an external file `<link href="css/styles.css" type="text/css" rel="stylesheet" />`.

Adding an external file is prefered , we can select the elements by : [check this](https://www.w3schools.com/cssref/css_selectors.asp)

# Basic JS instructions
The script consists of statements  each statement should end with `;` exept for the code blocks like if we are using `if (condition){code}` no need to add `;` after the curly brackets.

* To write a single line comment add `//` before your comment , and to write a multi line comment add `/*` Comment `*/` .

* You can define variables `var variableName;` and then assign the variable's value `variableName=5`. data types of the defined variable could be a number , a string or a boulean.

* Arrays are another type of variables, we use them when asignins a list of values to a variable

* How to write if conditions 
 ```
 if (condition) {
     code
 }
 else if ( another condition){
     code  
 }\\this is not nesesary
 else {
     code 
 }\\this also is not nesesary
 ```
 if the condition is true then the if code would run , if the another condition is true the else if code will run and if the both conditions are false the else code will run.
 
 The condition is written using comparasion operators and logical operators * Those are explaind [Here](Read05.md)*.

References :
* Ch.2 & Ch.4 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.2 & Ch.4 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.
* [Check this URL](https://chris.beams.io/posts/git-commit/).
