# Homework 4 - D3 Intro

**Due:** Monday, March 3, 2025 by 3pm

*Read the entire assignment before starting.*

## Assignment

In this assignment, you'll be recreating some of the charts from HW1 using D3.

You will be using D3 in an Observable notebook for this assignment.  In addition to creating the charts that are assigned, you must also include an explanation of the charts and how you have created them.  

Make sure to refer to the examples in our [CS 725/825 Observable Collection](https://observablehq.com/collection/@oducs-vis/cs-725).

### Report

Your Observable notebook functions as your report.  This means that after successfully creating your charts, you must go back and edit your notebook to add Markdown cells with explanations of your code, remove items that didn't work, etc. In general, make sure that it is clear what you have done to create the charts and explain the code for any customizations that you have made.

Your notebook must have a **References** section, with titles and links to references that you used, and an **Appendix** section, with needed imports (e.g., D3, Arquero, Swatches).

### Dataset and Data Manipulation

You should use the same dataset(s) that you used for HW1.  However, you might want to do additional data manipulation outside of your charting code to make your D3 vis code simpler. Using Arquero is recommended (though not required). (Since you'll be using the same data as in HW1, you may want to fork your HW1 notebook to get started. If you attached a datafile to your HW1 notebook, the forked notebook will also include the datafile.)

**Notes:** 
* If you had comments from me on the appropriateness of your data to chart mapping in HW1, please talk with me before starting on your D3 code. I don't want you recreating exactly what you had in HW1 if it was not appropriate.
* If you did more than the basic chart (for instance, a stacked bar chart instead of simple bar chart), just create a simple bar chart version in D3.

### Charts to Create

Use D3 in Observable to create the following charts.  You *do not* need tooltips or a legend for any of these charts (except where noted).  All of these are single charts (no repeating or faceting as we did with Vega-Lite).  

1. scatterplot
2. horizontal bar chart
3. line chart with 1 line
4. layered line and area chart
5. multi-line chart with 2-5 lines and legend

Notes:

* The **layered line and area chart** must show a single area and a single line that show different items or categories of the same attribute. One suggestion is to have the area show the attribute total for all categories and the line show the attribute for a single category. It must *not* be a dual-axis chart.
* The **multi-line chart** must be based on the ["Layered Line and Area Charts"](https://observablehq.com/@oducs-vis/d3-intro-layered-line-and-area-charts?collection=@oducs-vis/cs-725) format, meaning that the select/data/join process must be used rather than drawing each line individually. Each line must represent a different item or category in your data. Use color to distinguish the lines and `Swatches()` to generate a legend in the cell above your chart.

*Extra Credit:* Create a small multiples grid visualization showing how a single quantative attribute changes over time for different values in a categorical attribute. (You may want to refer to the [NYU Vis Small Multiples notebook](https://observablehq.com/@nyuvis/small-multiples) for an example. For instance, in the unemployment rate example in the notebook, the single quantitative attribute is unemployment rate and the categorical attribute is the state.)

## Submission

Submit the URL of your Observable notebook in the HW4 Assignment in Canvas.
