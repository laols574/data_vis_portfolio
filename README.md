# data_vis_portfolio
This tar file contains multiple data visualization projects which can be viewed through opening the "index.html" files for each project into a browser. 

Decompressing files depends on your OS but you can use

tar -xvf data_vis_portfolio.tar.gz

on the command line

## Assignment #4: 
### Notes
All four visualizations were rendering properly on Google Chrome. They all represent different variations of statistics for displaying UK driver fatality data and student scores data set. 

### Included files

* index.html - this file contains all HTML for the plots
* d3.v5.js - contains all the functions for d3
* calvinScores.js - contains small student scores data set
* ukDriverFatalities.js - contains a data set regarding UK Driver Fatalities
* a04.js - contains all javascript functions in the project

### References
https://cscheid.net/courses/fall-2019/csc444/lectures/lecture4/iteration_8.html

https://www.sitepoint.com/a-beginners-guide-to-data-binding-in-d3-js/


## Assignment #5
### Notes
This file was rendering correctly in Google Chrome. All three buttons, as 
well as the two extra buttons for the extra credit, were providing accurate
transitions. They graph the relationship between SAT and ACT scores, with color representing GPA. 


### Included files

* index.html - This file contains the HTML for the project. Its elements
are the ones manipulated in order to present visualizations. 
* a05.js - This file contains all the functions necessary to produce the 
visualization, including the coloring and scaling. 
* buttons.js - This file contains all the functionality necessary for 
creating the buttons as well as the functions to change the visualization
behavior. 
* d3.v5.js - all d3 functions
* calvinScores.js - the data 


### References
For scales: 
- https://github.com/d3/d3-scale#scaleQuantize
- https://github.com/d3/d3-scale#continuous_domain
- https://www.tutorialsteacher.com/d3js/scales-in-d3

For transitions:
- https://github.com/d3/d3-transition


## Assignment #7

### Notes
Graphs are rendering properly in Chrome. Brushing and linking is working in Chrome. This graph shows the "Iris" dataset, displaying the relationship between sepal and petal traits as well as species.  


### Included files

* a07.js - contains all functionality for creating graphs, linking and brushing
* index.html - contains the html template for d3 objects
* iris.js - contains all data
* d3.v5.js - d3 functions


### References
Troubleshooting:
https://stackoverflow.com/questions/36356201/filter-nodes-by-weight-and-change-attribute
https://stackoverflow.com/questions/43646573/d3-get-attributes-from-element
https://github.com/d3/d3-selection
https://observablehq.com/@d3/mona-lisa-histogram
https://bl.ocks.org/johnnygizmo/3d593d3bf631e102a2dbee64f62d9de4

## Assignment #8
### Notes
Visualization correctly renders in Google Chrome. This visualization shows a parallel coordinates diagram, where more "crossing" between axes shows a negative relationship and "parallel" lines show a positive relationship.


### Included files

* a08.js - contains all functionality for creating graphs, linking and brushing
* index.html - contains the html template for d3 objects
* iris.js - contains all data
* d3.v5.js - d3 functions

### References

## Assignment #9

### Notes
All four buttons and their respective renderings are rendering in Google Chrome. This visualization shows a tree map, a conduit for showing tree data, of the "Flare" dataset, which is a hierarchy of a file system.


### Included files

* a09.js - This file ccontains all of the functions required to create the visualization.
* index.html - This file creates the basic html layout for the visualization elements.
* flare.js - This file contains the large data set, which represents a tree-like file system.
* test-cases.js - This file contains the smaller sample tree data sets.
* solution-screenshots - This folder contains various screenshots of what the final tree structure is supposed to look like.


### References
* https://jalevine.bitbucket.io/csc444/assignments/2020/03/25/A09.html

## Assignment #10

### Notes
All four visualizations correctly render in Google Chrome. These visualizations show isocontours for hurricane data. 


### Included files
* a10.js - The file with all functions to create contours.
* index.html - The basic HTML template file, containing the outline of the project.
* data.js - The dataset, containing Hurricane Isabel dataset
* d3.v5.js - The D3 library.


### References
https://jalevine.bitbucket.io/csc444/lectures/2020/04/06/L21.html


## Assignment #11

### Notes
Visualization is rendering as necessitated in Google Chrome. This visualization is an editable transfer function which can be used to show a few different sets of flow data. 


### Included files

* a11.js - This file contains all the javascript necessary to render the visualization
* d3.v5.js - This file contains D3.
* index.html - This is the HTML file which acts as a template for the visualization.
* volren.js - Javascript necessary for volume rendering.
* vtk.js - Javascript necessary for volume rendering.


### References
https://bl.ocks.org/denisemauldin/538bfab8378ac9c3a32187b4d7aed2c2
https://github.com/d3/d3-scale-chromatic

## Assignment #12
### Notes
All visualizations are correctly rendering in Google Chrome. These visualizations show vector field via color mapping and glyphs


### Included files

* a12.js - This file contains all of the functionality for creating the visualizations
* d3.v5.js - This file contains D3.
* index.html - This is the HTML file which acts as a template for the visualization.
* data.js - Contains the flow data.


### References
for the markers:
http://bl.ocks.org/dustinlarimer/5888271

https://blockbuilder.org/anees715/72d4293c3ccbae8d272260586d21cc4c

http://jsfiddle.net/Tymek/9nbwS/

for the rotation:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan2
