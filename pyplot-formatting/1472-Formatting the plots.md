# Formatting The Plots

## Learning Objectives

* Changing Colors
* Changing line-styles
* Adding Markers
* Combining the three formatting options



## Formatting Plots

* The first adjustment you might wish to make to a plot is to control the line colors and styles.
* Look at all the above graphs you've created till now. What is the color and style of the plots where it is not explicitly specified? 
* **All solid blue lines. A solid blue line is the default formatting style in Matplotlib.**
* The plt.plot() function takes additional arguments that we can use to specify the formatting.
* You've already specified the color of a few plots before using the 'color' argument. Colors can be provided in a few other ways as well.




### Changing Colours

To adjust the color, you can use the color keyword, which accepts a string argument representing virtually any imaginable color. The color can be specified in a variety of ways:








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_88a9a060d53c495e887a31e0d6628864.png)





Matplotlib will automatically cycle through a set of default colors for multiple lines if no color is specified.

### Changing Line Styles

Similarly, the line style can be adjusted using the linestyle keyword. You can make the lines dashed, dotted, or both.










![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9e2c19d4ba644698b3df5fb039b78f97.png)









### Adding Markers

So you've plotted lines that pass through the points in the dataset. But we can't see those points in the lines above, can we?

Adding markers to a line plot can be a useful way to distinguish multiple lines or to highlight particular data points. 








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_013e7414bdf64f49a080556245c59dff.png)










### Combining the three formatting options

Let's plot a red dashed line with triangular markers!







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e58bf3283b6d468192323235a4133e3d.png)







### Shortcut for above

For every x, y pair of arguments, there is an optional third argument: the format string that indicates the color and line type of the plot. The letters and symbols of the format string are from MATLAB, and you concatenate a color string with a line-style string. The default format string is 'b-', a solid blue line.

These linestyle and color codes can be combined into a single non-keyword argument to the plt.plot() function:







![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6f3c5692d1ed45b4ad04eb173d67af0a.png)





### Scatter Plot with the plot function

It turns out that the plot function can produce scatter plots as well. Just don't mention any linestyle.










![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d2704d105f364dab9c4a1415b71e6d3f.png)







### More examples








![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_88268dc41f12444d9d0f2115aa91759c.png)






There are plenty of other options. You can try the following:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e7e48c75e6ec47928ca61a101db6a7de.png)

These single-character color codes reflect the standard abbreviations in the RGB (Red/Green/Blue) and CMYK (Cyan/Magenta/Yellow/blacK) color systems, commonly used for digital color graphics.