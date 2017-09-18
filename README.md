# GaitPrediction
Use accelerometer data to predict human gait cycles.

Gait cycle segmentation is not only useful for wearable products, automated selection of the gait parameters is also very helpful to medical practices to help physician's decision making.


## Dataset Specification

Activities: Walking and running

Accelerometer:

- Placement of 3-axis Accelerometer: Anywhere around the ankle in any orientation as shown in Figure 1
- Sensitivity of the Accelerometer: (+-) 4g or more
- Sampling Frequency: Preferred - 128 Hz 

Input data:

accX - accelerometer data from X - axis
accY - accelerometer data from Y - axis
accZ - accelerometer data from Z - axis

Input data format: The accelerometer signals should be in units of m/s^2 and need to be in .mat format [in Matlab file format].

IMPORTANT NOTE: The data should consist of ONLY walking and running segments of the signal. Segments corresponding to inactivity or any other activity should be removed from the signals prior to running the implementation.
