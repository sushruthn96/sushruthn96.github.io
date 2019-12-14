---
layout: default
---
### [Google Scholar](https://scholar.google.com/citations?hl=en&user=ebfkOBIAAAAJ)
## Publications

### RGB-X Object Detection via Scene-Specific Fusion Modules. [[paper]](https://ui.adsabs.harvard.edu/abs/2023arXiv231019372A/abstract) <span style="font-size:smaller;">(***2024 IEEE/CVF Winter Conference on Applications of Computer Vision. WACV 2024***)</span>
This paper proposes an efficient and modular network for multimodal object detection using pre trained single modal models along with scene specific fusion modules. Training this joint network only requires a small co-registered multimodal dataset compared to other methods which need a larger dataset. The paper demonstrates the superiority of this approach by achieving state of the art results on RGB-thermal and RGT-gated datasets.

### Unveiling the ambiguity in neural inverse rendering: A parameter compensation analysis. [[paper]](https://openaccess.thecvf.com/content/CVPR2024W/NRI/papers/Kouros_Unveiling_the_Ambiguity_in_Neural_Inverse_Rendering_A_Parameter_Compensation_CVPRW_2024_paper.pdf) <span style="font-size:smaller;">(***IEEE/CVF Conference on Computer Vision and Pattern Recognition. CVPR workshop 2024***)</span>
Inverse rendering using only multi view camera imgages to reconstruct the 3D scene is ill posed due to ambiguous estimations deviating from physically accurate representations. This paper proposes a evaluation framework to assess the degree of compensation or interaction between the estimated scene properties aiming to explore the mechanisms behind this ill-posed problem and potential mitigation strategies.

### DatasetEquity: Are All Samples Created Equal? In The Quest For Equity Within Datasets. [[paper]](https://openaccess.thecvf.com/content/ICCV2023W/OODCV/papers/Shrivastava_DatasetEquity_Are_All_Samples_Created_Equal_In_The_Quest_For_ICCVW_2023_paper.pdf) <span style="font-size:smaller;">(***ICCV 2023 Workshop - Out Of Distribution Generalization in Computer Vision***)</span>

This paper presents a novel method for addressing data imbalance in machine learning. This paper calculates sample likelihood based on image appaearance using learnt embeddings and latent space clustering. These likelihoods are then used to calculate a generalized focal loss which in turn is used as a complementary loss function during training. This resulted in state of the art results for under represented classes (over 200% gain in some cases) across different datasets which demonstrates the generalizability and complementarity of the proposed method.

### Ref-DVGO: Reflection-Aware Direct Voxel Grid Optimization for an Improved Quality-Efficiency Trade-Off in Reflective Scene Reconstruction. [[paper]](https://arxiv.org/pdf/2308.08530) <span style="font-size:smaller;">(***Oral presentation at ICCV 2023 workshop - Transparent & Reflective objects In the wild Challenges***)</span>

This paper presents a novel approach to strike a balance between efficiency and quality while modeling and rendering reflective objects. The paper adopts an efficient density-based grid representation and reparameterizes the reflected radiance. The paper converts a fully implicit reflection-aware neural rendering model into a hybrid implicit-explicit representation. The proposed method achieves competitive efficiency-quality tradeoff results compared to other baseline approaches on different datasets.

### Look both ways: Bidirectional visual sensing for automatic multi-camera registration. [[paper]](https://arxiv.org/pdf/2208.07362.pdf) [[video]](https://youtu.be/R3raY0YA1-E) <span style="font-size:smaller;">(***IROS 2023***)</span>
 
A novel approach to large scale multi-environment camera registration using visual sensing. A fisheye camera mounted on a calibration robot is used to perform visual odometry (VO). The calibration robot is also equipped with an ArUco marker which is used to determine the scale of VO. The local ArUco marker pose determined by the environment camera is used to optimize for it's global pose. The global positions of the estimated environment camera poses is refined further by minimizing the reprojection error between the projection of the estimated environment camera position and the corresponding pixel detection on the fisheye camera image. 

### Category-Level Pose Retrieval with Contrastive Features Learnt with Occlusion Augmentation. [[paper]](https://arxiv.org/pdf/2208.06195.pdf) <span style="font-size:smaller;">(***BMVC 2022***)</span> 
Category-level pose estimation by learning an alignment metric in an embedding space using a contrastive loss with a dynamic margin and a continuous pose-label space. For efficient inference, a simple real-time image retrieval scheme with a pre-rendered and pre-embedded reference set of renderings is used. To achieve robustness to real-world conditions, synthetic occlusions, bounding box perturbations, and appearance augmentations are used. Our approach achieves state-of-theart performance on PASCAL3D and OccludedPASCAL3D and surpasses the competing methods on KITTI3D in a cross-dataset evaluation setting.


### Domain Adaptation for Object Detection using SE Adaptors and Center Loss. [[paper]](https://arxiv.org/pdf/2205.12923.pdf) [[code]](https://github.com/shreyasrajesh/DA-Object-Detection)
An unsupervised domain adaptation method built on the foundations of faster-RCNN with two domain adaptation components addressing the shift at the instance and image levels respectively and applying a consistency regularization between them. We also introduce a family of adaptation layers that leverage the squeeze excitation mechanism called SE Adaptors to improve domain attention and thus improves performance without any prior requirement of knowledge of the new target domain. Finally, we incorporate a center loss in the instance and image level representations to improve the intra-class variance.


### Structure Aware and Class Balanced 3D Object Detection on nuScenes Dataset. [[paper]](https://arxiv.org/pdf/2205.12519.pdf) [[code]](https://github.com/sushruthn96/Det3D)

We propose to enhance the performance of the 3D LiDAR object detection models by designing an auxiliary network, that makes full use of the structure information of the 3D point cloud, in order to improve the localization accuracy. The detachable auxiliary network is jointly optimized by two point-level supervisions, namely foreground segmentation and center estimation. The auxiliary network does not introduce any extra computation during inference, since it can be detached at test time.
