
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

<center>Taking a sample image.</center>
![Sample Image](./readme-files/output_2_2.png)

<center>Grayscaling the image. </center>
![Gray Image](./readme-files/output_6_1.png)

<center>Applying Gaussian Blur to smoothen image and remove noise. </center>
![Gray Image Blur](./readme-files/output_8_0.png)

<center>Image after applying Canny Edge Detection Algorithm.</center>
![Canny Image](./readme-files/output_10_0.png)

<center>Masking the image to a region of interest as the upper part of image contains Sky and the lane lines are in the center.</center>
![ROI](./readme-files/output_12_1.png)

<center>Applying Hough Transform to find line segments and extrapolating them to find two lane lines.</center>
![Hough Transform](./readme-files/output_13_0.png)

<center>Finally drawing the lines on the orignal image.</center>
![Orignal Image with lines](./readme-files/output_14_1.png)

This pipeline is ran on the video and the output can be seen here.[Video Output](https://youtu.be/cbQyKotdif4)
