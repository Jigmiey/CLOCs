# CLOCs
## Introduction
For 3D object recognition, mainly three kinds of fusion can be done which are early, intermediate and late fusion.  Camera Lidar Object Candidates' Fusion (CLOCs) is a late fusion technique that combines 2D (from Camera)and 3D detectors(from Lidar) proposals and improve the detection results(prediction score). 
Here, CLOCs for 3D Object Detection network is used and a comprehensive study of different fusion network is done. This study is conducted using the KITTI training set and test results were produced based on the KITTI validation set.

The fact that the CLOCs adopt late fusion makes it flexible and can incorporate any 2D or 3D detector combination into its pipeline. Two 3D detectors used here are 
1. SECOND
2. Voxel - RCNN

and Cascade RCNN is the only 2D detector used here. Therfore, we obtain two combinations of 2D-3D detectors.   
