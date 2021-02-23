# Reading 12 Chart.js API


to add JS on page

`script src='Chart.Min.js'></script>`

<hr>

Adds Chart to Page

`<script>`

`var buyers = document.getElementById('buyers').getContext('2d');`

`new Chart(buyers).Line(buyerData);`

`</script>`

<hr>

Add labels and data sets in JS to edit the chart. The above one creates a line chart

<hr>

a closing `</script>` tag is required

`fillRect(x, y, width, height)`

created a rectangle that is solid or filled

`strokeRect(x, y, width, height)`
draws an empty or outlined rectangle

`clearRect(x, y, width, height)`
makes a clear rectangle

`beginPath()`

Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

`Path methods`

Methods set to different paths for objects

`closePath()`

adds a straight line to the path, going to the start of the current sub-path.

