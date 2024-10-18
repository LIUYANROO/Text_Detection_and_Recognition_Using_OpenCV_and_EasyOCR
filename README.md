# CV_Assignment-1_LIU-YANRU

This repository contains the Jupyter Notebook for Assignment 1 of a Computer Vision course. 

## Description

The notebook includes:
- Implementation of various computer vision techniques and algorithms.
- Step-by-step instructions on how to process images using Python and OpenCV.
- Detailed explanations and outputs for better understanding of the tasks.

## Methods Used

This notebook applies several computer vision techniques and methods, including:

1. **Image Preprocessing:**
   - Conversion of images to grayscale.
   - Resizing images to uniform dimensions.
   - Histogram equalization for contrast adjustment.

2. **Feature Detection:**
   - Edge detection using Canny algorithm.
   - Corner detection with Harris Corner Detector.
   - Keypoint detection and description using SIFT (Scale-Invariant Feature Transform).

3. **Image Classification:**
   - Implementation of a basic image classification pipeline using a Support Vector Machine (SVM).
   - Feature extraction from images for training and testing the model.

4. **Object Detection:**
   - Application of the HOG (Histogram of Oriented Gradients) feature descriptor for object detection.
   - Sliding window technique to scan images for detecting objects.

5. **Image Segmentation:**
   - Simple image thresholding for segmenting foreground from background.
   - K-means clustering to perform color-based image segmentation.

6. **Image Transformation:**
   - Geometric transformations including image rotation, translation, and scaling.
   - Perspective transformation for correcting image distortion.


## Requirements

To run the notebook, the following dependencies must be installed:

- Python 3.x
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib

You can install these libraries using the following command:

```bash
pip install -r requirements.txt
