# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS:

> Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

> A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

### Setting up:

> The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script.

### Drawing a line chart:

> To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

### Drawing a pie chart:

> Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element,Next, we need to get the context and to instantiate the chart,Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section.

### Drawing a bar chart:

> Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element,Next, we retrieve the element and create the graph.

![](https://miro.medium.com/max/3648/1*ZxZMc4n6XJxlNjA-p4WAKg.png)

___

# Basic usage of canvas:

* The (canvas) element:

> At first sight a (canvas) looks like the (img) element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the (canvas) element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

* Fallback content:

> Providing fallback content is very straightforward: just insert the alternate content inside the (canvas) element. Browsers that don't support (canvas) will ignore the container and render the fallback content inside it. Browsers that do support (canvas) will ignore the content inside the container, and just render the canvas normally.

* Required (canvas) tag:
> As a consequence of the way fallback is provided, unlike the (img) element, the (canvas) element requires the closing tag (canvas). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

___

# Drawing text:

![](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text/baselines.png)

> here are some more properties which let you adjust the way the text gets displayed on the canvas:

* font = value
* textAlign = value
* textBaseline = value
* direction = value