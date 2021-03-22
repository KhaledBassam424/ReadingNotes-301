**What is jQuery**
 
jQuery website defines jQuery (jQ) as “jQuery is a fast and concise JavaScript Library that simplifies HTML document traversing, event handling, animating, and Ajax interactions for rapid web development.”.
 
jQuery is not a programming language instead it is a cross-platform JavaScript library. There are many other JavaScript libraries available like MooTools, Knockout or even Angular (Though Angular uses TypeScript, it compiles to JavaScript at the end) and jQuery is one of the most popular among them.
 
jQuery is a fast feature-rich JavaScript library. It is created to help programmers with creating common UI and take care of browser compatibility issues more easily.
 
jQuery, in fact, is nothing but JavaScript. All the code you write in jQuery is converted to JavaScript internally. One line of code written using jQuery may be equal to many lines of code written using JavaScript which means programmers will have to write only lesser lines of code.
 
To start using jQuery on your page, you need to include one line of code in the header of your page like,

`<script src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-3.2.1.min.js"></script >`   




> What is jQuery Selector?

A jQuery selector is a way of selecting an HTML element using jQuery. After you select an HTML element Using jQuery, you can perform various operations on it. You can select single as well as the group of HTML elements according to your needs.

The operation of selection specifies with the DOM hierarchy from where the jQUery starts searching and selecting the HTML element.




> Why You Should Use jQuery Selector?

You should use the jQuery selector to access and manipulate the HTML element. Without selecting the exact element you cannot perform the required task with the required element.

The jQuery library offers selectors features to select any element in a single form or in group form. JQuery provides various effects and manipulation features to apply to HTML elements. The jQuery is the popular language to use and perform various manipulations.



> How to Use jQuery Selector to Select HTML Element Using jQuery?


A selector of jQuery starts from the dollar($) sign with a parenthesis – $() after it. Below are the various selectors you can use to select and manipulate an HTML element.




### Types of selectors in jQuery :

1. > Select All Element

If you want to apply a script to all HTML elements in one go, you can use the (*) selector. It will automatically apply the operation to all the HTML elements on a single page.


```<script type="text/javascript">
$(document).ready(function(){
   $("*").css("color", "#000");
});
</script>
```

 2. >   Select Element By ID:

You can select an HTML element using the id which is unique for any element on a page. Use the hash(#) sign before the id name to grab the required HTML element.


```<script type="text/javascript">
$(document).ready(function(){
    $("#txt-selectbyid").css("color", "red");
});
</script>
<p id="txt-selectbyid">This is a paragraph.</p>
```


3. > Select Element By Class:


You can select an HTML element using the class with jQuery on a page. Use the dot(.) sign before the class to access the required element.

A class name not required to be unique and you can use the same class name for many HTML elements. This applies the script to all the elements with the same class name.

```<script type="text/javascript">
$(document).ready(function(){
    $(".txt-selectbyclass").css("background", "red");
});
</script>
<p class="txt-selectbyclass">This is a paragraph.</p>
```


> other ways foe selecting elements : 

1. Select Element By Attribute
2. Select Element By Name
3. Select the First Element