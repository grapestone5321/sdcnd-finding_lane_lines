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

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I .... 

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by ...

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when ... 

Another shortcoming could be ...


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...


## Project Submission
Navigate to the project repository on GitHub and have a look at the Readme file for detailed instructions on how to get setup with Python and OpenCV and how to access the Jupyter Notebook containing the project code. You will need to download, or git clone, this repository in order to complete the project.

In this project, you will be writing code to identify lane lines on the road, first in an image, and later in a video stream (really just a series of images). To complete this project you will use the tools you learned about in the lesson, and build upon them. 

Your first goal is to write code including a series of steps (pipeline) that identify and draw the lane lines on a few test images. Once you can successfully identify the lines in an image, you can cut and paste your code into the block provided to run on a video stream. 

You will then refine your pipeline with parameter tuning and by averaging and extrapolating the lines. 

Finally, you'll make a brief writeup report. The github repository has a writeup_template.md that can be used as a guide.

Have a look at the video clip called "P1_example.mp4" in the repository to see an example of what your final output should look like. Two videos are provided for you to run your code on. These are called "solidWhiteRight.mp4" and solidYellowLeft.mp4". 

