# Reading: Basics of HTML, CSS & JS

## Chapter 2

**Headings**

`<h1>`
`<h2>`
`<h3>`
`<h4>`
`<h5>`
`<h6>`

**Paragraphs**

`<p>`

**bold and italic**
`<strong>`
`<b>` Bold

`<i>` italic
`<em>`

**Superscript & Subscript**

`<sup>`
The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22


`<sub>`

The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H2 0.


## Chapter 10

### CSS

* The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
* CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
* A CSS rule contains two parts: a selector and a declaration.
  * Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
  * Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.
* CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

### Using external CSS

**`<link>`**
  * The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element. It should use three attributes:

**`<href>`**
  * This specifies the path to the CSS file (which is often placed in a folder called css or styles).
  
**`< type>`**
  * This attribute specifies the type of document being linked to. The value should be text/css.
  
**`<rel>`**
  * This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
  
### Using Internal CSS

**`<style>`**
  * The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.
  
### CSS selectors

`* {}`
  * Universal selector. applies to all elements in the page.


## Chapter 2 Basic JavaScript

**JavaScript runs where it is found in the HTML**

* When the browser comes across a <script> element, it stops to load the script and then checks to see if it needs to do anything.

**Statements**

* A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.
* The semicolon also tells the JavaScript interpreter when a step is over, indicating that it should move to the next step. 

**What is a Variable?**

* A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
`var quantity;`
  * now you need to assign a value to the variable
    * `quantity = 3;`
    
**Data Types**

* Numeric data type
  * `0.75`
* String Data Type
  * `'hi, Ivy!'`
* Boolean Data Type
  * `true`

## Comparison Operators

`==` is equal to

`!=` is not equal to

`===` strict equal to

`!==` strict not equal to

`>` Greater Than

`<` less than

`>=` greater than or equal to

`<=` less than or equal to




