# Reading Notes 07 HTML Tables, JS Construction Functions

## Chapter 6: Tables (126-145) 

* we represent tables in a grid format.

examples:
1. TV Schedules
2. Sports Results
3. Financial Reports

* Table cells refer to each block in a grid

### KEY TERMS

`<table>`

* creates the table

`<tr>`

* (table row) starts a new row

`<td>`

* (table data) where you would write the info for each block

`<th>`

* (table head) represents the heading for either a column or a row

`<td colspan="2">`

* takes up two spaces on a row

`<td rowspan='2'>`

* Vertically takes two spots

**LONG TABLES**

`<thead>`

* same as th just a long boi

`<tbody>`

* put everything in this tag to make it a long chart

`<tfoot>`

* Gives you a long foot yo, you can use this for totals

## Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

`Var hotel = new Object();`


`hotel.name = "Royal sands";`


`hotel.rooms= 40;`


`hotel.booked = 25;`


`hotel.checkAvailibality = function


`() {`


`return this.rooms - this.booked;`


`}`


* two ways to update the value of properties

1. dot notation
    * add properties to the onject but gives it a new value

2. square brakets
    * updates the properties of an object but not its methods

`delete hote.name;`

* used to delete a property

`hotel.name = '';`

* used to clear a value

`function Hotel(names, rooms, booked) {`
`this.name = name;`

`this.rooms = rooms;`

`this.booked = booked;`

` this.checkAvailability = function() {`

`return this.rooms - this.booked;`

`};`

`}`

examples:

    `var quayHotel = new Hotel('Quay', 40, 25):`

* the first object is called quayHotel. its name is 'Quay' and it has 40 rooms, 25 of which are booked

    `var parkHotel = new Hotel('park', 120, 77);`

* this object is called parkHotel. it name is 'Park' and it has 120 rooms, 77 are booked

