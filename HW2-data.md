# Homework 2 - Data Manipulation

**Due:** Monday, February 10, 2025 by 3pm

Read the entire assignment before starting.

## Assignment

The goal of this assignment is to practice Arquero and D3 data manipulation.

### Report

You will be using JavaScript, Arquero, and Vega-Lite in an Observable notebook for this assignment.  In addition to writing code to answer the questions that are asked, you *must also include an explanation of your code*.  This will serve as your HW report.

Remember that every report must have an appropriate heading (with HW name, your name, semester, due date, etc.), appropriate section headings, a References section, and an Appendix section.

### Datasets

Use dataset(s) of your choosing. This could be the same as you used in HW1 or a different one.

*Your final project will be to create an interactive dashboard using dataset(s) of your choosing. Use this assignment as an opportunity to start investigating some interesting datasets.*

### Questions/Tasks

*The questions/tasks do not each need to be completed in a single Observable cell.*

First, briefly describe the dataset you've chosen. Discuss the most important attributes and their datatypes.

**Q1.** Similar to **Q2** from our [D3 Data Intro exercises](https://observablehq.com/@oducs-vis/d3-data-intro), write a function to sort your dataset based on some criteria. This sort function must use the JavaScript arrow notation. Explain in words what you intend your sort function to do.  Demonstrate that this sort function works as intended.

**Q2.** In a single statement, import your data into an Arquero data table and display the first 10 rows.  Then in a separate statement, display the last 10 rows (without sorting the data).

**Q3.** Use Arquero to filter your dataset by some criteria. Explain in words what you intend your filter statement to do.

**Q4.** Use Arquero to pull the values from one of your attributes into an array.

**Q5.** Demonstrate the use of Arquero's `groupby()` and `rollup()` functions on your dataset. Explain in words what your operations are trying to show (or what question you're trying to answer).

**Q6.** Use Arquero to create a derived attribute on your data. The function to compute the derived attribute should use at least one of Arquero's `op` operators. Explain in words what the derived attribute represents.

**Q7.** Find or create a second dataset that shares a key with your dataset. Demonstrate the use of Arquero's `join()` (or filtered join with `semijoin()` or `antijoin()`). Explain in words how you have combined the two datasets. (Note: We did not cover this in class, but see the Introducing Aquero notebook section ["Blend datasets with `join()`](https://observablehq.com/@uwdata/introducing-arquero#cell-525) for reference.)

**Q8.** Use Vega-Lite to create a chart from the resulting dataset from **Q5** (groupby/rollup), **Q6** (derived attribute), or **Q7** (joined data). The type of chart is up to you. Use appropriate axis labels, title, and tooltips. Explain your chart and how your data is mapped to the marks and channels.

**Q9.** Take at least three non-nominal (i.e., non-categorical) attributes in your dataset and use D3 functions (`d3.min`, `d3.max`, or `d3.extent`) to determine the range of values (i.e., min and max) in each of those attributes. One these attributes must be temporal and use a `Date` object.

## Evaluation Criteria

Your assignment will be evaluated on the following criteria:

* Was the data thoughtfully chosen?
* How well do the answers demonstrate an understanding of the Arquero and D3 functions?
* Does the report contain the required elements?
  * Attention to detail, including spelling, and overall aesthetics will be a factor.

## Submission

Submit the URL of your Observable notebook in the HW2 Assignment in Canvas.

### Note about Using Observable

You must be a member of the @oducs-vis Observable Team (https://observablehq.com/@oducs-vis) to submit this assignment.  If you are not already a member, create an Observable account and email me your username (it should be something related to your name so that I can verify who you are).  Once you've been added to our Observable Team, you can create private notebooks that you can use for your homework assignments.

To create a new private notebook:

* start at https://observablehq.com/@oducs-vis
* click New
* make sure **Workspace** is set to "ODUCS Vis" and **Visibility** is set to "Only You"
* click Create Notebook

To share with your instructor (for help or for grading):

* click Share
* in the **Search for a teammate** box, enter weiglemc
* choose "Can Edit"
* click Add
* click Save

Note that after the semester, you will be removed from the Team. I'll send an email to remind you and give you time to copy your notebooks elsewhere before that happens (you can transfer ownership to your own account). I would appreciate that you remove mention of CS 725/825 from the notebooks before making them public.
