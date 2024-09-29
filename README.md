# Exploring the Role of Computer Vision and Image Processing in AI MP1

## Overview
This project explores the critical role of **computer vision** and **image processing** in Artificial Intelligence (AI). It covers essential image processing techniques, case studies, and practical implementations that demonstrate how AI systems interpret and analyze visual data.

## Objective
The objective of this project is to:
- Understand the importance of image processing in AI.
- Explore various image processing techniques such as filtering, edge detection, and segmentation.
- Discuss real-world applications like **autonomous vehicles** that utilize these techniques.
- Implement a simple image processing model to demonstrate its use in AI.

## Contents
1. **Presentation**: A PowerPoint presentation that provides an introduction to computer vision and image processing techniques in AI.
2. **Video**: A video walkthrough of the presentation is available for preview.
3. **Colab Implementation**: A practical demonstration of image processing using Python on Google Colab.

## Image Processing Implementation
You can explore the implementation of image processing techniques, such as edge detection and segmentation, through this interactive Google Colab notebook:

[![Watch the video](./thumbnail.png)](https://youtu.be/-Ni0ZAvTJk8)

In this notebook, you will find:
- **Edge Detection**: The Canny edge detection algorithm applied to a sample image to identify the boundaries and edges of objects within the image.
- **Image Segmentation**: Techniques to segment an image into different regions, making it easier to identify specific objects or areas of interest.
- **Filtering**: A demonstration of noise reduction using filters to enhance image quality and improve feature extraction.

### Explanation:
The Colab notebook provides a step-by-step demonstration of basic image processing techniques. By running the code, you can experiment with applying filters, detecting edges, and segmenting images. These processes are critical in enabling AI systems to interpret visual data more effectively. The notebook includes both the code and explanations for how these techniques are implemented and how they contribute to solving real-world visual problems.

## Video Preview
[![Watch the video](./thumbnail.png)]([./4A-PANTANOZA-MP1.mp4](https://github.com/PhamHanni/CSST106-CS4A/blob/main/4A-Pantanoza-MP1/4A-PANTANOZA-MP1.mp4))

*Click the image above to watch the video presentation.*

## Key Topics Covered
- **Computer Vision and AI**: How AI systems process and interpret visual data from the world.
- **Image Processing Techniques**:
  - Filtering (Noise reduction, enhancement)
  - Edge Detection (Identifying object boundaries)
  - Segmentation (Dividing an image into meaningful parts)
- **Case Study: Autonomous Vehicles**:
  - Use of image processing for lane detection, obstacle identification, and decision-making in real-time.
- **Emerging Technique: Deep Learning-Based Image Analysis**:
  - The role of deep learning, especially Convolutional Neural Networks (CNNs), in transforming image processing in AI.

## How to View the Presentation
- You can download the **PowerPoint Presentation** from this repository.
- Click on the image above to watch the **video walkthrough** of the presentation.


# Image Processing with OpenCV

## Introduction

In this repository, we explore various image processing techniques using OpenCV, a powerful library for computer vision. This script allows you to perform a range of operations on images, from basic transformations to advanced filtering and edge detection. Below, we provide an overview of the capabilities demonstrated:

### Image Display

We start by providing functions to display images using matplotlib. These functions allow you to visualize single images or compare two images side by side.

### Image Upload and Conversion

You can upload an image from Google Colab and convert it into a format suitable for OpenCV processing. This step is essential for performing subsequent image manipulations.

### Basic Image Transformations

- **Scaling**: Adjust the size of the image by a specified factor.
- **Rotation**: Rotate the image by a given angle.

### Blurring Techniques

- **Gaussian Blur**: Smoothens the image to reduce noise and detail.
- **Median Blur**: Applies median filtering to remove salt-and-pepper noise.
- **Bilateral Filter**: Reduces noise while preserving edges, making it ideal for noise reduction without losing detail.
- **Box Filter**: Averages pixel values within a specified kernel size for smoothing.
- **Motion Blur**: Simulates the effect of motion blur by applying a linear kernel.

### Edge Detection

- **Canny Edge Detection**: Identifies edges in an image by detecting areas of rapid intensity change.
- **Sobel Edge Detection**: Uses the Sobel operator to detect edges by computing gradient magnitudes.
- **Laplacian Edge Detection**: Finds edges by applying the Laplacian operator, which highlights areas of rapid intensity change.
- **Prewitt Edge Detection**: Utilizes the Prewitt operator to detect edges in the x and y directions.

### Sharpening

- **Unsharp Masking**: Enhances image sharpness by subtracting a blurred version from the original image.

### Interactive Processing

Users can interactively choose an image transformation to apply from a predefined list, including scaling, rotation, various blurring techniques, and edge detection methods.

### Comparison Visualization

The script concludes by displaying the original and processed images for easy comparison, allowing you to assess the effects of each transformation visually.

This script provides a comprehensive toolkit for image processing, making it an invaluable resource for tasks such as image enhancement, noise reduction, and feature extraction.

### Step by Step Process on how to apply this Image Processing techniques

Ipynb notebook file: "https://github.com/PhamHanni/CSST106-CS4A/blob/main/Pantanoza_Exer1_Image_Processing_Techniques.ipynb"

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


# Image Processing Techniques Overview

This repository showcases a variety of advanced image processing techniques implemented using Python. These techniques are commonly used in computer vision tasks such as object detection, image matching, and image alignment. Below is an in-depth explanation of each method used in this project, along with its application and significance.

## 1. SIFT (Scale-Invariant Feature Transform)

**Overview:**  
SIFT is a popular algorithm used to detect and describe local features in images. It identifies keypoints that are stable across different scales, rotations, and transformations, making it highly reliable for feature matching.

**How it Works:**  
SIFT detects keypoints by finding extrema in the Difference of Gaussian (DoG) space. Each keypoint is assigned a descriptor, a vector that describes the local image gradient around the keypoint. These descriptors are then used to match keypoints across different images.

**Applications:**
- Object recognition
- Image stitching for creating panoramas
- 3D reconstruction from multiple images
- Motion tracking in videos

**Strengths:**  
- Highly accurate and robust feature detection
- Invariant to scale, rotation, and partially to affine transformations
- Works well in cluttered and noisy environments

## 2. SURF (Speeded-Up Robust Features)

**Overview:**  
SURF is a feature detection algorithm that offers a balance between speed and accuracy. It is designed to be faster than SIFT while still being robust to scaling, rotation, and changes in brightness.

**How it Works:**  
SURF uses a Hessian matrix-based approach to detect keypoints and describes them using a distribution of Haar wavelet responses within the interest point neighborhood. This method makes SURF significantly faster, especially for real-time applications.

**Applications:**
- Real-time object recognition
- Robotics and autonomous navigation
- Image registration for medical imaging
- Augmented reality overlays

**Strengths:**  
- Faster than SIFT due to simplified calculations
- Good performance under scale and rotation variations
- Suitable for real-time applications

## 3. ORB (Oriented FAST and Rotated BRIEF)

**Overview:**  
ORB combines the FAST (Features from Accelerated Segment Test) keypoint detector and the BRIEF (Binary Robust Independent Elementary Features) descriptor. It is an efficient, free alternative to SIFT and SURF, particularly optimized for low-power devices and real-time processing.

**How it Works:**  
ORB uses the FAST algorithm to detect keypoints and applies an orientation component to make it rotation invariant. The BRIEF descriptor is then used, which is a binary descriptor that is computationally inexpensive compared to floating-point descriptors used in SIFT and SURF.

**Applications:**
- Mobile vision applications
- Real-time image matching
- SLAM (Simultaneous Localization and Mapping) in robotics
- Gesture recognition

**Strengths:**  
- Extremely fast and efficient
- Suitable for devices with limited computational power
- Invariant to rotation and scaling, with good matching performance

## 4. Feature Matching with SIFT

**Overview:**  
Feature matching is essential for finding correspondences between two images. SIFT’s descriptors are used to match features between images, typically using the BFMatcher (Brute Force Matcher) or FLANN (Fast Library for Approximate Nearest Neighbors) to identify the best matches.

**How it Works:**  
- Keypoints are detected in both images using SIFT.
- Descriptors from both images are compared to find pairs of matching keypoints.
- Matches are refined using distance ratio tests or RANSAC (Random Sample Consensus) to eliminate outliers.

**Applications:**
- Image registration and alignment
- Object recognition
- 3D reconstruction from stereo images
- Panorama stitching

**Strengths:**  
- High accuracy in finding corresponding features
- Robust against noise and varying image conditions
- Can be used in combination with homography for precise image transformations

## 5. Image Alignment using Homography

**Overview:**  
Image alignment involves adjusting one image to match another by transforming it into the same coordinate system. Using homography, images can be accurately aligned, making it possible to overlay them perfectly or blend them into a single seamless image.

**How it Works:**  
- Keypoints and descriptors are first extracted from both images using a feature detection algorithm (e.g., SIFT).
- Corresponding points are found through feature matching.
- A homography matrix is computed using RANSAC, mapping points from one image to the other.
- The second image is warped using this homography matrix to align with the first.

**Applications:**
- Panorama creation by stitching multiple images
- Object tracking in videos
- Augmented reality, where virtual objects are overlaid on real-world scenes
- Document scanning and perspective correction

**Strengths:**  
- Precise alignment of images for various transformations
- Works well for planar objects and scenes
- Enables accurate object overlay and image blending

## Getting Started

To explore these techniques and run the code, ensure you have Python installed along with the required libraries. Follow the steps below to set up your environment:

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo.git
cd your-repo

# Install dependencies
pip install -r requirements.txt

