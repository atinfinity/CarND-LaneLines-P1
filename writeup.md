# **Finding Lane Lines on the Road** 

<img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" />

## **Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---

## Reflection

### 1. My Pipeline

My pipeline consisted of 5 steps.  

1. Extraction of the Lane Color(white, yellow)
1. Color Conversion(grayscale)
1. Smoothing
1. Edge Detection
1. Region Selection
1. Line Detection
1. Post-Processing

#### Extraction of the Lane Color(white and yellow)

#### Color Conversion

#### Smoothing

#### Edge Detection

#### Region Selection using ROI(Region Of Interest)

#### Hough Transform

#### Post-Processing

### 2. Identification of potential shortcomings with my current pipeline
- Change of the setting of camera
- Different　lighting conditions 

### 3. Suggestion of possible improvements to my pipeline

### Experimental material
- - [Color Conversion Test](https://github.com/atinfinity/CarND-LaneLines-P1/blob/master/experimental/Color-Conversion-Test.ipynb)

### Reference
- <https://github.com/udacity/CarND-Term1-Starter-Kit>
- <https://github.com/udacity/CarND-LaneLines-P1>
- <https://en.wikipedia.org/wiki/HSL_and_HSV>
