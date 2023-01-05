# COMP558_ComputerVision
COMP 558 Fundamentals of Computer Vision @ McGill Class Notes
Author: @asahahaha
```
* Instructor: Kaleem Siddiqi
* Term: Fall 2022
* Grading: 20% Assignments + 20% Group Research Project + 20% Midterm + 40% Final
```

All class notes written in [notion.so](https://www.notion.so/), click on the *lecture titles* to open the corresponding note page.

## [Lec 2 - RGB Images](COMP558_Lec2)
* Bayer pattern
* RAW to JPG

## [Lec 3 - Image Filtering](COMP558_Lec3)
* Smoothing (by local averaging), local differences
* Cross-correlation VS. convolution
* Impulse functions
* 1D VS. 2D
* Gaussians

## [Lec 4 - Edge Detection](COMP558_Lec4)
* Prewitt and Sobel (1960)
* Marr & Hildreth (1979)

## [Lec 5 - Canny Edge & Least Squares](COMP558_Lec5)
* Canny edge detection
* Least squares:
    * by linear regression
    * by total least squares

## [Lec 6 - Robust & Hough Transformation & RANSAC](COMP558_Lec6)
* Hough Transform
* RANSAC (Random Sample Consensus)

## [Lec 7 - Gaussian(Linear) Scale Spaces](COMP558_Lec7)
* Gaussian smoothing
    * 1) Iterative
    * 2) HEAT equation
* Gaussian property
* Lucas-Kanade Algorithm
* Coarse-to-fine
* Box(blob) detector

## [Lec 8 - Corners 1](COMP558_Lec8)
* Structure tensor
* (weighted) 2nd Moment Matrix

## [Lec 9 - Corners, cont’d & histogram](COMP558_Lec9)
* Corner → $\lambda_1$ & $\lambda_2$ both big and diffe
* Harris Corner Detection: $\lambda_1\lambda_2-k*(\lambda_1+\lambda_2)^2$
* Alternative Corner Detection: $\lambda_1\lambda_2/(\lambda_1+\lambda_2+\epsilon)$
* inner scale & outer scale
* HoG, histogram equalization

## [Lec 10 - SIFT Keypoints](COMP558_Lec10)
* Keypoint detection using laplacian pyramid & gradient → SIFT vector ⭐️⭐️
* Laplacian == DoG

## [Lec 11 & 12 - Image Registration](COMP558_Lec11&12)
* 1D & 2D Image Registration
    * iterative method
* Applications:
    * Lucas-Kanade
    * KLT Tracking
    * Shi & Tomasi (a 6D problem)
   
## [Lec 14 - Perspectives](COMP558_Lec14)
* Depth map
* Camera movement
    * similar triangles
* 1, 2, 3 point perspectives

## [Lec 15 - Rotations](COMP558_Lec15)
* 2D & 3D rotaion, scaling
* Homogenous coordinates

## [Lec 16 - Camera Extrinsics & Intrinsics](COMP558_Lec16)
* Camera calibration matrix K → intrinstics
* Extrinsics $R[I|-C]$

## [Lec 17 - Least Squares Estimation & SVD](COMP558_Lec17)
* A = $U∑V^T$

## [Lec 18 - Camera Calibration & Homographies](COMP558_Lec18)
* Having a list of paired point coordinates
    * Data normalization
* $P==M_1^{-1}P_{normalized}M_2$

## [Lec 19 - Homographies](COMP558_Lec19)
* Case 1: 1 camera, 1 image plane
* Case 2: 2 cameras, 1 image plane
* Case 3: 1 camera (rotation)
* Case 4: 2 images, 1 scene space (not same image plane)

## [Lec 20 - Epipolar Geometry](COMP558_Lec20)
* Essential matrix:
    * **Uses projection plane coordinates, not pixel coordinates**
* Fundamental matrix
    * **Uses pixel coordinates**

## [Lec 21 - Stereo & Epipolar Geometry](COMP558_Lec21)
* Estimating the fundamental matrix F
* Disparity Estimation
* Estimate Depth

## [Lec 22 - Binocular Disparity Estimation](COMP558_Lec22)
* Correspondence problem
* Occlusions
* Disparity space

## [Lec 23 - RGBD Cameras](COMP558_Lec23)
* How does depth camera work
* Iterative Closest Points (ICP)

## [Lec 24 - Convolutional Neural Networks (CNNs)](COMP558_Lec24)
* Classification problems in computer vision
