# CN_ND_SLAM
[![Udacity Computer Vision Nanodegree](http://tugan0329.bitbucket.io/imgs/github/cvnd.svg)](https://www.udacity.com/course/computer-vision-nanodegree--nd891)

## Repo for Exercises and the Project of the Computer Vision Nanodegree SLAM Chapter
![](https://image.slidesharecdn.com/visualizationofsimultaneouslocalizationandmappingusingsvg-icisbc2013-151120024446-lva1-app6891/95/visualization-of-simultaneous-localization-and-mapping-using-svg-icisbc-2013-3-638.jpg?cb=1447987646)

## Exercises
- The exercises consist of : 
  - computing Optical Flow between consecutive image using a simple Shi Tomasi Feature Detector 
  - Programming & debugging a 1D Histogram Filter in Python, mainly implementing the update and prediction steps 
  - An Intro to Graph SLAM in a 1D environment based on x Positions of the robot and land mark measurements as well as dealing with measurement uncertainty
 
 ## Project 
 
 - The project implements a 2D Graph Slam with Motion & Landmark Measurements 
 - The sense function was implemented, it considers uniformaly distributed noise for both motion and landmarks
 - The matrix omega and vector xi are both updated based on the measurements and observations at each time step 
 - The results are computed by calculating the output vector mu with the inverse of omega and vector xi 
