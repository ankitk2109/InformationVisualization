# Irish School Explorer using Vega-Lite

Interactive dashboard visualizatioon to analyse and explore Ireland's primary schools.

## How to view the visualization?

Please visit https://vega.github.io/editor/#/custom/vega-lite and paste the any json file in code section to view the visualization.

__Visualization 1:__
* With the aid of the topojson data sort, a geo-shaped map is initially built and, at the top, a point map is layered over with the latitude and longitude provided.

* Each point is an Irish school and is further differentiated by the sex field (Boys, Girls and Mixed). Finally, the size of each point is compared to the distinct value of the set.

__Visualization 2:__
* On a point Map, a layered bar graph with count of the field Roll Number on the y axis and the Total number of students on the x axis is generated.

__Visualization 3:__
* Stacked bar graph with the county on the y axis and the number of schools on the x axis is formed.

* The color sequence is defined with Boys first, then with Girls, and finally with Mixed Gender.

* All static visualization are then concatenated vertically and horizontally. Finally the structure is ready.

## Interactions:

__Interaction 1:__
* On a point map, a selection filter known as select gender is specified, which will show the performance of the corresponding category only when single clicked on the Gender field.

* The filter then binds to the legend and settles globally.

__Interaction 2:__
* On a layered bar chart, a brush selection known as a form of interval is generated so that you can pick the number of students on the graph.

__Interaction 3:__
* On a stacked bar graph, a selection filter called as select county is defined, where selected multiple counties will show the result of those selected counties that were resolved globally.

## Output Vizualization: 
__After applying all the filters an interactive dashboard is ready to visualize__

![Interactive Visualization Video](https://github.com/ankitk2109/InformationVisualization/blob/master/Interactive_IrishSchool_Viz/output/InteractiveGif.gif)
