[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Optical flow to detect vehicle and track its speed
This repository contains code to detect and track a moving vechilce using Sparse Optical Flow. The moving vechile is detected by taking the difference between two consecutive images, contour detection, SIFT feature matching, and pixel displacement. The speed of the vehicle was computed by taking the average of the pixel displacement of various features of the vehicle detected using SIFT. Achieved an accuracy of 99% for various speeds. The program can be executed in real-time and can find application in speed-limit enforcement.

Results can be found in the "results" directory.
## Flowchart
<img src=https://github.com/abhijitmahalle/optical_flow/blob/master/gif/flowchart.png width=100% height=100%>

## Video Output
<img src=https://github.com/abhijitmahalle/optical_flow/blob/master/gif/output_10mph.gif width=100% height=100%>

## Results
<img src=https://github.com/abhijitmahalle/optical_flow/blob/master/results/accuracy/10mph.png width=45% height=45%> <img src=https://github.com/abhijitmahalle/optical_flow/blob/master/results/accuracy/20mph.png width=45% height=45%>
<p align="center">
<img src=https://github.com/abhijitmahalle/optical_flow/blob/master/results/accuracy/25mph.png width=45% height=45%>
