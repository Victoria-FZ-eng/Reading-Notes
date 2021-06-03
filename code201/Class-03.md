# HTML Lists
There are 3 types of lists in html :

*Ordered List*

```
<ol>
  <li>one</i>
  <li>two</i>
  <li>three</i>
</ol>
```

*Unordered List*

```
<ul>
  <li>one</i>
  <li>two</i>
  <li>three</i>
</ul>
```
*Definition List*

```
<dl>
  <dt>Hacker</dt>
  <dd>An expert or enthusiast of any kind</dd>
  <dt>Cracker</dt>
  <dd>An intruder into computer systems</dd>
</dl>
```

*Note that lists can be nested ; a list inside a list.*

# CSS Box Model
>CSS treats elements as if it lives in it's own box.

You can specify the width, height and even limit them with a minimum and a maximum value.

Every box has a mirgin , a border & a padding ; that you also can control them by numbers or percentage.
```
mirgin:30px;
border:5px;
padding:25px;
```
You can also control the text alignment `text-align:center;`, the visability of an element `visability:hidden;`, the border properties, displaying the list inline `display:inline-block;`, controlling the boxes shadows, and border corners by controling the radius.


# Control Flow with JS

## Arrays
>Arrays are another type of variables, we use them when asigning a list of values to a variable.
You can also asign the values and change them.
*Note that index values start from 0*
![array](../img/Screenshot(20).jpg) 

## Conditional statements**

+ If statement; and it is explained [Here](../Class-02.md) .

+ Switch statement ;

![switch](../img/Screenshot(21).jpg)

## Type coercion

You can change the data type of the elements in JS (weak typing).

The below listed values are considered to be false; (falsy values):

- `false;` the boolean.
- `0;` the number zero.
- ` " " ` NAN value.
- Empty value.
- A variable with no value assigned.

The below listed values are considered to be true; (truthy values):

- `true;` the boolean.
- `1;` the number.
- `"false";` or ` "0"; ` or `"true";`Strings with any content.
- Number calculation.

So,

![expressions](../img/Screenshot(22).jpg)

## Loops
The types of loops are previously explained in [Here](../Read05.md).

and here are some examples:

**For Loop**

```
for ( var i = 0 ; i < 10 ; i++){
    document.write(i);
}
```
this loop will count from 0 to 9, so runs 10 times.

**While Loop**

```
var x = 2;
while ( x <= 10 ) {
    x = x + 3;
    console.log(x);
}
```
this loop will run 3 times, with the value of x = 2 , 5 , 8 and when x =11 the while condition is false so exit loop with x=11.

**Do...While Loop**

```
var x = 2;
do {x = x + 3;
    console.log(x);}
while ( x > 10 ); 
```
here the loop will run just one time and then exit with the value of x = 5.





References :

* Ch.3 & Ch.13 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.2 & Ch.4 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.