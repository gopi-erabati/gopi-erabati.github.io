---
layout: page
permalink: /projects/
title: Projects
description: 
nav: true
nav_order: 3
---

## Research Projects

### 3D Object Detection and Relative Localization using a 3D sensor embedded on a Mobile Robot

[Code](https://github.com/gopi-erabati/Object-Pose-Estimation); [Master Thesis](https://github.com/gopi-erabati/Object-Pose-Estimation/blob/master/GopikrishnaErabati-thesis.pdf) at LAAS-CNRS, Toulouse, France

This thesis tries to solve the issue of object pose estimation using 3D data of scene acquired from 3D sensors (e.g., Kinect, Orbec Astra Pro among others). 3D data has an advantage of independence from object texture and invariance to illumination. The proposal is divided into two phases: An offline phase where the 3D model template of the object (for estimation of pose) is built using Iterative Closest Point (ICP) algorithm. And an online phase where the pose of the object is estimated by aligning the scene to the model using ICP, provided with an initial alignment using 3D descriptors (like Fast Point Feature Transform (FPFH)). The approach we develop is to be integrated on two different platforms: 1) Humanoid robot ‘Pyrene’ which has Orbec Astra Pro 3D sensor for data acquisition, and 2) Unmanned Aerial Vehicle (UAV) which has Intel RealSense Euclid on it. The datasets of objects (like electric drill, brick, a small cylinder, cake box) are acquired using Microsoft Kinect, Orbec Astra Pro and Intel RealSense Euclid sensors to test the performance of this technique. The objects used to test this approach are the ones used by robots. This technique is tested in two scenarios, firstly, when the object is on the table and secondly when the object is held in hand by a person. The range of objects from the sensor is 0.6 to 1.6m. This technique could handle occlusions of the object by hand (when we hold the object), as ICP can work even if partial object is visible in the scene.

| Single object pose estimation | Multiple objects pose estimation |
| --- | --- |
| [![](../assets/img/projects/objposeest1.png)](https://www.youtube.com/watch?v=8NoalZesWR0) | [![](../assets/img/projects/objposeest2.png)](https://www.youtube.com/watch?v=cyvhGSBhMF0) |

***********

### Human Activity Recognition in Video

[Code](https://github.com/gopi-erabati/Human-Activity-Recognition-from-Videos-Using-Machine-Learning) [Report](https://github.com/gopi-erabati/Human-Activity-Recognition-from-Videos-Using-Machine-Learning/blob/master/report_HumanActivityDetction_SSI_GopikrishnaErabati_MohitKumarAhuja.pdf)

Actions can be characterized by spatiotemporal patterns. Like object detection, action detection finds the recurrences of such spatiotemporal patterns through pattern matching. I worked on a few types of interest-point based feature extractions like Spatio-Temporal Interest Point (STIP), 3D SIFT and Histogram of Oriented Optical Flow (HOOF) features. With the use of SVM classifier, I classified the actions. I implemented this human activity recognition on KTH dataset which has six actions like boxing, hand waving, hand clapping, jogging, running, and walking of 100 videos each.

[<img src="../assets/img/projects/action.png" width="500" height="250">](https://www.youtube.com/watch?v=Cn639T80BhQ)

**********
### Mapping, Autonomous Navigation and Localization of TurtleBot using ROS

[Code](https://github.com/gopi-erabati/Mapping_LocalizationOfARMarkers_Navigation_ROS_Turtlebot) [Report](https://github.com/gopi-erabati/Mapping_LocalizationOfARMarkers_Navigation_ROS_Turtlebot/blob/master/report_mappingAndLocalization_ROS.pdf)

The motto of the project is to gain experience in the implementation of different robotic algorithms using ROS framework. 
1. The first step of the task is to build a map of the environment and navigate to a desired location on the map.
2. Next, we must sense the location of marker (e.g., AR marker, color markers etc.) in the map, where there is pick and place task, and autonomously localize and navigate to the desired marker location.
3. After reaching the desired marker location, we have to precisely move towards the specified location based on visual servoing.
4. At the desired location, we have a robotic arm which picks up an object (e.g., a small cube) and places it on our TurtleBot (called the pick and place task).
5. After the pick and place task, again the robot needs to find another marker, which specifies the final target location, and autonomously localize and navigate to the desired marker location, which finishes the complete task of the project. 

Our team developed the software to implement the 1, 2 and 5 points in the above list. The implementation can be found in the attached project report.

[<img src="../assets/img/projects/turtlebotros.png" width="500" height="250">](https://www.youtube.com/watch?v=YPKXm8cRIKs)

**********
### Development of 3D Human Body Scanner using Kinect and PCL

[Code](https://github.com/gopi-erabati/3D-Reconstruction-of-Human-using-Kinect-v2-and-PCL) [Report](https://github.com/gopi-erabati/3D-Reconstruction-of-Human-using-Kinect-v2-and-PCL)

The main objective of this project is to develop human 3D scanner software able to fully interface with a scanner rig composed of a turning table and a stationary depth sensor. The software is aimed to perform full body scan under 90 seconds. A friendly, interactive graphical user interface provides simple control and outputs watertight mesh results that can be used mainly but not limited to 3D printing. The project was implemented using Microsoft Kinect v2 and PCL library in a Windows OS.

| Registration using ICP with Normals | Noise Removal and Smoothing |
| --- | --- |
| ![](../assets/img/projects/scanner1.png) | ![](../assets/img/projects/scanner2.png) |

**********
### Development of Computer Vision Toolbox in C++ and MATLAB using OpenCV

[Code(C++)](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-C-and-OpenCV) [Report(C++)](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-C-and-OpenCV/blob/master/report_openCV_cPlusPlus_GoikrishnaErabati.pdf) [Code(MATLAB)](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-MATLAB) [Report(MATLAB)](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-MATLAB/blob/master/Report_CVToolBox_Matlab_GoikrishnaErabati.pdf)

In this project I aimed at developing CV tools like feature matching, camera calibration etc. not only using OpenCV and C++ but also with MATLAB.

| CV Toolbox GUI in C++ | CV Toolbox GUI in MATLAB |
| --- | --- |
| ![](../assets/img/projects/cvtoolbox1.png) | ![](../assets/img/projects/cvtoolboxmatlab.png) |

[<img src="../assets/img/projects/cvtoolboxss.png" width="500" height="250">](https://www.youtube.com/watch?v=9FG2c6Qe0XM)

**********
### Development of Face Recognition software using PCA

[Code](https://github.com/gopi-erabati/Face-Recognition-Using-PCA) [Report](https://github.com/gopi-erabati/Face-Recognition-Using-PCA/blob/master/report_facerecog_PCA_ERABATI_DOUSAI.pdf)

The main objective of our project is to recognize faces from the collected set of face data using PCA (Principal Component Analysis). We have collected five pictures of every person, and the idea here is to extract a few features from the faces with the goal of reducing the number of variables used to represent the faces. In the next step, we divide the faces into two categories of train and test images. But the problem here is, an image has high dimensionality space (each image is a point in a space of dimension d = MN, M and N being image size) as each pixel is considered as a variable of an image. So, we can reduce the dimensionality by using PCA to simplify recognition problem, which can be considered as the core concept.

<img src="../assets/img/projects/facerecog.png" width="500" height="250">

**********
### 

* Human Activity Recognition in Videos. [[Code](https://github.com/gopi-erabati/Human-Activity-Recognition-from-Videos-Using-Machine-Learning)]
* Mapping, Autonomous Navigation and Localization of Turtlebot using ROS. [[Code](https://github.com/gopi-erabati/Mapping_LocalizationOfARMarkers_Navigation_ROS_Turtlebot)]
* Development of Computer Vision Toolbox in C++ [[Code](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-C-and-OpenCV)] and MATLAB [[Code](https://github.com/gopi-erabati/Development-of-Image-Processing-and-Computer-Vision-Toolbox-using-MATLAB)] using OpenCV.
* Development of 3D Scanner using Kinect and PCL. [[Code](https://github.com/gopi-erabati/3D-Reconstruction-of-Human-using-Kinect-v2-and-PCL)]
* Development of Face Recognition software using PCA. [[Code](https://github.com/gopi-erabati/Face-Recognition-Using-PCA)]
* Classification using SVM. [[Code](https://github.com/gopi-erabati/Classification-of-cats-and-dogs-using-SVM-classifier)]
* Click [here](https://www.linkedin.com/in/gopierabati/details/projects/) for more projects
