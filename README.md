
# Project 1 - Finding the lane lines

## Concepts learned:
* Region Masking
* Gaussian Blur
* Canny Edge detection
* Hough transform

## Action plan:
* Convert the image to grayscale
* Smoothen the edges using Gaussian blur
* Find the edges using Canny edge detector
* Mask the image
* Find lines using Hough transform
* Fit the points in a line and extrapolate the line

### Pipeline

<p align="center">
  <img src="./readme-files/output_2_2.png">
  Taking a sample image.
</p>

<p align="center">
  <img src="./readme-files/output_6_1.png">
  Grayscaling the image.
</p>

<p align="center">
  <img src="./readme-files/output_8_0.png">
  Applying Gaussian Blur to smoothen image and remove noise. 
</p>

<p align="center">
  <img src="./readme-files/output_10_0.png">
  Image after applying Canny Edge Detection Algorithm.
</p>

<p align="center">
  <img src="./readme-files/output_12_1.png">
  Masking the image to a region of interest as the upper part of image contains Sky and the lane lines are in the center. 
</p>

<p align="center">
  <img src="./readme-files/output_13_0.png">
  Applying Hough Transform to find line segments and extrapolating them to find two lane lines.  
</p>

<p align="center">
  <img src="./readme-files/output_14_1.png">
  Finally drawing the lines on the orignal image.  
</p>


This pipeline is ran on the video and the output can be seen here.[Video Output](https://youtu.be/cbQyKotdif4)
