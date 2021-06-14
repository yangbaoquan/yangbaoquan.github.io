---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My current research is about visual perception, long-term localization, and robust machine learning algorithms.

My research goal is to develop robust algorithms in a long-term perspective for complex multi-agent system. My past works focus on reliable perception and localization algorithms under changing environments, e.g. illumination, seasonal and weather changes. The involved tasks are place recognition, depth prediction, semantic segmentation, etc. Recently, I am working on multi-agent decision making algorithm for collaborative robust perception. 

<!-- My research consists of visual perception, long-term localization, and multi-agent control.

My research goal is to develop intelligent and robust algorithms for the sake of long-term, large-scale and multi-agent challenges. For outdoor autonomous vehicles, I seek for reliable perception and localization algorithms under changing environments in a long-term perspective. From the spatial view, I also engage in the precise control of multiple agents for a stable autonomous system.    -->


## Visual Perception and Localization

* **Cross-Season Monocular Depth Prediction under Changing Environments** <br> [[paper](https://arxiv.org/abs/2011.04408)] [[project](https://seasondepth.github.io/)]  <br >
<img src='../images/img_samples.png' style="float:center" width=500 alt="Text alternative when image is not available"> <br>
<!-- <img src='../images/img2.png' align="center" width=666 alt="Text alternative when image is not available"> -->
A new cross-season scaleless monocular depth prediction dataset is derived from CMU Visual Localization dataset through structure from motion. And then the several metrics are formulated to measure the performance on this dataset. Besides, we have benchmarked almost all the open-source state-of-the-art algorithms on KITTI dataset using the new dataset to find robust methods against the challenging environments. The dataset and benchmark is available on [SeasonDepth](https://seasondepth.github.io/).

* **Generative Vehicle Segmentation for Aerial-view Images** <br>
<img src='../images/UCB_video_speed_GIF.gif' style="float:middle" width=500 alt="Text alternative when image is not available"> <br> 
To improve the performance of vehicle detection and segmentation in aerial-view images, we propose a novel algorithm based on the generative model. Inspired by multi-modal image translation, the vehicle patches could be regarded as the combination of vehicle content and multi-modal surrounding style distribution. Consequently, the process of vehicle segmentation is a content extraction and multi-to-single-modal image translation, which is suitable for domain adaptation. Based on this work, a GUI tool has been developed to help to obtain the ground truth for the [INTERPRET NeurIPS 2020 Challenge](http://challenge.interaction-dataset.com/prediction-challenge/intro) by MSC Lab at UC Berkeley.

* **Domain Adaptation for Semantic and Geometric-aware Localization** <br> [[paper](https://ieeexplore.ieee.org/document/9296559)] [[code](https://github.com/HanjiangHu/DASGIL)] <br >
<img src='../images/img2.png' style="float:center" width=500 alt="Text alternative when image is not available"> <br>
A novel multi-task architecture is proposed to fuse the geometric and semantic information into the multi-scale latent embedding representation for long-term visual localization. Also, domain adaptation is adopted from synthetic to real-world datasets to use the high-quality virtual ground truths without any human effort. The proposed method outperforms state-of-the-art baselines for retrieval-based localization under the challenging environment on the Extended CMU-Seasons dataset from the [visual localization benchmark](https://www.visuallocalization.net/benchmark/).

* **Domain-invariant Activation Feature Learning for Long-term Localization** <br> [[Conference Paper](https://ieeexplore.ieee.org/document/8968047)] [[code](https://github.com/HanjiangHu/DIFL-FCL)], [[Journal Paper](https://ieeexplore.ieee.org/document/9358457)] [[code](https://github.com/HanjiangHu/DISAM)] <br>
<img src='../images/overview.png'  width="500px" alt="Text alternative when image is not available"> <br>
<!-- <img src='../images/SAM.png'  width="300px" alt="Text alternative when image is not available"> -->
A self-supervised representation learning is proposed to extract domain-invariant features through multi-domain image translation by introducing feature consistency loss. Besides, a novel gradient-weighted similarity activation mapping loss (Grad-SAM) is incorporated for high-precision localization. In medium or high precision localization, our performance outperforms state-of-the-art image-based localization
baselines under the challenging environments with illumination variance, vegetation
and night-time images on CMU-Seasons and RobotCar-Seasons dataset from the [visual localization benchmark](https://www.visuallocalization.net/benchmark/).


<!-- ## Multi-agent System

* **Distributed Rendezvous Control of Networked Uncertain Robotic Systems with Bearing Measurements** <br> [[available soon]()] <br>


* **Cooperative Adaptive Cruise Control Based Non-Stop Intersection Passing** <br> [[paper](https://ieeexplore.ieee.org/abstract/document/9196991/)]<br>
In this papeI help to conduct ther, we resolve the CACC problem from the viewpoint ofI help to conduct the synchronization control, our main idea is to introdI help to conduct theuce the spatial-temporal synchronizatI help to conduct theion mechanism into vehicle platoon control to aI help to conduct thechieve the robust CACC and to further realize the I help to conduct thenon-stop intersection control. Firstly, by introduciI help to conduct theng the cross-coupling based space
synchronization mechanism, a distributed control algorithm is presented to achieve the single-lane CACC in the presence of vehicle-to-vehicle (V2V) communications, which enables autonomous vehicles to track the desired platoon trajectory while synchronizing their longitudinal velocities to keeping the expected inter-vehicle distance. Secondly, by designing the enter-time scheduling mechanism (temporal synchronization), a high-level intersection control strategy is proposed to command vehicles to form a virtual platoon to pass through the intersection without stopping. Thirdly, a Lyapunov-based timedomain stability analysis approach is presented. Compared with the traditional string stability based approach, the proposed approach guarantees the global asymptotical convergence of the proposed CACC system. Experiments in the small-scale simulated system demonstrate the effectiveness of the proposed
approach. -->

<!-- ## Selected Undergraduate Project
* **Vision-based Intelligent Robotic Grasping System** <br> [[code](https://github.com/HanjiangHu/RGBD-eye-in-hand-robotics-grasping)] [[video](https://youtu.be/8ylxOqa1HiY)] <br>
<img src='../images/toy.gif' style="float:middle" width=500 alt="Text alternative when image is not available"> <br>
The project aims to develop an intelligent and autonomous grasping system based on ROS for UR-5 Robot using an eye-in-hand RGBD camera. From the voice input (Mandarin), YOLO-based object detection and SegmenterLight-based segmentation are implemented to find the target point cloud. The 6-DoF pose of the object with respect to the camera is then estimated based on template matching through FPFH-based RANSAC and ICP algorithm. The project was awarded Third Prize of of ORBBEC 3-D Sensor Application Design Competition in 2018 International Conference on Optical and Photonic Engineering ([ICOPEN 2018](http://jsem.jp/jsem-bbs/img/375.pdf)). -->

<!-- * **Automobile Transmission Solenoid Valve Detection Device** <br> [[patent](https://worldwide.espacenet.com/patent/search/family/056043507/publication/CN105628368A?q=CN105628368A)] <br> -->



