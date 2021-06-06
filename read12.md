# Charts 
##  Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

### First step is to download charts.js, then link it to the HTML page.
### <!DOCTYPE html>
### <html lang="en">
###     <head>
###        <meta charset="utf-8" />
###        <title>Chart.js demo</title>
###        <script src='Chart.min.js'></script>
###    </head>
###    <body>
###    </body>
### </html>

## Drawing a line chart
### To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

### <canvas id="buyers" width="600" height="400"></canvas>
### Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element:

### <script>
###     var buyers = document.getElementById('buyers').getContext('2d');
###     new Chart(buyers).Line(buyerData);
### </script>

## Drawing a pie chart
### Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element:

### <canvas id="countries" width="600" height="400"></canvas>
### Next, we need to get the context and to instantiate the chart:

### var countries= document.getElementById("countries").getContext("2d");
### new Chart(countries).Pie(pieData, pieOptions);


## Drawing a bar chart
### add bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:

### <canvas id="income" width="600" height="400"></canvas>
### Next, we retrieve the element and create the graph:

### var income = document.getElementById("income").getContext("2d");
### new Chart(income).Bar(barData);

## The <canvas> element
### The difference between <img> and <canvas> that <canvas> element doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height
