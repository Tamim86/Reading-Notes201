# Tables

## Tables represent information in grid format

### <table>
###     <tr>
###         <td>content</td>
###     </tr>
### </tables>

## <th> = table heading
## <th scope ='row or col1><th>
### *scope attribute used to indicate it is header for row or column

## colspan => colspan is an attribute that can be used on <td> or <th> to indicate how many columns the cell should run across
## row span attribute used to indicate how many rows the cell should span down

# long tables
## <thead> => the heading of the table ,ust sit inside the <thead>
## <tbody> => the body of the table should sit inside <tbody>
## <tfoot> => the footer should sit inside <tfoot>
### <table>
 ### <thead>
 ### <tr>
 ### <th>Date</th>
 ### <th>Income</th>
 ### <th>Expenditure</th>
 ### </tr>
 ### </thead>
 ### <tbody>
 ### <tr>
 ### <th>1st January</th>
 ### <td>250</td>
 ### <td>36</td>
 ### </tr>
 ### <tr>
 ### <th>2nd January</th>
 ### <td>285</td>
 ### <td>48</td>
 ### </tr>
 ### <!-- additional rows as above -->
 ### <tr>
 ### <th>31st January</th>
 ### <td>129</td>
 ### <td>64</td>
 ### </tr>
 ### </tbody>
 ### <tfoot>
 ### <tr>
 ### <td></td>
 ### <td>7824</td>
 ### <td>1241</td>
 ### </tr>
 ### </tfoot>
### </table>


# Functions, Methods and objects
## # Objects

## Objects group a set of variables and functions together in order to achieve something recognizable

### Variables inside objects called *properties*

### Functions inside objects called *Methods*

### var hotel = {
### name:'Veda'
### empoyees:80
### rooms:40
### function (){
###   code to execute;
###   }
### }

### The elements on the leftside (name,employees,rooms,function) are *Keys*, while the elements on the right side are values('Veda', 80, 40)


## Literal Notation is the easiest and most popular way to create Objects, just like the above hotel example

## Objects properties and methods can be accessed by '.' or '[]'
### var hotelName = hotel.name
### var hotelRooms = hotel['rooms']


# DOM [Document Object Model]
## basically DOM specifies how browser should create model of an HTML page and how J.S can access & update the content of the webpage on the browser.

### DOM is not part of HTML or J.S it is a separate set of rules implemented by browsers makers.