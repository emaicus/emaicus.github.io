---
title: "Homework #3: Graph Visualization"
subtitle: Interactive Visualization Summer 2021
course_link: courses/u21/csci4550/landing_page
course_title: CSCI4550
subpage_link: courses/u21/csci4550/homeworks/homework_3
subpage_title: Homework 3
---
## Specification

### Crowdsourced RPI CSCI Course & Instructor Dataset
Our dataset for this assignment will be the courses at RPI typically taken by Computer Science majors. Here's a link to our shared Google Sheets dataset:  

* [https://tinyurl.com/crowdsourced-hw3](https://tinyurl.com/crowdsourced-hw3)  

The data is organized into two tabs: one lists the courses and their prerequisites, the second shows the history of terms the course was offered and the instructor(s) for each term. We will focus on classes taken by CSCI majors to complete their degree requirements. Here are the requirements for the recent incoming class:   

* [2019-2020 CSCI Major Template](https://rpi.app.box.com/v/csci-2023-template)  
* [2019-2020 Catalog for Computer Science](http://catalog.rpi.edu/preview_program.php?catoid=20&poid=4545&hl=%22computer+science%22&returnto=search)  
* [CSCI Captone Concentration Areas](https://rpi.app.box.com/s/v8w9dejrfenfm2r3ig4exhv4atd9ktyt)  

Some of this data can be scraped from websites, but requires significant manual editing for clarity, consistency, and accuracy. In particular, the historical data might be inconsistent and much harder to acquire automatically. So we'll work together to crowdsource a clean and somewhat simplified version of this data.  

### Graphviz
The primary goal for this assignment is to familiarize yourself with [Graphviz](http://www.graphviz.org/), an open source visualization tool for automatically drawing network-like graphs of linked nodes. To get started:  

* Download the Graphviz software and explore the [gallery of examples](http://www.graphviz.org/gallery/). Learn how to run these examples on your own machine and view the results.  

* Edit by hand some of the input graph files -- see also the [DOT file format documentation](https://graphviz.org/doc/info/lang.html). Experiment with different display options.  

* Using your favorite programming language, write code to generate and output a range of synthetic input files. Your program should be parameterized (allow you to modify) the number of nodes, the density/sparseness of edges, etc. Consider using randomness.  

* Alternatively, you could write in C/C++ and [directly compile with the Graphviz codebase.](https://graphviz.org/pdf/libguide.pdf)  

* Create a variety of network connectivities including: a tree, a clique, a planar graph, a bipartite graph, disconnected components, etc. The size of your graphs should be "medium" sized (10-40 nodes). The size should not be too large -- that is, with a little time, a "good, optimal" layout could be done by hand. Save 5-10 of these images for inclusion in your homework writeup to demonstrate your experimentation.  

* Now let's work with the RPI CSCI Course & Instructor Datatset about to create 3 different polished graph visualizations:  

  1. A ___directed___ graph showing a typical or specific student progressing through the CSCI degree requirements over ~8 semesters. You can draw the exact course plan you followed, what you should have taken (if you had a time machine), or the course plan you would recommend to a friend starting at RPI in Fall 2021.\
  \
  _Note: You can include "the Arch" or ignore it. You can choose how to handle non CSCI courses: what to include, what to display, what to simplify._\
  \
  Carefully consider your audience for this visualization -- students and their advisors who are making course planning and registration decisions. Does your visualization help them understand what modifications are possible? Which classes can be taken early or delayed? Which courses and terms are more challenging -- workload, time commitment, etc.

  2. A ___bi-partite___ graph showing two types of nodes: courses and instructors where an edge is drawn between a course and an instructor if the instructor has taught the course at least once. (There are no edges between instructors, or between courses). This graph should reveal how faculty and courses cluster by teaching/research interests and specializations.

  3. And, finally, design and execute an interesting graph of your choice from this data (or subset of this data).

* Experiment with the visual options (layout, color, line style, line thickness, line shape, text placement, font, etc.). What options are most successful for the different visualizations? Write an excellent caption for each of your 3 polished graphs.

* Finally, analyze your experience with the Graphviz tool. Were you able to successfully execute your designs? Did the tool help you automatically create interesting, moderately-complex graphs? Note any weaknesses in the tool or degeneracies with more specific inputs. Could you have done better by hand? What adjustments/improvements do you believe are necessary to the graph drawing engine of this tool?  
\
Write a short review of the tool. How quick was the installation and learning to use the tool? What resources were most useful? What sorts of applications/datasets are most appropriate for this tool? What are the limitations of this tool? What are some suggestions/cautions to others who consider using this tool?

### How to Submit
* Prepare a report as a .pdf with embedded images. Be sure to include:

  * \~5 graphs of synthetic data demonstrating a variety of graph types and visualization styling. Write a short caption for each describing what you were trying to achieve, what was successful, and/or what needs improvement.  
  * 3 polished graphs of the course data with carefully written captions.
  * Analysis and review of Graphviz tool.

* Collect the code you wrote to generate the synthetic input files and code/scripts to organize/preprocess the course data in a subfolder named "code". ___Note: We won't try to run your code when grading, so don't include any 3rd party libraries you may have used or the executable.___ The code should have some organization and basic comments, but you do not need to prepare detailed documentation.
* Share your favorite, most-successful image from the assignment on the Submitty Forum. Make sure your forum post includes a well-written and descriptive caption to go along with your image.
