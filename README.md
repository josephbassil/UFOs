UFOs

1- We downloaded the JavaScript file (data.js) containing all the data needed to populate our HTML table
2- We created app.js (in VS code) in our repo folder where we'll write the code that builds the HTML (web) table and fills it with our data (data.js)
3- We created our index.html file where everything will be displayed, created our style.css and organized our UFOs file


We are going to create a webpage that will allow users to view the data (HTML)
and a dynamic table that will present it (JavaScript)
So let's do all the stroyboarding (webpage layout) first:
-We are going to use Jumbotron for the header, and the grid system for the filters and table
-We also have an idea of how many columns we want in each table (class='col-md-3 & class='col-md-9')

Now we begin coding with JavaScript and import the data and reference it with a variable:
[JavaScript Code] const tableData=data;

And then we referenced the HTML table using d3, telling JavaScript to look for the <tbody> tags in the HTML
NB: We did not create the HTML yet but we already know that our table will fit in the <tbody> tag
[JavaScript Code] var tbody=d3.select('tbody');
  
The array of our data is too large so we are going to need to iterate (loop) through it
function buildtable(data) {}
In this function we wanna clear any pre-existing data, loop through our data and assign every object in our data.js
to a row while assigning each value in our object to a cell
  
So now we have a a long table displaying all the UFO sighting, so we are going to use D3 (Data-Driven Documents), a JavaScript library to enable filtering by date. We do that by adding a user clicking button to our HTML page.

  After accomplishing all that, building our filtered data table.
  it's time to build the HTML page where we're showcasing our work. There will be #filter-btn and #datetime id nested into
  our HTML tags 
  in our index.html file, we created the basic HTML code and added a link to Bootsrap CDN which will help us organize our webpage into containers and stylesheet. These links were added before diving into our body
 
  in our body tag, we first created a nav bar in <div>. Then we added jumbotron in another <div> section to add visual enhancements and typed: The Truth Is Out There
  
  We created a empty table and populated the HTML webpage with basic
  Our aim is to display all our data and then use a Filter Search: Date, City, State, Country, Shape
  We used Bootstrap and CSS to add more dynamic colours to our HTML webpage
  
  
 
  

  
 
  

