# **Finding Lane Lines on the Road** 

---

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

First, I filtered the impossible slope about the lane line.

Second, I draw the lane line (According to y = ax + b formula)

Third, apply it to the following pipeline.

My Pipeline includes five steps:
1. Gray scale
2. Gaussian Smoothing
3. Canny
4. Masked
5. Hough transform


### 2. Identify potential shortcomings with your current pipeline

One shortcoming is the lane line drawing might "blink" sometimes, 


### 3. Suggest possible improvements to your pipeline

A possible improvement would be to build a stable line that won't "blink".



---
and the project will be done.

