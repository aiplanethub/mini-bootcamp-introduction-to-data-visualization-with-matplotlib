# Making The Plots Descriptive

## Learning Objectives

* Why should we make plots descriptive?
* Adding a Title
* Adding Labels
* Adding a legend




## Why should we make plots descriptive?

The plots that we created in the previous module do the job but do you think any person who looks at those will be able to understand what they represent?

It's a good practice to make all the plots descriptive and easy to understand using Title, Labels and Legends.

### 1. Adding a Title

Your graph isn't complete without a title that summarizes what the graph itself depicts. The title is usually placed in the center, either above or below the graph. The proper form for a graph title is "y-axis variable vs. x-axis variable."

Adding title to a plot is very straightforward. It can be done with the title function as follows:






![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6e1820129cda459dbf3ffe816bb02ef4.png)






### 2. Adding Labels

Axis labels are the variable names or descriptions that represent a particular axis. The axis label usually appears below or to the left of the axis.

* To add a label to the X axis, xlabel function is used.
* Similarly, to add a label to the Y axis, ylabel function is used.







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_3c07726820444d34a11bc4f03cd01c6c.png)







### 3. Adding a legend

Now that you've added what the graph, X and Y axis represent, you're already halfway through the process of making your graphs intuitive.

You plotted the income of both work_force and physicians on the same graph above. How would a layman know which plot represents the work_force and which the physicians? That problem is solved by a legend.

A legend is an area describing the elements of the graph. In the matplotlib library, there’s a function called legend which is used to place a legend on the axes, as follows:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1f17b49dc19340ba812359ff85b71501.png)