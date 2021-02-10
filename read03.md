# Reading Notes 3

## Chapter 3 "Lists" (62-73)

**There are four different types of lists**

1. Ordered Lists `<ol>` `<li>`
    * this is a list with every item numbered. like the one im making right now.
    * `<li>` (list item ) is where all your content would go when making a list.
2. Unordered lists `<ul>`
    * this are lists without numbers. like the one im using to describe the lists
    * the same `<li>`is used for unordered list. but the ul tells it that its unordered. so to not add numbers
3. Definition lists
    * these lists use a set of terms along with definitions for each of the terms.
    * `<dt>` `<dd>`
4. Nested List
    * this is when you add another tab with a * which creates a list
        * within a list

**Boxes**

* in CSS we can make boxes that we can control by:
    * adjusting the dimensions
    * creating borders around the box
    * set margins and padding
    * show and hide boxes

**How we size these boxes**

* pixels (px)
* percentages (%)
    * adjusts based on the relative size of the window or if its incased in another box.
* ems
    * adjusts size based on the size of the text.


**How do we limit width and height?**

* we can limit how big or small a box can get in css by using
    * `min-width: 450px;`
    * `max-width: 650px;`
    * `min-height: 450px;`
    * `max-height; 650px;`


**OverFlow**

* When your text is too big for a box there are two options

>p {
>  
>overflow: hidden;} 
1. hidden
    * This option will hide what is too big for the box

2. scroll
    * this adds a scroll bar inside the box in order to see all the content.


**Editing boxes**

1. Border
    * The border seperates boxes from one another along the edge
    > border-width: 2px;
    >
    > border-width: thick;
    >
    > border-width: 1px 4px 12px 4px;
    >
    > top right bottom left. clockwise around the box
    >
    > border-style: solid; / dotted/ dashed / double / groove/ ridge / insert / outset
    >
    >border-color: red;


2. Margin
    * this is the gap between two borders

3. Padding
    * this is the space between the content and the box

4. Text align
    * in oder to move text around inside the box use
    > text-align: center;

**Change inline/block (display)**

* Inline
    * this causes a block elemeent to act inline
    * you used this nav
    > display: inline;

* Block
    * this causes the element to act like a block element.
    > display: block;

**Box Shadows**

1. Horizontal Offset
    * sets a shadow to the left

2. vertical offset
    * sets a shadow at the top of the box

3. blur distance
    * a shadow like a border

4. spread of shadow
    * how far the shadow will go
    > moz-box-shadow: inset 0 0 10px #777777;
    >
    > webkit-box-shadow: inset 0 0 10px #777777;
    >
    > box-shadow: inset 0 0 10px #777777;} 

**Round Corners of a box**

> border-radius: 5px, 10px, 5px, 10px;
>
> or
>
> border-radius: 5px;

## Chapter 4 (162-182)

**If.. Else**

* if the statement is true it runs the first code
* if its false then it runs the second code (else)

**Data Types**

1. string-text
2. number-number
3. boolean-true or false
4. null-empty value
5. undefined- no var detected

**Loops**

1. For
    * typically used as a counter. the most common loop
    * can be used to loop through items in an array.

2. While
    * use this one when you dont know how many times exactly you want to run the loop. mainly if another action would stop the loop
3. Do While
    * same as while loop but it will always run the code inside the curly braces at least once. 

**Loops Counter**

* initializtion
    * this sets the starting point at 0
    > var i = 0;

* condition
    * this causes the loop to run 10 times before stopping
    > i < 10;

* update
    * adding to the counter
    > i++

> for (var i = 0; i<10; i++) {
    
* the loop will start at 0 and count to 10 adding 1 for each loop.
> 0 1 2 3 4 5 6 7 8 9 

**Stop or continue loop**

1. break
    * terminates the loop
2. continue
    * continues the loop

