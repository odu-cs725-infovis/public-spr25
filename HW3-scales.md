# Homework 3 - D3 Scales and SVG

**Due:** Monday, February 17, 2025 by 3pm

Read the entire assignment before starting.

**Important Updates (Feb 14):**
> 🚨 See the notes indicated like this below for updates.

## Assignment

The goal of this assignment is to practice using D3 scales and the basics of SVG and D3 visualization. This will closely map to the [D3 Data Intro](https://observablehq.com/@oducs-vis/d3-data-intro?collection=@oducs-vis/cs-725) and [D3 Vis Intro](https://observablehq.com/@oducs-vis/d3-vis-intro?collection=@oducs-vis/cs-725) notebooks that were discussed in class.

### Report

You will be using JavaScript and D3 in an Observable notebook for this assignment.  In addition to writing code to answer the questions that are asked, you *must also include an explanation of your code*.  This will serve as your HW report.

Remember that every report must have an appropriate heading (with HW name, your name, semester, due date, etc.), appropriate section headings, a References section, and an Appendix section.

### Dataset

These tasks require a simple dataset of 5 items with one categorical attribute, one quantitative attribute, and one categorical attribute representing a color. You can manually create your dataset as a JavaScript Array of Objects. For example:

```js
students = [
  {name: 'Joe', value: 5, color: 'blue'},
  {name: 'Mary', value: 8, color: 'red'},
  {name: 'Spencer', value: 3, color: 'yellow'}
  ]
```

### Setup

For some of the questions, you'll need to use `visualizeTicks()` and `swatches()`. For this, include the following statements in your Appendix section:
```js
import {visualizeTicks} from "@d3/continuous-scales"
import {Swatches} from "@d3/color-legend"
```

> 🚨 Note about D3 and Observable Cells: 
> * You can't have cells that produce the same variable name. So you have to be careful if you are setting up scales and axes for multiple charts in a single notebook.
> * Additionally, having multiple browser tabs with variables of the same name can cause issues. Close other Observable notebooks that might use the same variable names, or choose unique variable names.
> * Sometimes having multiple sets of svg containers in the same notebook can make things wonky. If you have multiple charts, things aren't working, and you can't figure out why, try separating out the broken chart into a separate notebook.
> * Sometimes just reloading the webpage can reset the state and make things work.

### Questions/Tasks

These tasks work towards creating a set of rectangles that could be used in a horizontal bar chart.

**Q1.** Create a D3 linear scale based on the quantitative attribute in your dataset. Use 400 as the max value in your range. Use `visualizeTicks()` to visualize the scale.

**Q2.** Create a D3 band scale based on the non-color categorical attribute in your dataset. Use 150 as the max value in your range. Use `visualizeTicks()` to visualize the scale.

**Q3.** Create a D3 ordinal scale based on the color categorical attribute in your dataset. Choose one of [D3's categorical schemes](https://d3js.org/d3-scale-chromatic/categorical) for your colors. Use `swatches()` to visualize the scale.
> 🚨 *Map your ordinal color scale to your non-color categorical attribute, not your color attribute.*

**Q4.** Use SVG to manually create the rectangles for a horizontal bar chart from your data. 
> 🚨 *Use the color attribute in your data to color the rectangles.*

**Q5.** Use D3 to manually recreate the rectangles from Q4. Include a screenshot showing the SVG elements in your web browser inspector.
> 🚨 *Use the color attribute in your data to color the rectangles.*

**Q6.** Use your dataset and D3 joins to generate the rectangles in D3. Include a screenshot showing the SVG elements in your web browser inspector.
> 🚨 *Use the ordinal color scale (not your color attribute) to color the rectangles. This may result in different colors than you had for Q4 and Q5 -- this is fine.*

**Q7.** Generate the rectangles in D3 using your scales from Q1-Q3. Include a screenshot showing the SVG elements in your web browser inspector.
> 🚨 *Use the ordinal color scale (not your color attribute) to color the rectangles. This may result in different colors than you had for Q4 and Q5 -- this is fine.*

**Extra Credit:** Generate a simple dataset with at least 7 items and two quantitative attributes. Use D3 scales and joins to draw the dots that would be used in a scatterplot based on your dataset. Include a screenshot showing the SVG elements in your web browser inspector.

## Evaluation Criteria

Your assignment will be evaluated on the following criteria:

* How well do the answers demonstrate an understanding of the D3 functions?
* Does the report contain the required elements?
  * Attention to detail, including spelling, and overall aesthetics will be a factor.

## Submission

Submit the URL of your Observable notebook in the HW3 Assignment in Canvas.
