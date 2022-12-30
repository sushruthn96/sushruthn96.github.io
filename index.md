---
layout: default
---

<p align="center">
<img src="profile_pic.png" title="profile_pic" width="300" height="350"/>
</p>

## Publications
### Look both ways: Bidirectional visual sensing for automatic multi-camera registration. [[paper]](https://arxiv.org/pdf/2208.07362.pdf) [[video]](https://youtu.be/R3raY0YA1-E) <span style="font-size:smaller;">(***Submitted to ICRA 2023***)</span>
 
A novel approach to large scale multi-environment camera registration using visual sensing. A fisheye camera mounted on a calibration robot is used to perform visual odometry (VO). The calibration robot is also equipped with an ArUco marker which is used to determine the scale of VO. The local ArUco marker pose determined by the environment camera is used to optimize for it's global pose. The global positions of the estimated environment camera poses is refined further by minimizing the reprojection error between the projection of the estimated environment camera position and the corresponding pixel detection on the fisheye camera image. 

### Category-Level Pose Retrieval with Contrastive Features Learnt with Occlusion Augmentation. [[paper]](https://arxiv.org/pdf/2208.06195.pdf) <span style="font-size:smaller;">(***BMVC 2022***)</span> 
Category-level pose estimation by learning an alignment metric in an embedding space using a contrastive loss with a dynamic margin and a continuous pose-label space. For efficient inference, a simple real-time image retrieval scheme with a pre-rendered and pre-embedded reference set of renderings is used. To achieve robustness to real-world conditions, synthetic occlusions, bounding box perturbations, and appearance augmentations are used. Our approach achieves state-of-theart performance on PASCAL3D and OccludedPASCAL3D and surpasses the competing methods on KITTI3D in a cross-dataset evaluation setting.


### Domain Adaptation for Object Detection using SE Adaptors and Center Loss. [[paper]](https://arxiv.org/pdf/2205.12923.pdf) [[code]](https://github.com/shreyasrajesh/DA-Object-Detection)
An unsupervised domain adaptation method built on the foundations of faster-RCNN with two domain adaptation components addressing the shift at the instance and image levels respectively and applying a consistency regularization between them. We also introduce a family of adaptation layers that leverage the squeeze excitation mechanism called SE Adaptors to improve domain attention and thus improves performance without any prior requirement of knowledge of the new target domain. Finally, we incorporate a center loss in the instance and image level representations to improve the intra-class variance.


### Structure Aware and Class Balanced 3D Object Detection on nuScenes Dataset. [[paper]](https://arxiv.org/pdf/2205.12519.pdf) [[code]](https://github.com/sushruthn96/Det3D)

We propose to enhance the performance of the 3D LiDAR object detection models by designing an auxiliary network, that makes full use of the structure information of the 3D point cloud, in order to improve the localization accuracy. The detachable auxiliary network is jointly optimized by two point-level supervisions, namely foreground segmentation and center estimation. The auxiliary network does not introduce any extra computation during inference, since it can be detached at test time.

## Patents
### Multi camera end-to-end vehicle pose estimation using non-linear optimization <span style="font-size:smaller;">(***Filed, Appl No: 17/745920***)</span>

Realtime automated generation of 3D bounding boxes/poses for vehicles using 2d keypoints seen across multiple cameras at a given timestamp. Non-linear optimization using a CAD model of the vehicle to determine predefined keypoints in 3d space.
### Extrinsic Calibration of distributed cameras using Monocular Visual Odometry <span style="font-size:smaller;"> (***Filed, Appl No: 17/815252***) </span>

[Details](#look-both-ways-bidirectional-visual-sensing-for-automatic-multi-camera-registration-paper-video-submitted-to-icra-2023)

## Academic projects
### To be updated. Currenly listing projects till 2019.

### Image Captioning using Neural Networks
Developed a Deep learning model to generate textual description of given image. Used Resnet-152 based CNN model (Encoder) to extract features from training images. These features were feeded into an LSTM network (Decoder) to sequentially generate captions of images. This project was based on "Show and tell" model.

Various experiments for improving the model efficiency based on optimizers, GloVe word embeddings, LSTM hidden layer feature size , types of Decoder models (RNN, GRU, LSTM) were carried out. [Link_to_project](https://github.com/sushruthn96/Image_Captioning_ML_IP)

### Automated energy meter reading using machine learning and image processing.
Devised a system which automatically detected the readings of different energy meters. Energy meters like needle based meters and digital meters which had number displays were considered.

To classify meters based on needles and digital displays , a CNN based model  using a custom dataset was developed. Then, for needle-based meters, image preprocessing techniques like edge detection algorithms, Hough line transforms and some trigonometric functions were used to find the readings. On the other hand, Chars74k dataset was used to train a CNN based classifier which in turn was used to detect the numbers in digital display.

Also a GUI interface in Python using Tkinter library for displaying real-time detection of energy meter readings was developed. This project comes a long way in helping to automate the readings of energy meters which cannot be taken out in time critical applications. [Link_to_project](https://github.com/sushruthn96/AMR-with-CV)

### Traffic guidance system using Computer Vision
The project aims to automatically turn off the vehicle when the traffic signal becomes red and turn it on when the signal shows green. Further the system varies the speed of the vehicle based on the traffic signs which indicate speed limit. Raspberry Pi was used on a 4 wheeled bot to simulate the system.

To start and stop the vehicle concepts such as CLAHE, Hough circle transform and HSV color transforms were used. Google Vision API was used to detect the traffic speed limit and the subsequent speed control was achieved through the Raspberry Pi interface to the 4 wheeled bot. [Link_to_project](https://github.com/sushruthn96/Automated_Traffic_Guidance_System)

###  PID controller for Pluto drone
Participated in a national level robotics competition named "E-yantra" conducted by IIT Bombay, India. We were given the challenge to make a quadcopter follow a land based bot and navigate smoothly to its destination. ROS was used to communicate with the quadcopter from our workstation. PID control algorithms (for stabilizing and flying the quadcopter) were developed in python.

### Biomedical feedback using Wireless sensor nodes
As part of Texas Instruments India Innovation Challenge Design Contest where around 2000 different ideas were submitted by students cutting across different colleges , we developed a wearable module based on CC3200 microcontroller which measures real-time health parameters like heart rate, temperature and blood oxygen levels of a patient which can then be sent to the doctor’s smartphone using Wireless Sensor Node (WSN) technology via a centralized database. In addition, an alert message in case of abnormal health parameters is sent to the doctor’s smartphone. This way, remote monitoring of patients can be enabled and the archaic file system can be completely made obsolete. Our prototype module made the cut into the top 30 startup ideas to be incubated by Indian Institute of Management Bangalore (IIMB) and an initial monetary funding to the tune of 3 Lakh rupees was provided by Texas Instruments for fabricating the wearable module. [Link_to_project_video](https://youtu.be/V2Wcln0M9FM)

### Grab the garb
As part of a 24 hour hacakthon conducted by Tricon Infotech, India, we developed an android app which helps in garbage collection management. It makes the garbage collection system more transparent between the residents and the muncipal authority. [Link_to_project](https://github.com/sushruthn96/grab_the-garb)

