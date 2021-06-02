
# HTML

## What, Why & How ?.
*Hyper Text Markup Language*; text documents, that describes the structure of the pages using elements. And elements are made-up from tags (eg. `<p> paragraph <\p>`)
There have been several versions of html and you can notice them from the html text eg. for the HTML5 , we use `<!DOCTYPE html>` for the declaration
An explaining example:

```
<!DOCTYPE html>
<html>
 <head> <!--This is an opening tag-->
  <title> Example </title>
  <!-- This is how you write a comment on html. The head part usually contain some information and they dont show up to the users-->
  <!-- there are another type of tags , that is self closing like the <img src="link"\> tag -->
 </head><!--This is a closing tag-->
 <body> <!-- what is written in this part appear to the user -->
  <header>
  <h1>Title </h1> <!-- here is the header of the page , the headers can be witten from h1 to h6 the larger the number the smaller the header --> 
  </header>
  <main>
   <p> This is a paragraph tag </p> 
   <p id="one"> you can id or class your elements </p>
   <ul class="first"> 
     <li> the list tag is a block element same as the paragraph tag and the unorders list tag </li>
     <li> <a href=" you can add a link using the a tag"> Link </a> </li>
     <li> the anchor tag is an example of the inline elements </li>
   </ul>
   <iframe
   width="700"
   height="450"
   src="link off any html page">
   </iframe> <!-- this is used to add a web page inside your page like if you want to add the direction from google map -->
   <footer> copy rights </footer>
 </body>
 </html>
```
There are so many other tags that are used to group some elements like the `<nav>` , `<div>` , `<hgroup>`, `<article>` , `<aside>`, etc....

Escape characters :
+ ( &lt; ) by typing `&lt;`.
+ ( &gt; ) by typing `&gt;`.
+ ( &amp; ) by typing `&amp;`.
+ ( &quot; ) by typing `&quot;`.
+ ( &cent; ) by typing `&cent;`.
+ ( &pound; ) by typing `&pound;`.
+ ( &yen; ) by typing `&yen;`.
+ ( &euro; ) by typing `&euro;`.
+ ( &copy; ) by typing `&copy;`.
+ ( &lsquo; ) by typing `&lsquo;`.
+ ( &rsquo; ) by typing `&rsquo;`.
+ ( &ldquo; ) by typing `&ldquo;`.
+ ( &rdquo; ) by typing `&rdquo;`.
+ ( &times; ) by typing `&times;`.
+ ( &divide; ) by typing `&divide`. 

*Note*: Before you make your website make sure to understand the targeted audience and to communicate with them properly by the styling and the designing , alwaays plan your page make a map for your site and a wireframe.
*Note*:extra JavaScript is needed to make the HTML5 work on old versions.


# JavaScript

## What, Why & How ?.
JS is a programming language that allows the dynamic interaction with the browser.
In order to write your script adequetly you need to set your goals , break them them down into several tasks, and always remember how to think like a computer.
you can *Add Your JS* :
- Internally using `<script> code </script>` tags.
- Externally by creating and adding **the app.js** file `<script src="relative path for thr app.js file"> </script>` , and this is the most preffered.

References :

* Ch.1, 8, 17 & 18 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* The introduction &  Ch.1 / *JavaScript & JQuery:Interactive Front-End Development. JON DUCKETT*.