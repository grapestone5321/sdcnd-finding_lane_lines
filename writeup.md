# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

The pipeline consisted of 5 steps. 

1. The images to grayscale is converted.
2. Gaussian smoothing is applied.
3. Canny transformation is used.
4. The region of interest is selected.
5. Hough Tranform line detection is applied.


In order to draw a single line on the left and right lanes, I modified the draw_lines() function by getting the slopes of left lane line and right lane line.


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the lanes are curvy. 


### 3. Suggest possible improvements to your pipeline

Optional Challenge is not comleted yet. A possible improvement would be to work on curvy lanes by completing the Challenge.
