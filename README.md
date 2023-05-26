# Codes for all the tasks done in the workshop on Computer Vision

Notes for the workshop are written at this <a href = "https://mhardik003.notion.site/CVIT-Worksop-9a0bfe2f318140408556b119d6cf4ac4">notion doc</a>


Have the following packages installed to run the programs:
```
pip install opencv-python
pip install dicom
pip install pydicom
pip install scipy
pip install scikit-image
```

Also, feel free to make a pull request if you find any bugs in the code, since it is my first time doing this, I am sure there will be a lot of bugs.

---


<br>

Short rundown of tasks done on each day:

## Day 1

### Session 1 (Basics)

    - Intro to Python Notebooks
    - Intro to Python
    - Intro to Numpy
    - Intro to Image Processing ( OpenCV )
        - Importing and
        - Chroma Keying
        - To be Done - Frequency Histogram
        - To be Done - Thresholding

## Session 2 (Barcode Detection and Scanning)

    - Sobel Filters
    - Bar Code Detection and Scanning
    - Learning about EAN-13 Barcode System
    - Thresholding Methods
        - Global Threshholding (using same threshold for all pixels)
        - Adaptive Threshholding (using different threshold for different pixels)

    - HW
        -Find seed fill algorithm (similar to DFS)
        - Sobel Filters

# Day 2

## Task 1 (Document Imaging)

    - Intro to Document Imaging
    - Hands-on Task
        - Canny Edge Detection
        - Hough Line Transform
        - Skew Correction
            -(Not aligned with the horizontal axis)
            - Correction by Rotation
            - Rotation of a document image from its intended orientation
            - Reduces the acuracy of OCR
        - Line And Word Detection
        - Reading Check Number

        - HW : try root(sobelX^2 + sobel^2) and compare with Canny
        - Non-Maximal Suppresion

## Task 2 (Word and Line Segmentation)

## Task 3 (Cheque Number Reader)
    - Understanding the nomeclature of a cheque
    - Smoothing techniques
    - Removing noise and borders
    - Intro to OCR (by template matching)
    - Sobel Filters
    - Black Hat Transform


# Day 3

## Session 1 (Convex Optimization)

    - Intro to Convex Optimization
    - Using CVXOPT library
    - Solving Knapsack Problem
    - Smoothing graph using Convex Optimization
    - Realtime Application of smoothing boxes in video

## Session 2 (Medical Imaging)

    - Windowing for different parts of the body
    - Parallel Beam Tomographic Reconstruction using Simple Backprojection


# Day 4 

## Session 1 ( 3-D )
    - Intro to 3D
    - PyMesh
    - Open3D
    - ICP
     
## Session 2
    - Blender

# Day 5
## Sesion 1 (Basics of ML)
    - Basics of ML
    - K- Nearest Neighbours
    - K-Means Clustering
        - Distance Metrics

    - Linear Decision Boundaries
        - Loss function 
        - Minimizing the loss fucntion with respect to the parameters (weights)
        - Gradient Descent
            - Different Loss Functions for Gradient Descent

