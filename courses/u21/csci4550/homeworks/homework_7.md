---
title: "Homework #7: Stream Graphs"
subtitle: Interactive Visualization Summer 2021
course_link: courses/u21/csci4550/landing_page
course_title: CSCI4550
subpage_link: courses/u21/csci4550/homeworks/homework_7
subpage_title: Homework 7
---

* You may work on this assignment on your own or team up with a classmate.
* First, decide on an interesting, categorized, time-based dataset. For example:
  - time spent in a typical week on sleep/class/homework/eat/sports/tv/etc.
  - lines of code written during your time at RPI in different programming languages (python,c++,java,etc)
  - money spent over a typical month/year on tuition/apartment/food/travel/clothing/movies
  - something else?
\
\
___Note on dataset choice: If this assignment fits well with a dataset from an earlier assignment you are welcome to re-use that dataset (make sure that you spend a bit of time either expanding or improving the dataset or more time designing and implementing and revising the new visualization).___

* Next prepare the dataset. If the data already exists in an easily obtainable and sufficient detail and quantity, collect that data. Alternatively, you may write a simple program to generate synthetic data that matches your understanding of the data. Be sure to add a small amount of random noise so it's "interesting".
\
\
To really show off the visualization, generate 2 ___different___ versions of the data. If it's a team project, this should be the data for the 2 team members. You may want to idealize or exaggerate the similarities and differences in the data for the 2 team members.
\
\
___If you've created synthetic data or exaggerated or expanded real data, note that in your writeup.___

* Now to make the visualizations!
  - First, plot the data using a "boring" stacked bar graph over time: 2 separate plots, 1 for each version of the data (e.g., the data for each team member). Use the same design/legend/scale/colors/ordering so that the differences between the datasets can be easily compared.
  - Then, create a streamgraph version of this data. Again, make 2 separate plots, 1 for each dataset/person, using the same design/colors/ordering so that the two streamgraphs can be compared to each other, and each streamgraph can be compared to the boring stacked bar graph version of the same dataset.
  - Streamgraphs can be created with D3. Here are some links with same code: [http://bl.ocks.org/WillTurman/4631136](http://bl.ocks.org/WillTurman/4631136) or [https://hrbrmstr.github.io/streamgraph/](https://hrbrmstr.github.io/streamgraph/) or search for additional references. Or you may use another toolkit to create your streamgraph.
  - Iterate as necessary to revise the colors, ordering, and time discretization to maximize legibility of all 4 plots.
* ___If you are having trouble creating or controlling the streamgraph plots, you may either draw a detailed diagram by hand with crayons/colored pencils/markers or with a digital painting program, or you may use software tools.___
* ___If you do the drawing by hand, take care to approximately match the data values between the bar graph and stream graph. Follow the examples and algorithm description from our reading and chose a thoughtful baseline and ordering of the components of the data.___

* Gather your plots in a .pdf report. Be sure to write detailed figure captions that will fully explain your plots to a reader who hasn't seen streamgraphs before.

* Analyze the effectiveness of the bar graph vs. streamgraph in showing off the differences and similarities in the two datasets. How well do these plots allow the viewer to make accurate conclusions about the data? What might be confusing, unclear, or misleading about these plots?

* Share your plots on the Submitty Discussion Forum.
