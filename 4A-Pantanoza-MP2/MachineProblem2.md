# Image Processing Techniques using OpenCV MP2

## Overview
This script demonstrates basic image processing techniques using OpenCV, including image scaling, rotation, blurring, and edge detection. These operations are fundamental in computer vision and image processing tasks and are commonly used in various applications, such as enhancing images, detecting objects, and preparing images for further analysis.

Here is the the documentation : https://github.com/PhamHanni/CSST106-CS4A/blob/main/4A-Pantanoza-MP2.pdf

## Script Usage

The script performs the following image processing techniques:

- **Scaling**: Resizes the image based on specified scaling factors.
- **Rotation**: Rotates the image by a specified angle.
- **Blurring**: Applies a Gaussian blur to the image to reduce noise.
- **Edge Detection**: Detects edges in the image using the Canny edge detection algorithm.

## Expected Output

Original Image: Displays the original image loaded from the specified path.
- **Scaled Image**: Displays the image resized based on the scaling factors.
- **Rotated Image**: Displays the image rotated by the specified angle.
- **Blurred Image**: Displays the image after applying Gaussian blur.
- **Edge Detection**: Displays the edges detected in the image using the Canny algorithm.
  
## Functions Overview

- **scale_image()**: Resizes the image to new dimensions based on scale_x and scale_y. Useful for enlarging or shrinking images.
- **rotate_image()**: Rotates the image around its center. Commonly used for adjusting image orientation.
- **blur_image()**: Smoothens the image to reduce noise and detail. This is useful for preprocessing steps in computer vision.
- **detect_edges()**: Identifies edges in the image, highlighting areas of high intensity change, which is useful for object detection and image segmentation.

## Additional Tips

You can adjust the parameters of each function to customize the effects according to your needs.
Make sure your input images are in the correct path and format; otherwise, OpenCV will not be able to load them.

Here is the g-colab documentation : https://colab.research.google.com/drive/1kfogc5ZJpUXp8rVrPMGUMlkCGwiD_sjf#scrollTo=zgeXI7rfSCGr
