---
layout: default
---

## Publications
### Look both ways: Bidirectional visual sensing for automatic multi-camera registration. [[paper]](https://arxiv.org/pdf/2208.07362.pdf) [[video]](https://youtu.be/R3raY0YA1-E) <span style="font-size:smaller;">(***Submitted to ICRA 2023***)</span>
 
A novel approach to large scale multi-environment camera registration using visual sensing. A fisheye camera mounted on a calibration robot is used to perform visual odometry (VO). The calibration robot is also equipped with an ArUco marker which is used to determine the scale of VO. The local ArUco marker pose determined by the environment camera is used to optimize for it's global pose. The global positions of the estimated environment camera poses is refined further by minimizing the reprojection error between the projection of the estimated environment camera position and the corresponding pixel detection on the fisheye camera image. 

### Category-Level Pose Retrieval with Contrastive Features Learnt with Occlusion Augmentation. [[paper]](https://arxiv.org/pdf/2208.06195.pdf) <span style="font-size:smaller;">(***BMVC 2022***)</span> 
Category-level pose estimation by learning an alignment metric in an embedding space using a contrastive loss with a dynamic margin and a continuous pose-label space. For efficient inference, a simple real-time image retrieval scheme with a pre-rendered and pre-embedded reference set of renderings is used. To achieve robustness to real-world conditions, synthetic occlusions, bounding box perturbations, and appearance augmentations are used. Our approach achieves state-of-theart performance on PASCAL3D and OccludedPASCAL3D and surpasses the competing methods on KITTI3D in a cross-dataset evaluation setting.


### Domain Adaptation for Object Detection using SE Adaptors and Center Loss. [[paper]](https://arxiv.org/pdf/2205.12923.pdf) [[code]](https://github.com/shreyasrajesh/DA-Object-Detection)
An unsupervised domain adaptation method built on the foundations of faster-RCNN with two domain adaptation components addressing the shift at the instance and image levels respectively and applying a consistency regularization between them. We also introduce a family of adaptation layers that leverage the squeeze excitation mechanism called SE Adaptors to improve domain attention and thus improves performance without any prior requirement of knowledge of the new target domain. Finally, we incorporate a center loss in the instance and image level representations to improve the intra-class variance.


### Structure Aware and Class Balanced 3D Object Detection on nuScenes Dataset. [[paper]](https://arxiv.org/pdf/2205.12519.pdf) [[code]](https://github.com/sushruthn96/Det3D)

We propose to enhance the performance of the 3D LiDAR object detection models by designing an auxiliary network, that makes full use of the structure information of the 3D point cloud, in order to improve the localization accuracy. The detachable auxiliary network is jointly optimized by two point-level supervisions, namely foreground segmentation and center estimation. The auxiliary network does not introduce any extra computation during inference, since it can be detached at test time.