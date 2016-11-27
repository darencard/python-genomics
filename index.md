---
layout: lesson
root: .
lastupdated: November 13, 2016
contributors: ["Daren Card", "Alexey Shiklomanov"]
maintainers: ["Daren Card"]
domain: Genomics
topic: Python
software: Python
dataurl:
status: Under Development
---

<!-- USING THIS LESSON TEMPLATE -->
<!-- Lesson specific information is taken from the YAML header at the top of the page -->

<!-- THE LESSON INFORMATION -->


# Data Carpentry {{ page.topic }} for {{ page.domain }}

Data Carpentry's aim is to teach researchers basic concepts, skills,
and tools for working more effectively with data.
The lessons below were designed for those interested
in working with {{page.domain %}} data in {{page.topic %}}.


**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**


**Lesson status: {{ page.status }}**

<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:


1. [Lesson 00 Before we start](00-before-we-start.html)
2. [Lesson 01 Introduction to Python](01-intro-to-Python.html)
3. [Lesson 02 Starting with data](02-starting-with-data.html)
4. [Lesson 03 Introducing `data.frame`](03-data-frames.html)
5. [Lesson 04 Aggregating and analyzing data with pandas](04-pandas.html)
6. [Lesson 05 Data visualization with ggplot2](05-data-visualization.html)


## Learning objectives

### Basics
* Write and execute commands in a Jupyter notebook
* Perform basic math operations
* Create, identify, and distinguish between integers, floats, and strings
* Assign values to variables
* Call built-in Python functions
* Find documentation on a Python object in the documentation
* Write and execute a simple program

### Intermediate concepts
* Create and identify lists
* Select elements of a list (including characters from a string)
* Retrieve attributes of an object, such as their methods
* Predict the behavior of the `+` and `*` operators based on their inputs
* Create and identify tuples
* Create and identify dicts

### Introduction to Numpy
* Import modules in different ways
* Perform vector-based math operations on numpy arrays
* Perform operations and subset numpy arrays of various dimensions

### Introduction to Pandas
* Identify similarities and differences between dicts and Pandas Series
* Create a Pandas data frame
* Read data from a CSV file into a Pandas data frame

## Data

Data files for the lesson are available here: ({{page.dataurl %}})[{{page.dataurl %}}]


### Requirements

Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workflow.
*These lessons assume no prior knowledge of the skills or tools*, but working
through this lesson requires working copies of the software described below.
To most effectively use these materials, please make sure to install everything
*before* working through this lesson.




{% if page.software == "Python" %}
{% include pythonSetup.html %}
{% elsif page.software == "Spreadsheets" %}
{% include spreadsheetSetup.html %}
{% elsif page.software == "R" %}
{% include rSetup.html %}
{% else %}
{% include anySetup.html %}
{% endif %}

<p><strong>Twitter</strong>: @datacarpentry
