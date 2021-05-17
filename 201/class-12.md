##  Chart.js, Canvas
![pic](https://steemitimages.com/p/3W72119s5BjWMGm4Xa2MvD5AT2bJsSA8F9WeC71v1s1fKfGkK9mMKuc3LcvF4KigbWg9UsrpEPFze2C61y2sxAxtKmWJVNFubdYCPzN1CwoEK6sdi5ZQQN?format=match&mode=fit&width=640)
## EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
###  Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.


### A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.
###  To see how to use chart.js we’re going to create a set of 3 graphs; one will show the number of buyers a fictional product has over the course of 6 months, this will be a line chart; the second will show which countries the customers come from, this will be the pie chart; finally we’ll use a bar chart to show profit over the period.
## Setting up
###  The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
## Drawing a line chart

###  To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:


## Drawing a pie chart

###  Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element: You’ll notice that this time, we are going to supply some options to the chart. Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section:


## Drawing a bar chart

###  Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element:


## Conclusion
### You can view a demo of this in action here, and if you prefer copy and paste, here is the full script: The great things about Chart.js are that it’s simple to use and really very flexible. Plus, once you’ve mastered the basics here, you’ll discover that there are tons of options listed in the documentation.

  
## Chart.js

###  
## Installation
### You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN . Detailed installation instructions can be found on the installation page.


## Creating a Chart

###  It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.


## Contributing

### Before submitting an issue or a pull request to the project, please take a moment to look over the contributing guidelines first.


## License 
