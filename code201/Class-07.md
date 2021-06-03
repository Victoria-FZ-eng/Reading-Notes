# Tables in HTML

* Using `<table> </table>` tags, raw bye row `<tr></tr>` and then filling the data `<td></td>`.
* Use `<th></th>` for the head of the  column or row.
* `colspan='number';` to merge cells in the table accross the column, the number indicates how many cells to merge.
* `rowspan='number';` to merge cells in the table accross the row, the number indicates how many cells to merge.
* To organize you code use `<thead></thead>` for the table headings, `<tbody></tbody>` for the filling data & `<tfoot></tfoot>` for the footer. this will help you during styling in the css file.
* Specifying the attributes: width , spacing , border and bgcolor (background color) for the styling.

# Object Oriented Programming in JS

* Define a blank object `const objectName = new Object ();`.
* Adding and updating properties and methods later on by `objectName.newProperty='value',` or `objectName.newFunction= function (){ code; },` .
* Using function as a template to creat objects ; example

```
function objectName (property1, property2, property3){
    this.property1=value;
    this.property2=value;
    this.property3=value;
    this.addMethod = function(){
        return property3 - property2;
    };
}
```

OR  `const objectName = new object (here you type the values of the properties);`.
* Add properties by `object.propertyName = value;` and the value can be number, string or boolean.
* Delete prooperties by ` delete object.propertyName;` .
* `this` keyword is only used within the function.
* Ability to store variables and arrays in the objects.
* Arrays are a special type of objects.

## Build-in Objects

These offers different tools to help writing the script of web pages . Mainly there are 3 groups:

1- Browser object model.
2- Document object model.
3- Global java script objects.

## Data types in java script 

* Simple ( string, nnnumber, boolean, undefined & null).
* Complex datatypes (Objects).

**Here are some usefull functions**

![image1](../img/Screenshot(36).jpg).

![image2](../img/Screenshot(37).jpg).

And check out these [Helper Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random).

**Objects and timing**

![time functions](../img/Screenshot(38).jpg)

***Check the link (URL) below that is listed in the references for some examples that explain this whole title of java script objects***

References :

* Ch.6 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.3 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.
* [URL](https://github.com/codefellows/domain_modeling#domain-modeling)