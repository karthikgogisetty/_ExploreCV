# 📸 Exploring OpenCV

## 🧠 Introduction

This repository showcases a structured journey into computer vision using **OpenCV**. It contains hands-on experiments demonstrating fundamental and advanced image processing techniques — from grayscale conversion to motion detection and template matching.

> 🔬 The goal: To build intuition around OpenCV’s core functionalities by applying them to real-world image tasks with visual outputs.

---

## 🧱 Topics Covered

### 🖼️ 1. Image Basics
- Convert BGR to Grayscale
- Drawing primitives (Lines, Rectangles, Circles, Polygons)
- Writing on images

### 🌈 2. Image Blending
- Additive blending using `cv2.add`
- Weighted blending using `cv2.addWeighted`

### 🧮 3. Bitwise Operations & Logo Overlay
- Region of Interest (ROI)
- Binary masks & thresholding
- Overlaying logos on images with logical operations

### 🎚️ 4. Thresholding Techniques
- Binary Thresholding
- Adaptive Thresholding
- Comparison of grayscale vs color thresholding

### 🎯 5. Color Filtering (HSV)
- Color isolation with HSV conversion
- Masking specific color ranges
- Noise reduction and masking using convolution

### 🔍 6. Image Smoothing Techniques
- 2D Convolution
- Gaussian Blur
- Median Blur
- Bilateral Filtering

### 🧼 7. Morphological Operations
- Erosion & Dilation
- Opening & Closing (Noise correction in FG/BG)

### 🧱 8. Edge Detection
- Laplacian, Sobel (X/Y)
- Canny Edge Detection (with double thresholding)

### 🧩 9. Template Matching
- Matching sub-image patterns using `cv2.matchTemplate`
- Real-world application with celebrity face detection

### 🧠 10. Feature Detection (ORB)
- Detecting image corners
- Tuning number of corners and quality levels
- ORB (Oriented FAST and Rotated BRIEF)

### 🎯 11. Feature Matching
- Match keypoints even under rotation
- Adjusting match thresholds to reduce false positives

### 🎥 12. Motion Detection (Background Subtraction)
- Foreground/Background detection with `cv2.createBackgroundSubtractorMOG2`
- Real-time detection on video frames

---

## 🖼️ Sample Visual Outputs

| Task                     | Example Output                     |
|--------------------------|-------------------------------------|
| Grayscale Conversion     | <img src="https://user-images.githubusercontent.com/69350191/91662700-b7d67000-eb01-11ea-8e74-bee3503e9fd0.PNG" width="300"/> |
| Drawing Shapes           | <img src="https://user-images.githubusercontent.com/69350191/91662706-c6248c00-eb01-11ea-9a61-2285000fbfbe.PNG" width="300"/> |
| Image Blending           | <img src="https://user-images.githubusercontent.com/69350191/91645451-c6ba1580-ea62-11ea-8724-9c8bbc1b4467.PNG" width="300"/> |
| Adaptive Thresholding    | <img src="https://user-images.githubusercontent.com/69350191/91645554-9d4db980-ea63-11ea-9dc4-d77e3a805671.PNG" width="300"/> |
| Canny Edge Detection     | <img src="https://user-images.githubusercontent.com/69350191/91746495-4a4a4280-ebda-11ea-9c59-4520c09bae76.png" width="300"/> |
| Motion Detection         | <img src="https://user-images.githubusercontent.com/69350191/91861267-3e1dbe00-ec8a-11ea-928d-c566b1d9e213.png" width="300"/> |
``

---

## 📚 Resources

- 🔗 [OpenCV Docs](https://docs.opencv.org/master/d6/d00/tutorial_py_root.html)
- ▶️ [Python OpenCV Tutorials - Sentdex](https://www.youtube.com/playlist?list=PLQVvvaa0QuDdttJXlLtAJxJetJcqmqlQq)

---

## 🚀 How to Run

### Install Requirements
```bash
pip install opencv-python numpy
