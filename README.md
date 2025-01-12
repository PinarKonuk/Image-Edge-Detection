# Edge Detection and Line Detection with Sobel, Canny, and Hough Transform

## 📋 Project Description

This project demonstrates the implementation of various edge detection and line detection algorithms using Python and OpenCV. It includes the following techniques:

* Sobel Edge Detection: Detects horizontal and vertical edges in images by calculating gradients.

* Canny Edge Detection: A multi-step process for detecting edges with precise thresholds and noise reduction.

* Hough Transform: Identifies linear structures (lines) in images based on detected edges.

The aim of this project is to showcase the application of these algorithms in detecting and visualizing edges and lines in images.

## 🚀 Features

Apply Sobel Edge Detection to detect horizontal, vertical, and combined edges.

Perform Canny Edge Detection with customizable thresholds.

Use Hough Transform to identify and draw lines on the edges detected in an image.

Modular Python code structure for easy customization and experimentation.

## 🔧 Technologies Used

* Python: Programming language

* OpenCV: Image processing library

* NumPy: Numerical computations

* Matplotlib: Visualization library

## 🔍 Technical Details

1. Sobel Edge Detection

The Sobel operator calculates gradients in the horizontal (X) and vertical (Y) directions to detect edges. These gradients can be combined to show all edges in the image.

2. Canny Edge Detection

This method involves multiple steps:

Noise reduction using Gaussian blur.

Gradient calculation.

Non-maximum suppression to thin edges.

Double thresholding to identify strong and weak edges.

3. Hough Transform

Hough Transform identifies lines in an image by transforming edge points into parameter space and detecting alignments corresponding to lines.
