# HTML Text
### Describing the structure of html :

* There are 6 levels o headings in html , h1-6 the bigger the number the smaller the header .

```
 <h1>main header </h1>
 <h2>a smaller header </h2>
 <h6>the smallest header </6>
```
* 

 | Tags      |  Use or Indication |
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
 | `<adress></adress>` | Address |
 | `<del></del>` & `<ins></ins>`| Delete & Insert |
 | `<s></s>` | No longer accurate or relevant | 
 | `<sup></sup>` | Supscript |
 | `<sub></sub>` | Subscript |

* White space collapse : we benefit from this to easily follow the code.

# CSS
## What , Why & How ?.
*Cascading Style Sheet*, we use css to style our website simply by selecting the elements and declare them. We can add css by:
+ Internally within the opening tag eg. `<p style= color:"red";>paragraph</p>`.
+ Internally  using `<style></style>` eg. `<p> <style>{ color:red;} </style> </p>`.
+ Adding an external file `<link href="css/styles.css" type="text/css" rel="stylesheet" />`.

Adding an external file is preferred , we can select the elements by : [check this](https://www.w3schools.com/cssref/css_selectors.asp)

# Basic JS instructions
The script consists of statements  each statement should end with `;` exept for the code blocks like if we are using `if (condition){code}` no need to add `;` after the curly brackets.

* To write a single line comment add `//` before your comment , and to write a multi line comment add `/*` Comment `*/` .

* You can define variables `var variableName;` and then assign the variable's value `variableName=5`. data types of the defined variable could be a number , a string or a boulean.

* Arrays are another type of variables, we use them when asigning a list of values to a variable

* How to write if conditions 
 ```
 if (condition) {
     code
 }
 else if ( another condition){
     code  
 }\\this is not necessary
 else {
     code 
 }\\this also is not necessary
 ```
 if the condition is true then the if code would run , if the another condition is true the else if code will run and if the both conditions are false the else code will run.
 
 The condition is written using comparision operators and logical operators *Those are explained [Here](../code102/Read05.md)*.

# Commit Messages
## Why & How ?.
We basically write commit messages in order to organize our changes , so to easily track the changes.Here are the rules of writing commit messages:
1. Separate subject from body with a blank line.
2. Limit the subject line to 50 characters.
3. Capitalize the subject line.
4. Do not end the subject line with a period.
5. Use the imperative mood in the subject line.
6. Wrap the body at 72 characters.
7. Use the body to explain what and why vs. how.



References :

* Ch.2 & Ch.10 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.2 & Ch.4 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.
* [Check URL](https://chris.beams.io/posts/git-commit/).
