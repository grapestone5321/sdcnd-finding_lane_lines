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

### Evaluation
Once you have completed your project, use the Project Rubric to review the project. If you have covered all of the points in the rubric, then you are ready to submit! If you see room for improvement in any category in which you do not meet specifications, keep working! 

Your project will be evaluated by a Udacity reviewer according to the same Project Rubric. Your project must "meet specifications" in each category in order for your submission to pass.


In this project, you will use the tools you learned about in the lesson to identify lane lines on the road. You can develop your pipeline on a series of individual images, and later apply the result to a video stream (really just a series of images). Check out the video clip "raw-lines-example.mp4" (also contained in this repository) to see what the output should look like after using the helper functions below.

Once you have a result that looks roughly like "raw-lines-example.mp4", you'll need to get creative and try to average and/or extrapolate the line segments you've detected to map out the full extent of the lane lines. You can see an example of the result you're going for in the video "P1_example.mp4". Ultimately, you would like to draw just one line for the left side of the lane, and one for the right.

In addition to implementing code, there is a brief writeup to complete. The writeup should be completed in a separate file, which can be either a markdown file or a pdf document. There is a write up template that can be used to guide the writing process. Completing both the code in the Ipython notebook and the writeup template will cover all of the rubric points for this project.
