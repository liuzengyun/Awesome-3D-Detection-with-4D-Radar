# Awesome-3D-Detection-with-4D-Radar



## Overview

[TOC]

## Datasets

|      Dataset       |                Sensors                 | Radar Data  |   Source   |   Annotations    |                             url                              |        Other         |
| :----------------: | :------------------------------------: | :---------: | :--------: | :--------------: | :----------------------------------------------------------: | :------------------: |
|       Astyx        |         4D Radar,LiDAR, Camera         |     PC      |  19'EuRAD  |     3D bbox      | [github](https://github.com/under-the-radar/radar_dataset_astyx/)  [paper](https://ieeexplore.ieee.org/abstract/document/8904734) |     ~500 frames      |
|       RADIal       |         4D Radar,LiDAR, Camera         | PC, ADC, RT |  22'CVPR   |   2D bbox, seg   | [github](https://github.com/valeoai/RADIal)  [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Rebut_Raw_High-Definition_Radar_for_Multi-Task_Learning_CVPR_2022_paper.pdf) | 8,252 labeled frames |
| View-of-Delft(VoD) |     4D Radar,LiDAR, Stereo Camera      |     PC      |  22'RA-L   |     3D bbox      | [website](https://tudelft-iv.github.io/view-of-delft-dataset/) |     8,693 frames     |
|     TJ4DRadSet     |      4D Radar,LiDAR, Camera, GNSS      |     PC      |  22'ITSC   | 3D bbox, TrackID | [github](https://github.com/TJRadarLab/TJ4DRadSet)  [paper](https://ieeexplore.ieee.org/abstract/document/9922539) |     7,757 frames     |
|      K-Radar       | 4D Radar,LiDAR, Stereo Camera, RTK-GPS |     RT      | 22'NeurIPS | 3D bbox, TrackID | [github](https://github.com/kaist-avelab/k-radar)  [paper](https://arxiv.org/pdf/2206.08171) |      35K frames      |
|     Dual Radar     |      dual 4D Radars,LiDAR, Camera      |     PC      |  23'arXiv  | 3D bbox, TrackID |          [paper](https://arxiv.org/pdf/2310.07602)           |      10K frames      |
|      ZJUODset      |                                        |             |            |                  |                                                              |                      |
|                    |                                        |             |            |                  |                                                              |                      |

## SOTA Papers

### From 4D Radar Point Cloud

1. **RPFA-Net: a 4D RaDAR Pillar Feature Attention Network for 3D Object Detection (21'ITSC)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9564754)
   - **:school:Affiliation:** Tsinghua University
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 
2. **Multi-class road user detection with 3+ 1D radar in the View-of-Delft dataset (22'RA-L)** 
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9699098)
   - **:school:Affiliation:** 
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** baseline of VoD
3. **SMURF: Spatial multi-representation fusion for 3D object detection with 4D imaging radar (23'TIV)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10274127)
   - **:school:Affiliation:** Beihang University
   - **:file_folder:Dataset:** VoD, TJ4DRadSet
   - **:book:Note:** 
4. **RadarPillars: Efficient Object Detection from 4D Radar Point Clouds (24'arXiv)**
   - **:link:Link:** [paper](https://arxiv.org/pdf/2408.05020)
   - **:school:Affiliation:** Mannheim University of Applied Sciences, Germany
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** 

### Fusion of 4D Radar & LiDAR

1. **InterFusion: Interaction-based 4D Radar and LiDAR Fusion for 3D Object Detection (24'IROS)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9982123)
   - **:school:Affiliation:** Tsinghua University
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 

### Fusion of 4D Radar & RGB Camera


### Others

1. **Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions (24'CVPR)**
   - **:link:Link:** [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html)  [code](https://github.com/yujeong-star/RL_3DOD)
   - **:school:Affiliation:** KAIST
   - **:file_folder:Dataset:** K-Radar
   - **:book:Note:** This method takes LiDAR point cloud, 4D radar tensor and image as input.
2. 



## Basic Knowledge

### Different Radar Data Representations

- PC: point cloud
- ADC: analog-to-digital converter signal
- RT: Radar Tensor