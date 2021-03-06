# 3D - Point Cloud

**Paper list** and **Datasets** about Point Cloud. Datasets can be found in [Datasets.md](https://github.com/zhulf0804/3D-PointCloud/blob/master/Datasets.md).

<hr />

## Survey papers

+ [Deep Learning for 3D Point Clouds: A Survey](https://arxiv.org/pdf/1912.12033.pdf) [TPAMI 2020]

## 2020
+ ECCV
	- [DeepGMR: Learning Latent Gaussian Mixture Models for Registration](https://arxiv.org/pdf/2008.09088.pdf) [`registration`; [PyTorch](https://github.com/wentaoyuan/deepgmr)]
	- [Quaternion Equivariant Capsule Networks for 3D Point Clouds](https://arxiv.org/pdf/1912.12098.pdf) [[PyTorch](https://github.com/tolgabirdal/qecnetworks)]
	- [PointContrast: Unsupervised Pre-training for 3D Point Cloud Understanding](https://arxiv.org/pdf/2007.10985.pdf) [`unsupervised`; `cls`, `seg`, `det`]
	- [Convolutional Occupancy Networks](https://arxiv.org/pdf/2003.04618.pdf) [`reconstruction`; [PyTorch](https://github.com/autonomousvision/convolutional_occupancy_networks)]
	- [Iterative Distance-Aware Similarity Matrix Convolution with Mutual-Supervised Point Elimination for Efficient Point Cloud Registration](https://arxiv.org/pdf/1910.10328.pdf) [`registration`; [PyTorch](https://github.com/jiahaowork/idam)]
	- [A Closer Look at Local Aggregation Operators in Point Cloud Analysis](https://arxiv.org/pdf/2007.01294.pdf) [`cls`, `seg`; [Code](https://github.com/zeliu98/CloserLook3D)]
	- [Multimodal Shape Completion via Conditional Generative Adversarial Networks](https://arxiv.org/pdf/2003.07717.pdf) [`completion`; [PyTorch](https://github.com/ChrisWu1997/Multimodal-Shape-Completion)]
	- [GRNet: Gridding Residual Network for Dense Point Cloud Completion](https://arxiv.org/pdf/2006.03761.pdf) [`completion`; [PyTorch](https://github.com/hzxie/GRNet)]
	- [3D-CVF: Generating Joint Camera and LiDAR Features Using Cross-View Spatial Feature Fusion for 3D Object Detection](https://arxiv.org/pdf/2004.12636.pdf) [`det`]
	- [Progressive Point Cloud Deconvolution Generation Network](https://arxiv.org/pdf/2007.05361.pdf) [`generation`; [github](https://github.com/fpthink/PDGN)]
+ CVPR
	- [Deep Global Registration](https://arxiv.org/pdf/2004.11540.pdf) [`registration`; [PyTorch](https://github.com/chrischoy/DeepGlobalRegistration)]
	- [PV-RCNN: Point-Voxel Feature Set Abstraction for 3D Object Detection](https://openaccess.thecvf.com/content_CVPR_2020/papers/Shi_PV-RCNN_Point-Voxel_Feature_Set_Abstraction_for_3D_Object_Detection_CVPR_2020_paper.pdf) [`det`; [code](https://github.com/open-mmlab/OpenPCDet)]
	- [SA-SSD: Structure Aware Single-stage 3D Object Detection from Point Cloud](https://www4.comp.polyu.edu.hk/~cslzhang/paper/SA-SSD.pdf) [`det`; [PtTorch](https://github.com/skyhehe123/SA-SSD)]
	- [3DRegNet: A Deep Neural Network for 3D Point Registration](https://openaccess.thecvf.com/content_CVPR_2020/papers/Pais_3DRegNet_A_Deep_Neural_Network_for_3D_Point_Registration_CVPR_2020_paper.pdf) [`registration`; [Tensorflow](https://github.com/3DVisionISR/3DRegNet)]
	- [MINA: Convex Mixed-Integer Programming for Non-Rigid Shape Alignment](https://openaccess.thecvf.com/content_CVPR_2020/papers/Bernard_MINA_Convex_Mixed-Integer_Programming_for_Non-Rigid_Shape_Alignment_CVPR_2020_paper.pdf) [`non-rigid alignment`]
	- [SampleNet: Differentiable Point Cloud Sampling](https://openaccess.thecvf.com/content_CVPR_2020/papers/Lang_SampleNet_Differentiable_Point_Cloud_Sampling_CVPR_2020_paper.pdf) [`cls`, `registration`, `reconstruction`; [PyTorch](https://github.com/itailang/SampleNet)]
	- [Learning multiview 3D point cloud registration](https://arxiv.org/pdf/2001.05119.pdf) [`multiview registration`; [PyTorch](https://github.com/zgojcic/3D_multiview_reg)]
	- [Feature-metric Registration: A Fast Semi-supervised Approach for Robust Point Cloud Registration without Correspondences](https://arxiv.org/pdf/2005.01014.pdf) [`registration`; [PyTorch](https://github.com/XiaoshuiHuang/fmr)] 
 	- [PointASNL: Robust Point Clouds Processing using Nonlocal Neural Networks with Adaptive Sampling](https://arxiv.org/pdf/2003.00492.pdf) [`cls`, `seg`; [Tensorflow](https://github.com/yanx27/PointASNL)]
	- [Global-Local Bidirectional Reasoning for Unsupervised Representation Learning of 3D Point Clouds](https://arxiv.org/pdf/2003.12971.pdf) [`unsupervised`; `cls`; [PyTorch](https://github.com/raoyongming/PointGLR)]
	- [Grid-GCN for Fast and Scalable Point Cloud Learning](https://arxiv.org/pdf/1912.02984.pdf) [`cls`, `seg`; [mxnet](https://github.com/Xharlie/Grid-GCN)]
	- [FPConv: Learning Local Flattening for Point Convolution](https://arxiv.org/pdf/2002.10701.pdf) [`cls`, `seg`; [PyTorch](https://github.com/lyqun/FPConv)]
	- [PointAugment: an Auto-Augmentation Framework for Point Cloud Classification](https://arxiv.org/pdf/2002.10876.pdf) [`cls`, `retrieval`; [github](https://github.com/liruihui/PointAugment/)]
	- [RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds](https://arxiv.org/pdf/1911.11236.pdf) [`seg`; [Tensorflow](https://github.com/QingyongHu/RandLA-Net)]
	- [Weakly Supervised Semantic Point Cloud Segmentation:Towards 10X Fewer Labels](https://arxiv.org/pdf/2004.04091.pdf) [`weakly supervised`; `seg`; [Tensorflow](https://github.com/alex-xun-xu/WeakSupPointCloudSeg)]
	- [PolarNet: An Improved Grid Representation for Online LiDAR Point Clouds Semantic Segmentation](https://arxiv.org/pdf/2003.14032.pdf) [`seg`; [PyTorch](https://github.com/edwardzhou130/PolarSeg)]
	- [Learning to Segment 3D Point Clouds in 2D Image Space](https://arxiv.org/pdf/2003.05593.pdf) [`seg`; [Keras](https://github.com/Zhang-VISLab/Learning-to-Segment-3D-Point-Clouds-in-2D-Image-Space)]
	- [PointGroup: Dual-Set Point Grouping for 3D Instance Segmentation](https://arxiv.org/pdf/2004.01658.pdf) [`seg`; [PyTorch](https://github.com/Jia-Research-Lab/PointGroup)]
	- [D3Feat: Joint Learning of Dense Detection and Description of 3D Local Features](https://arxiv.org/pdf/2003.03164.pdf) [`registration`; [Tensorflow](https://github.com/XuyangBai/D3Feat)]
	- [RPM-Net: Robust Point Matching using Learned Features](https://arxiv.org/pdf/2003.13479.pdf) [`registration`; [PyTorch](https://github.com/yewzijian/RPMNet)]
	- [Cascaded Refinement Network for Point Cloud Completion](https://arxiv.org/pdf/2004.03327.pdf) [`completion`; [Tensorflow](https://github.com/xiaogangw/cascaded-point-completion)]
	- [P2B: Point-to-Box Network for 3D Object Tracking in Point Clouds](https://arxiv.org/pdf/2005.13888.pdf) [`tracking`; [PyTorch](https://github.com/HaozheQi/P2B)]
	- [An Efficient PointLSTM for Point Clouds Based Gesture Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Min_An_Efficient_PointLSTM_for_Point_Clouds_Based_Gesture_Recognition_CVPR_2020_paper.pdf) [`gesture`; [PyTorch](https://github.com/Blueprintf/pointlstm-gesture-recognition-pytorch)]
+ AAAI
	- [MSN: Morphing and Sampling Network for Dense Point Cloud Completion](https://cseweb.ucsd.edu/~mil070/projects/AAAI2020/paper.pdf) [`completion`; [PyTorch](https://github.com/Colin97/MSN-Point-Cloud-Completion)]
	- [TANet: Robust 3D Object Detection from Point Clouds with Triple Attention](https://arxiv.org/pdf/1912.05163.pdf) [`det`; [PyTorch](https://github.com/happinesslz/TANet)]
	- [Point2Node: Correlation Learning of Dynamic-Node for Point Cloud Feature Modeling](https://arxiv.org/pdf/1912.10775.pdf) [`cls`, `seg`]
	- [Pointwise Rotation-Invariant Network with Adaptive Sampling and 3D Spherical Voxel Convolution](https://arxiv.org/pdf/1811.09361.pdf) [`cls`, `seg`, `matching`]
+ arXiv
	- [Multi-Resolution Graph Neural Network for Large-Scale Pointcloud Segmentation](https://arxiv.org/pdf/2009.08924.pdf) [`seg`]
	- [A Density-Aware PointRCNN for 3D Objection Detection in Point Clouds](https://arxiv.org/pdf/2009.05307.pdf) [`det`]

## 2019

+ NeurIPS
	- [Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds](https://arxiv.org/pdf/1906.01140.pdf) [`seg`; [Tensorflow](https://github.com/Yang7879/3D-BoNet)]	
	- [PRNet: Self-Supervised Learning for Partial-to-Partial Registration](http://papers.nips.cc/paper/9085-prnet-self-supervised-learning-for-partial-to-partial-registration.pdf) [`registration`, `cls`; [PyTorch](https://github.com/WangYueFt/prnet)]
	- [Point-Voxel CNN for Efficient 3D Deep Learning](https://arxiv.org/pdf/1907.03739.pdf) [`seg`, `det`; [PyTorch](https://github.com/mit-han-lab/pvcnn)]
+ ICCV
	- [Fast Point R-CNN](https://arxiv.org/pdf/1908.02990.pdf) [`det`]
	- [Revisiting Point Cloud Classification: A New Benchmark Dataset and Classification Model on Real-World Data](https://openaccess.thecvf.com/content_ICCV_2019/papers/Uy_Revisiting_Point_Cloud_Classification_A_New_Benchmark_Dataset_and_Classification_ICCV_2019_paper.pdf) [`dataset`; `cls`; [Tensorflow](https://github.com/hkust-vgd/scanobjectnn)]
	- [KPConv: Flexible and Deformable Convolution for Point Clouds](https://openaccess.thecvf.com/content_ICCV_2019/papers/Thomas_KPConv_Flexible_and_Deformable_Convolution_for_Point_Clouds_ICCV_2019_paper.pdf) [`cls`, `seg`; [code](https://github.com/HuguesTHOMAS/KPConv)]
	- [Fully Convolutional Geometric Features](https://openaccess.thecvf.com/content_ICCV_2019/papers/Choy_Fully_Convolutional_Geometric_Features_ICCV_2019_paper.pdf) [`match`; [PyTorch](https://github.com/chrischoy/FCGF)]
	- [Deep Closest Point: Learning Representations for Point Cloud Registration](https://arxiv.org/pdf/1905.03304.pdf) [`registration`; [PyTorch](https://github.com/WangYueFt/dcp)]
	- [DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration](https://arxiv.org/pdf/1905.04153.pdf) [`registration`]
	- [Hierarchical Point-Edge Interaction Network for Point Cloud Semantic Segmentation](https://arxiv.org/pdf/1909.10469.pdf) [`seg`]
	- [DensePoint: Learning Densely Contextual Representation for Efficient Point Cloud Processing](https://arxiv.org/pdf/1909.03669.pdf) [`cls`, `retrieval`, `seg`, `normal estimation`; [PyTorch](https://github.com/Yochengliu/DensePoint)]
	- [DUP-Net: Denoiser and Upsampler Network for 3D Adversarial Point Clouds Defense](https://arxiv.org/pdf/1812.11017.pdf) [`cls`]
	- [Efficient Learning on Point Clouds with Basis Point Sets](https://arxiv.org/pdf/1908.09186.pdf) [`cls`, `registration`; [PyTorch](https://github.com/sergeyprokudin/bps)]
	- [PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows](https://arxiv.org/pdf/1906.12320.pdf) [`generation`, `reconstruction`; [Pytorch](https://github.com/stevenygd/PointFlow)
	- [PU-GAN: a Point Cloud Upsampling Adversarial Network](https://arxiv.org/pdf/1907.10844) [`upsampling`, `reconstruction`; [Project](https://liruihui.github.io/publication/PU-GAN/)]
	- [3D Point Cloud Learning for Large-scale Environment Analysis and Place Recognition](https://arxiv.org/pdf/1812.07050.pdf) [`retrieval`, `place recognition`]
	- [Deep Hough Voting for 3D Object Detection in Point Clouds](https://arxiv.org/pdf/1904.09664.pdf) [`det`; [PyTorch](https://github.com/facebookresearch/votenet)]
	- [Exploring the Limitations of Behavior Cloning for Autonomous Driving](https://arxiv.org/pdf/1904.08980.pdf) [`autonomous driving`; [Pytorch](https://github.com/felipecode/coiltraine)]

+ CVPR
	- [Modeling Point Clouds with Self-Attention and Gumbel Subset Sampling](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yang_Modeling_Point_Clouds_With_Self-Attention_and_Gumbel_Subset_Sampling_CVPR_2019_paper.pdf) [`cls`, `seg`, `gesture`]
	- [Learning to Sample](https://arxiv.org/pdf/1812.01659.pdf) [`cls`, `retrieval`, `reconstruction`; [Tensorflow](https://github.com/orendv/learning_to_sample)]
	- [PointConv: Deep Convolutional Networks on 3D Point Clouds](https://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_PointConv_Deep_Convolutional_Networks_on_3D_Point_Clouds_CVPR_2019_paper.pdf) [`cls`, `seg`; [Tensorflow](https://github.com/DylanWusee/pointconv)]
	- [The Perfect Match: 3D Point Cloud Matching With Smoothed Densities](https://openaccess.thecvf.com/content_CVPR_2019/papers/Gojcic_The_Perfect_Match_3D_Point_Cloud_Matching_With_Smoothed_Densities_CVPR_2019_paper.pdf) [`match`; [code](https://github.com/zgojcic/3DSmoothNet)]
	- [PointNetLK: Point Cloud Registration using PointNet](https://arxiv.org/pdf/1903.05711.pdf) [`registration`; [PyTorch](https://github.com/hmgoforth/PointNetLK)]
	- [PointRCNN: 3D Object Proposal Generation and Detection From Point Cloud](http://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_PointRCNN_3D_Object_Proposal_Generation_and_Detection_From_Point_Cloud_CVPR_2019_paper.pdf) [`det`; [PyTorch](https://github.com/sshaoshuai/PointRCNN)]		
	- [PointPillars: Fast Encoders for Object Detection From Point Clouds](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lang_PointPillars_Fast_Encoders_for_Object_Detection_From_Point_Clouds_CVPR_2019_paper.pdf) [`det`; [Pytorch](https://github.com/nutonomy/second.pytorch)]
	- [Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving](https://arxiv.org/pdf/1812.07179.pdf) [`depth estimation`, `det`; [github](https://github.com/mileyan/pseudo_lidar)]
	- [ApolloCar3D: A Large 3D Car Instance Understanding Benchmark for Autonomous Driving](https://arxiv.org/pdf/1811.12222.pdf) [`dataset`, `autonomous driving`]
	- [Stereo R-CNN based 3D Object Detection for Autonomous Driving](https://arxiv.org/pdf/1902.09738.pdf) [`det`, `autonomous driving`; [github](https://github.com/HKUST-Aerial-Robotics/Stereo-RCNN)]
	- [Monocular 3D Object Detection Leveraging Accurate Proposals and Shape Reconstruction](https://arxiv.org/pdf/1904.01690.pdf) [`det`, `autonomous driving`; [Tesorflow](https://github.com/kujason/monopsr)]
	- [LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving](https://arxiv.org/pdf/1903.08701.pdf) [`det`]
	- [GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving](https://arxiv.org/pdf/1903.10955.pdf) [`det`, `autonomous driving`]
	- [L3-Net: Towards Learning based LiDAR Localization for Autonomous Driving](https://songshiyu01.github.io/pdf/L3Net_W.Lu_Y.Zhou_S.Song_CVPR2019.pdf) [`autonomous driving`]
+ arXiv
	- [Adversarial Sensor Attack on LiDAR-based Perception in Autonomous Driving](https://arxiv.org/pdf/1907.06826.pdf) [`autonomous driving`]

## 2018
+ CVPR
	- [PIXOR: Real-Time 3D Object Detection From Point Clouds](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf) [`det`; [PyTorch](https://github.com/philip-huang/PIXOR)]
	- [Frustum PointNets for 3D Object Detection From RGB-D Data](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf) [`det`; [Tensorflow](https://github.com/charlesq34/frustum-pointnets)]		
	- [VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_VoxelNet_End-to-End_Learning_CVPR_2018_paper.pdf) [`det`]
	- [3D-RCNN: Instance-Level 3D Object Reconstruction via Render-and-Compare](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.pdf) [`reconstruction`]
	- [Multi-Level Fusion Based 3D Object Detection From Monocular Images](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_Multi-Level_Fusion_Based_CVPR_2018_paper.pdf) [`det`]		
+ ECCV
	- [Deep Continuous Fusion for Multi-Sensor 3D Object Detection](http://openaccess.thecvf.com/content_ECCV_2018/papers/Ming_Liang_Deep_Continuous_Fusion_ECCV_2018_paper.pdf) [`det`]
	- [3DFeat-Net: Weakly Supervised Local 3D
Features for Point Cloud Registration](https://openaccess.thecvf.com/content_ECCV_2018/papers/Zi_Jian_Yew_3DFeat-Net_Weakly_Supervised_ECCV_2018_paper.pdf) [`match`, `registration`; [Tensorflow](https://github.com/yewzijian/3DFeatNet)]
	- [Stereo Vision-based Semantic 3D Object and Ego-motion Tracking for Autonomous Driving](http://openaccess.thecvf.com/content_ECCV_2018/papers/Peiliang_LI_Stereo_Vision-based_Semantic_ECCV_2018_paper.pdf) [`autonomous driving`]
+ Others
	- [Second: Sparsely embedded convolutional detection](https://www.mdpi.com/1424-8220/18/10/3337/pdf) [`det`; `Sensors`]	
	- [Rt3d: Real-time 3-d vehicle detection in lidar point cloud for autonomous driving](https://ieeexplore.ieee.org/abstract/document/#) [`det`, `autonomous driving`; IEEE Robotics and Automation Letters]
	- [HDNET: Exploiting HD Maps for 3D Object Detection](http://proceedings.mlr.press/v87/yang18b/yang18b.pdf) [`det`, `autonomous driving`; CoRL]
	- [Joint 3D Proposal Generation and Object Detection from View Aggregation](https://arxiv.org/pdf/1712.02294.pdf) [`det`, `autonomous driving`; IROS]
	- [Flex-Convolution(Million-Scale Point-Cloud Learning Beyond Grid-Worlds)](https://arxiv.org/pdf/1803.07289.pdf) [`cls`, `seg`; ACCV; [Tensorflow](https://github.com/cgtuebingen/Flex-Convolution)]
+ arXiv
	- [Point Convolutional Neural Networks by Extension Operators](https://arxiv.org/pdf/1803.10091.pdf) [`cls`, `seg`, `normal estimation`; [Tensorflow](https://github.com/matanatz/pcnn)]
	- [PointSIFT: A SIFT-like Network Module for 3D Point Cloud Semantic Segmentation](https://arxiv.org/pdf/1807.00652.pdf) [`seg`; [Tensorflow](https://github.com/MVIG-SJTU/pointSIFT)]
	- [Roarnet: A robust 3d object detection based on region approximation refinement](https://arxiv.org/pdf/1811.03818.pdf) [`det`]
	- [Complex-YOLO: Real-time 3D Object Detection on Point Clouds](https://arxiv.org/pdf/1803.06199) [`det`; [PyTorch](https://github.com/AI-liu/Complex-YOLO)]

## 2017
+ CVPR
	- [Multi-View 3D Object Detection Network for Autonomous Driving](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chen_Multi-View_3D_Object_CVPR_2017_paper.pdf) [`det`, `autonomous driving`; [Tensorflow](https://github.com/bostondiditeam/MV3D)]
	- [Deep MANTA: A Coarse-To-Fine Many-Task Network for Joint 2D and 3D Vehicle Analysis From Monocular Image](http://openaccess.thecvf.com/content_cvpr_2017/papers/Chabot_Deep_MANTA_A_CVPR_2017_paper.pdf) [`autonomous driving`]
	- **[PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](http://openaccess.thecvf.com/content_cvpr_2017/papers/Qi_PointNet_Deep_Learning_CVPR_2017_paper.pdf)** [`cls`, `seg`; [Tensorflow](https://github.com/charlesq34/pointnet)]
	- [3D Bounding Box Estimation Using Deep Learning and Geometry](http://openaccess.thecvf.com/content_cvpr_2017/papers/Mousavian_3D_Bounding_Box_CVPR_2017_paper.pdf) [`det`]
	- [OctNet: Learning Deep 3D Representations at High Resolutions](http://openaccess.thecvf.com/content_cvpr_2017/papers/Riegler_OctNet_Learning_Deep_CVPR_2017_paper.pdf) [`cls`, `seg`, `orientation estimation`; [PyTorch](https://github.com/griegler/octnet)]
	- [3DMatch: Learning Local Geometric Descriptors from RGB-D Reconstructions](https://openaccess.thecvf.com/content_cvpr_2017/papers/Zeng_3DMatch_Learning_Local_CVPR_2017_paper.pdf) [`match`, `registration`; [project](http://3dmatch.cs.princeton.edu/)]
	- [3D Point Cloud Registration for Localization using a Deep Neural Network Auto-Encoder](https://openaccess.thecvf.com/content_cvpr_2017/papers/Elbaz_3D_Point_Cloud_CVPR_2017_paper.pdf) [`registration`; [github](https://github.com/gilbaz/LORAX)]
+ ICCV
	- [2D-Driven 3D Object Detection in RGB-D Images](http://openaccess.thecvf.com/content_ICCV_2017/papers/Lahoud_2D-Driven_3D_Object_ICCV_2017_paper.pdf) [`det`]
+ TPAMI
	- [3D Object Proposals Using Stereo Imagery for Accurate Object Class Detection](https://arxiv.org/pdf/1608.07711.pdf) [`det`, `autonomous driving`]
+ NIPS
	- **[Pointnet++: Deep hierarchical feature learning on point sets in a metric space](http://papers.nips.cc/paper/7095-pointnet-deep-hierarchical-feature-learning-on-point-sets-in-a-metric-space.pdf)** [`cls`, `seg`; [Tensorflow](https://github.com/charlesq34/pointnet2)]
+ Others
	- [Vote3deep: Fast object detection in 3d point clouds using efficient convolutional neural networks](https://arxiv.org/pdf/1609.06666.pdf) [`det`; ICRA]
	- [3d fully convolutional network for vehicle detection in point cloud](https://arxiv.org/pdf/1611.08069.pdf) [`det`; IROS; [Tensorflow](https://github.com/yukitsuji/3D_CNN_tensorflow)]

## Before 2016 
+ 2016
	- [Fast Global Registration](https://www.researchgate.net/profile/Vladlen_Koltun/publication/305983982_Fast_Global_Registration/links/57a8086908aefe6167bc8366/Fast-Global-Registration.pdf) [`registration`; ECCV; [Github](https://github.com/intel-isl/FastGlobalRegistration)]
	- [Monocular 3D Object Detection for Autonomous Driving](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Chen_Monocular_3D_Object_CVPR_2016_paper.pdf) [CVPR]
	- [Volumetric and Multi-View CNNs for Object Classification on 3D Data](http://openaccess.thecvf.com/content_cvpr_2016/papers/Qi_Volumetric_and_Multi-View_CVPR_2016_paper.pdf) [CVPR]
	- [Three-Dimensional Object Detection and Layout Prediction Using Clouds of Oriented Gradients](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ren_Three-Dimensional_Object_Detection_CVPR_2016_paper.pdf) [CVPR]
	- [Deep Sliding Shapes for Amodal 3D Object Detection in RGB-D Images](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Song_Deep_Sliding_Shapes_CVPR_2016_paper.pdf) [CVPR]				
	- [Fpnn: Field probing neural networks for 3d data](http://papers.nips.cc/paper/6416-fpnn-field-probing-neural-networks-for-3d-data.pdf) [NIPS]
	- [Vehicle Detection from 3D Lidar Using Fully Convolutional Network](https://arxiv.org/pdf/1608.07916) [RSS]
+ 2015
	- [Go-ICP: A Globally Optimal Solution to 3D ICP Point-Set Registration](https://arxiv.org/pdf/1605.03344.pdf) [`registration`; TPAMI; [Github](https://github.com/yangjiaolong/Go-ICP)] 
	- [3D ShapeNets: A Deep Representation for Volumetric Shapes](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wu_3D_ShapeNets_A_2015_CVPR_paper.pdf) [CVPR]
	- [SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Song_SUN_RGB-D_A_2015_CVPR_paper.pdf) [CVPR]
	- [Data-Driven 3D Voxel Patterns for Object Category Recognition](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiang_Data-Driven_3D_Voxel_2015_CVPR_paper.pdf) [CVPR]
	- [Multi-view convolutional neural networks for 3d shape recognition](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Su_Multi-View_Convolutional_Neural_ICCV_2015_paper.pdf) [ICCV]
	- [3d object proposals for accurate object class detection](http://papers.nips.cc/paper/5644-3d-object-proposals-for-accurate-object-class-detection.pdf) [NIPS]
	- [Voting for Voting in Online Point Cloud Object](https://pdfs.semanticscholar.org/521f/688f1fadaaff81269040f13270e8ec1a14d4.pdf) [RSS]
	- [Voxnet: A 3d convolutional neural network for real-time object recognition](https://www.ri.cmu.edu/pub_files/2015/9/voxnet_maturana_scherer_iros15.pdf) [IROS]
+ 2014
	- [Are Cars Just 3D Boxes? - Jointly Estimating the 3D Shape of Multiple Objects](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Zia_Are_Cars_Just_2014_CVPR_paper.pdf) [CVPR]
	- [Sliding shapes for 3d object detection in depth images](https://pdfs.semanticscholar.org/832e/eaede4f697f005b007798fe0d04829f656b7.pdf) [ECCV]

- 2012
	- [Are we ready for autonomous driving? the kitti vision benchmark suite](http://www.webmail.cvlibs.net/publications/Geiger2012CVPR.pdf) [CVPR]
- 1992
	- [A method for registration of 3-D shapes ](https://www.researchgate.net/publication/3191994_A_method_for_registration_of_3-D_shapes_IEEE_Trans_Pattern_Anal_Mach_Intell) [`registration`; TPAMI]
- 1987
	- [Least-squares fitting of two 3-D point sets](https://www.researchgate.net/publication/224378053_Least-squares_fitting_of_two_3-D_point_sets_IEEE_T_Pattern_Anal) [`registration`; TPAMI]

## Reference
+ [https://github.com/amusi/ECCV2020-Code](https://github.com/amusi/ECCV2020-Code)
+ [https://github.com/amusi/CVPR2020-Code](https://github.com/amusi/CVPR2020-Code)
+ [https://github.com/extreme-assistant/CVPR2020-Paper-Code-Interpretation](https://github.com/extreme-assistant/CVPR2020-Paper-Code-Interpretation)
+ [https://github.com/Yochengliu/awesome-point-cloud-analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis)
+ [http://bbs.cvmart.net/topics/302/cvpr2019paper](http://bbs.cvmart.net/topics/302/cvpr2019paper)
+ [https://github.com/extreme-assistant/iccv2019](https://github.com/extreme-assistant/iccv2019)
+ [https://github.com/amusi/daily-paper-computer-vision](https://github.com/amusi/daily-paper-computer-vision)
+ [http://openaccess.thecvf.com/menu.py](http://openaccess.thecvf.com/menu.py)