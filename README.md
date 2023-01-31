# HTML Basics


### Learning Objective
* Build a basic page and identify HTML5 semantic elements
* Understand what HTML stands for
* Be able to create an HTML page from scratch
* Understand Nested HTML
* Understand the basics of The DOM

### Essential Question(s)
* How do you start an HTML document? 



### Talking Points/Road Map
* What HTML stands for
* Differences from physical media
* What the DOM is
* Writing from scratch
* nested elements


---

### What is HTML
Hyper text markup language
html is just a contract between a browser and the server that things will be displayed in a certain way

### HTML tags
html tags are style with greater than and less than signs like: `< >`
We open and close them like so `<p> </p>`

---

### Heading tags and Paragraph tags
* HTML uses `<h + number>` for a heading, h1 > h2 > h3
* there are up to 6
* `<p>` is for paragraph

### Break tag
`<br>` is html code for break, meaning a new line

### Image tags
Are used to include an image
`<img src="">`

### Lists in HTML
Creating lists in HTML is super ez theyre structured with two elements `<ul>` unordered list, and `<li>` list item.
structured like so

	<ul>
	  <li>I'm a list item</li>
	  <li>So am I</li>
	  <li>We're Unordered</li
	  <li>And we love it!</li>
	</ul>

### Tables in HTML
Tables are great for doing one thing, making tables
we structure tables with 3 main tags `<table>` to open the table `<tr>` for a table row, and  `<td>` for a table cell. We can build a table pretty quickly like so:

	<table>
	  <tr>
	    <td>Row 1, Cell 1</td>
	    <td>Row 1, Cell 2</td>
	  </tr>
	  <tr>
	    <td>Row 2, Cell 1</td>
	    <td>Row 2, Cell 2</td>
	  </tr>
	</table>
	
---

### Span and Div
`<span>` and `<div>` elements are used to define parts of a document so that they are identifiable when no other HTML element is suitable. 
Where no existing HTML element is applicable, `span` and `div` can valuably represent parts of a document so that HTML attributes such as `class` or `id` can be applied.

### Section
Works like a div

* Why is section preferred over div? Holds more info, used for grouping, a div has no special meaning 

* http://stackoverflow.com/questions/6939864/what-is-the-difference-between-section-and-div

* http://html5doctor.com/

* http://html5.validator.nu/

### Form tags
Form tags are to create HTML Forms,

```
  <html>
    <head>
      <title>Form Page</title>
    </head>
    <body>
        <form action="submit.php" method="get">
        Name: <input type="text" name="name" >
        Age: <input type="text" name="age">
        <input type="submit" >
      </form>
    </body>
  </html>
  ```
  
---
### Input tags
`<input>` tags are to define....inputs

each `input` tag will have at least two options, a `type`, and a `name`. 
There are a ton of different types that an input can have, most of them are self explanatory and for a complete list check the [w3 docs here](http://www.w3.org/TR/2014/REC-html5-20141028/forms.html#attr-input-type)

The ones that you'll be using most often are:

*  `text`
*  `password`
*  `submit`
*  `date`
*  `checkbox`
*  `radio`
*  `button`

### Select Tags

So what if you want to give the user a set number of options without cluttering up your form with a huge list.
Luckily we have the `<select>` tag!
Nested inside the `<select>` tag we have a list of `<option>` tags which do exactly what they sound like, they create options.
 
---

### What is the DOM
stands for Document Object Model...
what does that mean? 
THe webpage is the Document
Objects are stuff on the page.
The model of this is a structure that lets you access them.
Think of the Roots of a tree.

### Homework:
Create an HTML doc that includes these elements

* an internal link
* multiple headers
* a link that opens in a new tab
* an image
* a list
* a link that opens to an email address and has "Greetings!" as the subject
* a paragraph element

[Code specs for what the Document is ans what you can do with it](http://www.w3.org/TR/html5/dom.html#the-document-object)

###Resources
* [Homework Mega Hint](http://stackoverflow.com/questions/15551779/open-link-in-new-tab)


