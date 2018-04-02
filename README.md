# Term 2 Project 2 - Unscented Kalman Filters
Self-Driving Car Engineer Nanodegree Program

In this project you will utilize an unscented kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower than the tolerance outlined in the project rubric. 

This project involves the Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make` 
   * On windows, you may need to run: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./ExtendedKF `

## Modifications
The files that have been modified to make the kalman filter reach the desired RMSE thresholds are:
	1. ukf.cpp
	2. ukf.h
	3. tools.cpp
All of these can be found in the src/ folder.

Output results of the Normalized Innovation Squared and a screenshot of the resulting simulator run can be found in the results folder 

A screenshot of the result for dataset 1 in the term2 sim is below.
![Screenshot](/results/result_ss.jpg)