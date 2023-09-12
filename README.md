# Camera Lidar Object Candidates for 3D Object Detection 
Extension of work done by Su Pang, Daniel Morris, Hayder Radha on 3D object detection by fusing LiDAR and Camera sensory data. 


@article{pang2020clocs,
  title={CLOCs: Camera-LiDAR Object Candidates Fusion for 3D Object Detection},
  author={Pang, Su and Morris, Daniel and Radha, Hayder}, 
  booktitle={2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2020}
  organization={IEEE}
}

## Introduction
For 3D object recognition, mainly three kinds of fusion can be done which are early, intermediate and late fusion.  Camera Lidar Object Candidates' Fusion (CLOCs) is a late fusion technique that combines 2D (from Camera)and 3D detectors(from Lidar) proposals and improve the detection results(prediction score). 
Here, CLOCs for 3D Object Detection network is used and a comprehensive study of different fusion network is done. This study is conducted using the KITTI training set and test results were produced based on the KITTI validation set.

The fact that the CLOCs adopt late fusion makes it flexible and can incorporate any 2D or 3D detector combination into its pipeline. Two 3D detectors used here are 
1. SECOND
2. Voxel - RCNN

and Cascade RCNN is the only 2D detector used here. Therfore, we obtain two combinations of 2D-3D detectors.  
## Network Architectures 
<img width="714" alt="clcs" src="https://github.com/Jigmiey/CLOCs/assets/48585119/c7b84e8e-e551-4492-99da-1528118bbc19">

<img width="729" alt="fusion" src="https://github.com/Jigmiey/CLOCs/assets/48585119/c4873cac-f9e0-4589-8f67-eb9058a90ad8">

## Results 
<img width="743" alt="second-cascade" src="https://github.com/Jigmiey/CLOCs/assets/48585119/e0903f01-a809-4093-9c48-d03d3cf8db00">
<img width="766" alt="voxel-cascadercnn" src="https://github.com/Jigmiey/CLOCs/assets/48585119/55bd8974-2ee1-43da-8414-38c187d4ecc7">


