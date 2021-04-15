# awesome-occlusion-detection
A survey of occlusion handling in object detection/recognition

## Survey
- 遮挡目标检测与识别技术研究_蔡星艳
- Occlusion Detection and Handling: A Review
- Occlusion Handling in Generic Object Detection: A Review
- Survey of pedestrian detection with occlusion
  
### Pedestrian Detection
- [ICCV2015] [Deep learning strong parts for pedestrian detection](https://openaccess.thecvf.com/content_iccv_2015/html/Tian_Deep_Learning_Strong_ICCV_2015_paper.html)
- [ECCV2018] [Occlusion-aware R-CNN: detecting pedestrians in a crowd](https://arxiv.org/abs/1807.08407)
- [CVPR2018] [Repulsion Loss: Detecting Pedestrians in a Crowd](https://arxiv.org/abs/1711.07752)
- [TITS2019] [Overcoming Occlusion in the Automotive Environment—A Review](https://ieeexplore.ieee.org/abstract/document/8928542/)
- [2021] [Survey of pedestrian detection with occlusion](https://link.springer.com/article/10.1007/s40747-020-00206-8)

### Object Tracking
- [TC2017] [Towards occlusion handling: object tracking with background estimation](https://ieeexplore.ieee.org/abstract/document/7994708)
- [TMM2018] [Context-aware three-dimensional mean-shift with occlusion handling for robust object tracking in RGB-D videos](https://ieeexplore.ieee.org/abstract/document/8425768/)
- [2020] [A Bayesian Filter for Multi-view 3D Multi-object Tracking with Occlusion Handling](https://arxiv.org/abs/2001.04118)

### Face detection
- [TPAMI2017] [Faceness-net: Face detection through deep facial part responses](https://arxiv.org/abs/1701.08393)
- [ICMR2020] [Occlusion-Aware GAN for Face De-Occlusion in the Wild](https://ieeexplore.ieee.org/abstract/document/9102788)
- [2020] [A survey of face recognition techniques under occlusion](https://arxiv.org/abs/2006.11366)

### Stereo
- [BMVC2018] [Symmnet: A symmetric convolutional neural network for occlusion detection](https://arxiv.org/abs/1807.00959)

### Car Detection
- [SP2015] [Inferring occluded features for fast object detection](https://www.sciencedirect.com/science/article/abs/pii/S0165168414004940)
- [CVPR2019] [Occlusion-Net: 2D/3D Occluded Keypoint Localization Using Graph Networks](https://openreview.net/pdf?id=_cv1Qp4e3x)
- [WACV2020] [Combining Compositional Models and Deep Networks For Robust Object Classification under Occlusion](https://arxiv.org/abs/1905.11826)
  - 提出数据集Occluded-Vehicles
- [CVPR2020] [Compositional Convolutional Neural Networks: A Deep Architecture with Innate Robustness to Partial Occlusion](https://arxiv.org/pdf/2003.04490.pdf) [[Code]](https://github.com/AdamKortylewski/CompositionalNets)
  - 使用数据集Occluded-Vehicles
  
### Others
- [IROS2018] [Instance segmentation of visible and occluded regions for finding and picking target from a pile of objects](https://ieeexplore.ieee.org/abstract/document/8593690)
- [3DV2018] [Seethrough: Finding objects in heavily occluded indoor scene images](https://ieeexplore.ieee.org/abstract/document/8490977)
- [IROS2019] [Seeing behind things: Extending semantic segmentation to occluded regions](https://arxiv.org/abs/1906.02885)

### General
- [CVPR2006] [The layout consistent random field for recognizing and segmenting partially occluded objects](https://ieeexplore.ieee.org/abstract/document/1640739/)
- [CVPR2011] [A segmentation-aware object detection model with occlusion handling](https://ieeexplore.ieee.org/abstract/document/5995623)
- [BMVC2016] [Measuring the effect of nuisance variables on classifiers](https://infoscience.epfl.ch/record/220613)
- [ECCV2016] [Amodal instance segmentation](https://arxiv.org/abs/1604.08202)
- [CVPR2016] [Context encoders: Feature learning by inpainting](https://arxiv.org/abs/1604.07379)
  - inpainting是解决遮挡的一种方法，但是与实际任务不符
- [2017] [Detecting semantic parts on partially occluded objects](https://arxiv.org/abs/1707.07819)
- [2017] [Improved regularization of convolutional neural networks with cutout](https://arxiv.org/abs/1708.04552)
- [CVPR2017] [A-fast-rcnn: Hard positive generation via adversary for object detection](https://arxiv.org/abs/1704.03414)
- [CVPR2018] [Segan: Segmenting and generating the invisible](https://arxiv.org/abs/1703.10239)
  - 提出DYCE数据集
- [CVPR2018] [Deepvoting: A robust and explainable deep network for semantic part detection under partial occlusion](https://arxiv.org/abs/1709.04577)
- [2019] [Robustness of Object Recognition under Extreme Occlusion in Humans and Computational Models](https://arxiv.org/abs/1905.04598)
- [2019] [Tdapnet: Prototype network with recurrent top-down attention for robust object classification under partial occlusion](https://arxiv.org/abs/1909.03879)
- [CVPR2019] [Amodal instance segmentation with kins dataset](https://openreview.net/forum?id=H7AvC4XeO6r)
  - 提出KITTI数据集，针对amodal实例分割任务
- [WACV2019] [Learning to see the invisible: End-to-end trainable amodal instance segmentation](https://arxiv.org/abs/1804.08864)
- [IJCV2020] [Deep Learning for Generic Object Detection: A Survey](https://arxiv.org/abs/1809.02165)
  - 只提到了一点关于occlusion
- [CVPR2020] [Robust object detection under occlusion with context-aware compositionalnets](https://arxiv.org/abs/2005.11643)
  - 提出新遮挡数据集 OccludedCOCO
- [CVPR2020] [Self-supervised scene de-occlusion](https://arxiv.org/abs/2004.02788)
- [IJCV2021] [Compositional convolutional neural networks: A robust and interpretable model for object recognition under occlusion](https://arxiv.org/pdf/1905.04598.pdf)