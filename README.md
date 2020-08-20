<h1>
<p align="center">
Vehicle and Lane Detection
<br>
<font size="5"></font>
</h1>

#### CSS 487: Computer Vision Final Project

Taking steps toward autonomous vehicles. 

We developed a lane and vehicle detection program by utilizing various computer vision methods. As a summary, we utilized a Hough Transform for lane detection, trained a support vector machine on a HOG (histogram of gradient) image representation, and used a sliding window approcha to detect vehicles in our ROI. In addition, we counted the number of vehicles in each frame by counting our bounding boxes.

Our C++ solution requires C++17

Link to Google Doc Report: https://docs.google.com/document/d/1b4tJOJyv5KYdL_-rR2neeoJutpU8AYpMxji59ZpoVhk/edit?usp=sharing

![demo](outputs/ld_vd_1.gif "demo")


#### Support Vector Machine Training

```
-- Performing a Test on the SVM --
 -------- Training SVM ---------
x_train size = 17560
y_train size = 17560
x_test size = 200
y_test size = 200
-- Training Complete --
SVM Test Accuracy = 0.965000
```

**Hough Transform for Lane Detection**
![demo](outputs/detected_lanes_py_5.gif "demo")

**Histogram of Oriented Gradients & SVM for Vehicle Detection**
![demo](outputs/detected_vehicles_1.gif "demo")
