---
title: "Homework #2: Time-Based Datasets & Chart Junk"
subtitle: Interactive Visualization Summer 2021
course_link: courses/u21/csci4550/landing_page
course_title: CSCI4550
subpage_link: courses/u21/csci4550/homeworks/homework_2
subpage_title: Homework 2
---
## Specification
This assignment should be done in a team two or three. You are welcome to work with the same people
you met for the Lecture 2 worksheet, or form a new team. You may use an idea you brainstormed in
class for the worksheet, or pick something entirely different.  

Identify an interesting ___time-based___ dataset on a topic that is familiar to at least one member
of the team. Be sure to pick a topic for which sufficient data can be found online without too much
effort. For example, sports player/team wins/salary, movie ticket sales/actor salaries, etc. It
should be time-based, meaning that an interesting component of the data is time (e.g., year, day,
hour, age, duration), and you can pose interesting questions about the data that can be solved by
plotting data relative to a time axis.  

Review the categories of charts from ["Eenie, Meenie, Minie, Moe: Selecting the Right Graph for
Your Message", Stephen Few, 2004](http://www.perceptualedge.com/articles/ie/the_right_graph.pdf)
and brainstorm how different relationships in this data (or subsets of this data) could be plotted
to answer simple questions about the data. Make sure you are following the paper's recommendations
for best practices to display information. ___Aim to produce at least 5 charts of different types.
Extra credit points if you can create one of each of the 7 different types!___  

Now collect the data. Some online data sources are trivial to parse -- just a click to download a
single simply-structured, error-free file. Other data sources might require collection from
multiple locations, complicated parsing, filtering, manual cleaning, and elaborate association
or post-processing. Re-evaluate your plan if the data collection and data preparation process is
either too simple or more time-consuming that you expected. This is a 1 week, team assignment and
one goal is to learn and practice something about the data collection process.  

Tools you might use/learn for data collection:
* Simple copy-paste from a website to a file.
* wget to download files from websites.
* UNIX utilities: grep / sort / uniq / sed / awk
* Your favorite programming language to parse/strip out unnecessary html formatting.
* Save as .csv (comma separated value) files to upload to Excel / Google Sheets.
* Python has lots of packages for parsing (e.g., json format).
* Selenium for automated browsing of websites.
* Please share other ideas/tips for data collection on the Discussion Forum!

Finally, use Excel or Google Sheets (yes, limit yourself to one of these simple visualization
tools) to create your charts. Make sure to carefully label the data, axes, legend, and title as
appropriate. Write an excellent caption for each chart that ensures the viewer understands the
purpose of the chart and the conclusion that can be drawn from the data.  

__OPTIONAL (for extra credit):__ Select one of your charts rendered in Excel or Google Sheets and
redraw it (using any tool) to make it more memorable, inspired by the examples in ["Useful Junk?
The Effects of Visual Embellishment on Comprehension and Memorability of Charts", Bateman et al.,
CHI 2010](https://www.researchgate.net/publication/221517808_Useful_Junk_The_effects_of_visual_embellishment_on_comprehension_and_memorability_of_charts)  

## What to Submit
* Collect your charts into a single .pdf document. The charts should mostly stand on their own.
(You shouldn't need to write much additional text about the topic.)  

* In the .pdf, formally cite the source(s) of your dataset. And provide a detailed documentation
of the steps you took to collect and prepare your dataset.  

* Include the source code for scripts or programs that you wrote to prepare the data. __Note: We
won't attempt to run these scripts, so you don't need to include helper libraries/programs that
you did not write, just document those libraries/programs in the .pdf.__  

* In the .pdf include a brief explanation of "who did what" on the team and "what you learned"
(hopefully something about web scraping and/or data preparation tools). Note: we encourage pair
programming so that everyone learns all of the tools used to complete the assignment.  

* Make a single post for the team on the Submitty Discussion Forum sharing two of your diagrams.  
