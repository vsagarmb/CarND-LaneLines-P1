# **Finding Lane Lines on the Road** 

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image0]: ./examples/out/0-solidYellowLeft.jpg "Original"
[image1]: ./examples/out/1-gray_solidYellowLeft.jpg "Grayscale"
[image2]: ./examples/out/2-blurred_solidYellowLeft.jpg "Blurred"
[image3]: ./examples/out/3-canny_solidYellowLeft.jpg "Canny"
[image4]: ./examples/out/4-region_solidYellowLeft.jpg "RegionIfInterest"
[image5]: ./examples/out/5-hough_solidYellowLeft.jpg "LaneLines"
[image6]: ./examples/out/6-single_solidYellowLeft.jpg "SingleLaneLines"
[image7]: ./examples/out/7-final_solidYellowLeft.jpg "MergedFinal"

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
