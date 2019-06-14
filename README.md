# Dashboard-Healthcare-Disparities-US


#### Dashboard

Animated
![x](assets/images/animated.gif)


Tooltip
![x](assets/images/tooltip.gif)



Responsive
![x](assets/images/responsive.gif)


# Background

 You're tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings.
The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.
The data set included with the assignment is based on 2014 ACS 1-year estimates: https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml, but you are free to investigate a different data set. The current data set incldes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."

# Goals

You need to create a scatter plot between two of the data variables such as Healthcare vs. Poverty or Smokers vs. Age.
Using the D3 techniques we taught you in class, create a scatter plot that represents each state with circle elements. You'll code this graphic in the app.js file of your homework directory—make sure you pull in the data from data.csv by using the d3.csv function..


Include state abbreviations in the circles.


Create and situate your axes and labels to the left and bottom of the chart.


Note: You'll need to use python -m http-server to run the visualization. This will host the page at localhost:8000 in your web browser.

More Data, More Dynamics
You're going to include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.

Hint: Try binding all of the CSV data to your circles. This will let you easily determine their x or y values when you click the labels.


Incorporate d3-tip
While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the d3-tip.js plugin developed by Justin Palmer—we've already included this plugin in your assignment directory.


# Run Locally

Run this command git clone https://github.com/Piterbrito/Healthcare-DisparitiesUS--Dashboard/

Make sure you have installed in your computer all libraries used above

Double check if you are in the right directory in you terminal ...that often cause errors

Terminal Should be addressed at folder: flask_app

Run the command: python app.py in your terminal

Copy the output link and paste in your Browser

You are now in the dev environment and you can play around
