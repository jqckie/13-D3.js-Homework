# D3-Obesity-Interactive-Graph

## Instructions

* Use `python -m http.server` to host an interactive analysis of [2014 ACS 1-year estimate data](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml) on poverty and obesity at `localhost:8000` in your web browser.

## Background

Analyzing rates of income, obesity, poverty, etc. by state using D3.

## Details

Creating a scatter plot between multiple data variables.

Using D3 to create a scatter plot that represents each state with circle elements. 
Pulling in the data from `data.csv`.

* Including state abbreviations in the scatter plot circles.

* Creating axes and labels to the left and bottom of the chart.

Placing labels with click events in the scatter plot to allow users to decide which data to display. 
Animating the transitions for circle locations as well as the range of your axes. 

* Implementing `d3-tip.js` [tooltips by Justin Palmer](https://github.com/Caged) to reveal a specific element's data when the user hovers their cursor over the element.
