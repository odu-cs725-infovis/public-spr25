# Interactive Dashboard Visualization Project 

Choose a real-world dataset and develop an interactive dashboard visualization that allows users to better understand the data, such as by discovering patterns, identifying outliers, confirming or rejecting hypotheses, etc. As opposed to an open exploration of all elements of the data, your dashboard must focus on an intended audience with a set of specific tasks.

Your visualization must employ multiple interactive charts in a single viewport ([Single Page in the Structure design pattern / Screenfit, Detail-on-demand, and/or Parameterized in the Screenspace design pattern](https://dashboarddesignpatterns.github.io/patterns.html)) that allow the user to ask and answer questions about the data.  You may add widgets such as drop-down menus, radio buttons, etc. to provide filtering functions.  There should also be some amount of direct interaction with the charts themselves. You are encouraged to use brushing and linking and chart navigation (focus+context) as appropriate. The interactive elements must add value. *Do not add interactivity just because you can.*

A well-chosen dataset is key to creating an interesting project.  Choose something that you either already know about or that you're willing to learn about.  The context that you can provide will help determine what features should be highlighted to help the user better understand the data.

All projects will be demonstrated live in class.

See the [Project Examples page](https://canvas.odu.edu/courses/177607/pages/project-examples) in Canvas for some ideas.

## Mechanics

Project topic selection and demo scheduling will be done through the Canvas Discussion Board, similar to how we've done for the paper presentation. Once all project topics have been chosen, we'll start scheduling the demos in a similar manner.  No two students may choose the exact same dataset. 

As with the paper presentations, I would prefer for all students to deliver their demos live in Zoom.  If you are not able to attend on your scheduled presentation date, you may pre-record your presentation -- but this must be approved in advance.

Your project must be implemented in Vega-Lite or D3. You may build your project in Observable or on a stand-alone webpage (see [Advanced Embeds](https://observablehq.com/documentation/embeds/advanced)).

You will also provide a report about the design of your project.  This should be done as a Markdown document separate from your project visualization page.  Details are below.  

Your project page/notebook must include your name, CS 725/825 (as appropriate), Spring 2025, and a link to your report (can initially be a placeholder - report may be due later than the project).

### Deadlines

**Mon, Mar 24, 3pm** - dataset and topic chosen (posted in Canvas discussion forum)

**Mon, Mar 31, 3pm** - description of the user audience, specific tasks that will be enabled, and example analysis scenario

**Fri, Apr 4** - deadline for meeting with me to discuss your initial design

**Mon, Apr 21, 3pm** - final project deadline (last modifications to implementation notebook) 

**Fri, May 2, 7pm** - final report deadline - *this is the end of our scheduled final exam slot*

## Grading

This assignment is worth 25% of your final grade. 

Your project and report will be largely evaluated on how well they meet the guidelines provided here.  Additional considerations will be made for differences in difficulty (i.e., D3 vs. Vega-Lite), aesthetics, attention to detail, and project ambition.

## Audience/Tasks/Scenario

This requirement is to provide an initial outline of what you are planning for your dashboard project. 

* User Audience - Identify the audience who you expect to use your dashboard (general public, researcher, expert, etc.)
* Tasks - Identify the major tasks that will be enabled by your dashboard. What do you plan to allow the user to do/investigate? What questions do you anticipate they could answer? You may want to refer to VAD Ch 3 for some terminology around tasks.
* Scenario - Provide an example scenario of a user using your dashboard to complete a task or answer a question. This can be a narrative description of what they would do, or could be sketches of how they might interact with the dashboard.

This document will form the basis for our individual discussions regarding your plans, so provide as much detail as you can so that we can have a productive meeting.

**Submission:** In Canvas, submit this as plain text, an uploaded .txt or .pdf file, or a link to a Markdown document (could be on GitHub or Observable).

## Report

Your report must be done in Markdown. Points will be deducted for missing sections, excessive typos or grammatical errors, or a report that is difficult to read.  You may create your report in GitHub or in an Observable notebook separate from your project. 

Your report must include the following sections:

**Introduction.** Describe your visualization topic and motivation for why you chose this topic. Describe the main questions that you are attempting to address (or allow the user to ask) with your visualization.

**Data.** Describe the dataset that you used, including links to the original data sources. As different visualizations can emphasize different aspects of a data set, you should document what aspects of the data you are attempting to most effectively communicate. 

**Visualization.** Describe your visualization. Explain any interactive elements you employed. Address how the visualization addresses the questions you raised in the Introduction.

**Design Decisions.** You must explain every design decision you make and essentially be able to explain the contribution of every pixel in the display. 
* For each chart in your dashboard, document the visual encodings (idioms, marks, channels) you used and why they are appropriate for the data. These decisions include the choice of visualization idiom, size, color, scale, and other visual elements, as well as the use of sorting or other data transformations. How do these decisions facilitate effective communication?  
* Include a description of the principles of effective dashboard design that you used. 
* Provide a justification for the interactive elements (filters, facets, etc.) that you provide. Why is this particular representation of the data useful?  How does the interaction contribute to the user's insight into the data?

**Development Process.** Include a commentary on the development process, including answers to the following questions:
* Roughly how much time did you spend developing your visualization?
* What aspects took the most time?

**References.** Include a list of any pre-existing resources (e.g. Stack Overflow, Observable notebooks, etc.) used in your implementation.

**Submission:** In Canvas, submit the URL of your project report by the final report deadline.

## Demo

You will have at most 20 minutes for your demo, but I expect that most projects could be demonstrated in about 10 minutes.  You do not need to provide slides, but you should plan out your demo in advance.  

Your demo should contain the following elements:
* Briefly describe the problem and data you're visualizing.
* Highlight the main features of the visualization by walking through a scenario (or multiple scenarios).
* Demonstrate that the visualization provides effective representation of the data, uses appropriate colors, and supports multiple tasks through interactivity.

You may also want to talk about significant things you learned (such as helpful tips or pitfalls to avoid) while implementing your project.

In addition, you should be prepared to answer questions about your visualization and its implementation after the demo.

**Submission:** In Canvas, submit the URL of your project implementation by the final project deadline.
