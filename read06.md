# Reading 06

## Chapter 3 

Object Literals
(100-105)

Objects group together a set of variables and functions to create a model of something you would recognize from the real world.

A property is when a variable is part of an object.

Properties describe objects.

 ie:

    * Name of a hotel
    * Number of rooms it has

a **method** is whena function is part of an object.

* methods are a representation of tasks that are associated with the object.

Properties and methods have a name and a value called a **key**

two keys cannot belong to an object.

properties of a value:

1. string

2. number

3. boolean

4. array

5. another object

* the value of a method is always a function

* You can access the properties or methods of an object using dot notation.

* you can also access properties using swuare brackets.

To access a property or method of an object you use:

1. The name of the object

2. followed by a period

3. Name of the propert or method you want ot access.

* **HTML** uses *attribue names* and *values*

* **CSS** uses *property names* and *values*

**In JavaScript:**

* Variables have a name and you can assign them a
value of a string, number, or Boolean.

* Arrays have a name and a group of values. (Each
item in an array is a name/value pair because it
has an index number and a value.)

* Named functions have a name and value that is a
set of statements to run if the function is called. 

* Objects consist of a set of name/value pairs
(but the names are referred to as keys).

>`var hotel = {`
>
>   `name: 'quay',`
>
>   `rooms: 40,'`
>
>   `booked: 25,`
>
>   `gym: true,`
>
>   `roomTypes: ['twin, 'double'],`
>
>   `checkAvailability: function() {`
>
>   `return this.rooms - this.booked;
>
>   `}`
>
>`};`


**Accessing An Object And Dot Notation**



**Period**

* The periodk is known as the member operator.