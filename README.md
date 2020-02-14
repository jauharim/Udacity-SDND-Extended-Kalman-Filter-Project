
This repository has files for the Udacity SDND Extended Kalman Filter Project. These files are:
1.	obj_pose-laser-radar-synthetic-input- data file (lidar and radar measurements; and the ground truth data)
2.	main.cpp-Communicates with the Udacity Simulator; receives the data measurements; call a function to run the Kalman Filter; calls a function to calculate RMSE
3.	FusionEKF.cpp- initializes the filter, calls the predict function, calls the update function
4.	kalman_filter.cpp- defines the predict function, update function for lidar, and the update function for radar
5.	tools.cpp- function to calculate RMSE and the Jacobian matrix
6.	kalman_filter.h - defines the KalmanFilter class
7.	measurement_package.h - defines the MeasurementPackage class
8. Writeup_Extended_Kalman_Filters_Project.pdf- my writeup with the Project details

The Project work summary is:
1.	In tools.cpp, fill in the functions that calculate root mean squared error (RMSE) and the Jacobian matrix.
2.	Fill in the code in FusionEKF.cpp. You'll need to initialize the Kalman Filter, prepare the Q and F matrices for the prediction step, and call the radar and lidar update functions.
3.	In kalman_filter.cpp, fill out the Predict(), Update(), and UpdateEKF() functions.
