# Introduction



### Learning Objectives

* Introduction to Matplotlib
* Advantages
* Installation
* Importing Matplotlib
* Matplotlib Chart

### Introduction 

* Matplotlib is the most popular Python plotting library. 
* It is a comprehensive library for creating static, animated, and interactive visualizations in Python.
* It is useful for those working with Python and NumPy.
* It is a low-level library with a MATLAB-like interface which offers lots of freedom at the cost of having to write more code.

### Advantages

* Extremely powerful
* Fast and efficient
* Open source
* Works well with many operating systems and graphic backends
* High-quality graphics and plots 
* Ability to print and view a range of graphs 
* Large community support and cross-platform support 
* Full control over graph or plot styles




### Installation

* Before Matplotlib's plotting functions can be used, Matplotlib needs to be installed. 
* The Anaconda distribution of Python as well as Google Colab come with Matplotlib pre-installed and no further installation steps are necessary.
* However, if you're not using any of those, you can install it by running a simple pip command in your terminal: **`pip install matplotlib`**






### **Pyplot**

The most used module of Matplotlib is Pyplot which is Matplotlib's plotting framework. 

Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.

### Importing matplotlib 

There are a lot of modules in Matplotlib but for plotting purposes, we only import pyplot.

Just as we use the np shorthand for NumPy and the pd shorthand for Pandas, we will use the standard shorthand 'plt' for the Matplotlib import:

**`import matplotlib.pyplot as plt`**



### Matplotlib Chart

Matplotlib’s charts are made up of two main components:

* **The axes:** the lines that delimit the area of the chart
* **The figure:** where we draw the axes, titles and elements that come out of the area of the axes.

Note: Unlike the plural of axis, axes in Matplotlib is actually the whole rectangular box containing the axis lines, ticks and labels. 

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_80a3f7287fc34c1b8320e7a8ce8618a5.png)