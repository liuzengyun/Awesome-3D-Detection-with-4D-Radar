# Awesome-3D-Detection-with-4D-Radar

![Aptiv_4D_Radar_og](https://lzypicstorage.oss-cn-beijing.aliyuncs.com/pic/Aptiv_4D_Radar_og.jpg)

## Overview

[Datasets](#Datasets)

[SOTA Papers](#SOTA-Papers)

​        [From 4D Radar Point Cloud](#From-4D-Radar-Point-Cloud)

​        [Fusion of 4D Radar & LiDAR](#Fusion-of-4D-Radar-&-LiDAR)

​        [Fusion of 4D Radar & RGB Camera](#Fusion-of-4D-Radar-&-RGB-Camera)

​        [Others](#Others)

[Basic Knowledge](#Basic-Knowledge)

## Datasets

|      Dataset       |                Sensors                 | Radar Data  |   Source   |   Annotations    |                             url                              |               Other               |
| :----------------: | :------------------------------------: | :---------: | :--------: | :--------------: | :----------------------------------------------------------: | :-------------------------------: |
|       Astyx        |         4D Radar,LiDAR, Camera         |     PC      |  19'EuRAD  |     3D bbox      | [github](https://github.com/under-the-radar/radar_dataset_astyx/)  [paper](https://ieeexplore.ieee.org/abstract/document/8904734) |            ~500 frames            |
|       RADIal       |         4D Radar,LiDAR, Camera         | PC, ADC, RT |  22'CVPR   |   2D bbox, seg   | [github](https://github.com/valeoai/RADIal)  [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Rebut_Raw_High-Definition_Radar_for_Multi-Task_Learning_CVPR_2022_paper.pdf) |       8,252 labeled frames        |
| View-of-Delft(VoD) |     4D Radar,LiDAR, Stereo Camera      |     PC      |  22'RA-L   |     3D bbox      | [website](https://tudelft-iv.github.io/view-of-delft-dataset/) |           8,693 frames            |
|     TJ4DRadSet     |      4D Radar,LiDAR, Camera, GNSS      |     PC      |  22'ITSC   | 3D bbox, TrackID | [github](https://github.com/TJRadarLab/TJ4DRadSet)  [paper](https://ieeexplore.ieee.org/abstract/document/9922539) |           7,757 frames            |
|      K-Radar       | 4D Radar,LiDAR, Stereo Camera, RTK-GPS |     RT      | 22'NeurIPS | 3D bbox, TrackID | [github](https://github.com/kaist-avelab/k-radar)  [paper](https://arxiv.org/pdf/2206.08171) |      35K frames; 360° Camera      |
|     Dual Radar     |      dual 4D Radars,LiDAR, Camera      |     PC      |  23'arXiv  | 3D bbox, TrackID |          [paper](https://arxiv.org/pdf/2310.07602)           |            10K frames             |
|      L-RadSet      |       4D Radar,LiDAR, 3 Cameras        |     PC      |   24'TIV   | 3D bbox, TrackID | [github](https://github.com/crrasjtu/L-RadSet)  [paper](https://ieeexplore.ieee.org/abstract/document/10591452) | 11.2K frames; Annos range to 220m |
|                    |                                        |             |            |                  |                                                              |                                   |

## SOTA Papers

### From 4D Radar Point Cloud

1. **RPFA-Net: a 4D RaDAR Pillar Feature Attention Network for 3D Object Detection (21'ITSC)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9564754) [code](https://github.com/Nerdmust/astyx-pcdet-radar)
   - **:school:Affiliation:** Tsinghua University (Xinyu Zhang)
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 
2. **Multi-class road user detection with 3+1D radar in the View-of-Delft dataset (22'RA-L)** 
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9699098)
   - **:school:Affiliation:** 
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** baseline of VoD
3. **SMURF: Spatial multi-representation fusion for 3D object detection with 4D imaging radar (23'TIV)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10274127)
   - **:school:Affiliation:** Beihang University (Bing Zhu)
   - **:file_folder:Dataset:** VoD, TJ4DRadSet
   - **:book:Note:** 
4. **PillarDAN: Pillar-based Dual Attention Attention Network for 3D Object Detection with 4D RaDAR (23'ITSC)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10422406)
   - **:school:Affiliation:** Shanghai Jiao Tong University (Lin Yang)
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 
5. **MVFAN: Multi-view Feature Assisted Network for 4D Radar Object Detection (23'ICONIP)**
   - **:link:Link:** [paper](https://link.springer.com/chapter/10.1007/978-981-99-8070-3_38)
   - **:school:Affiliation:** Nanyang Technological University
   - **:file_folder:Dataset:** Astyx, VoD
   - **:book:Note:** 
6. **SMIFormer: Learning Spatial Feature Representation for 3D Object Detection from 4D Imaging Radar via Multi-View Interactive Transformers (23'Sensors)**
   - **:link:Link:** [paper](https://www.mdpi.com/1424-8220/23/23/9429)
   - **:school:Affiliation:** Tongji University
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** 
7. **RadarPillars: Efficient Object Detection from 4D Radar Point Clouds (24'arXiv)**
   - **:link:Link:** [paper](https://arxiv.org/pdf/2408.05020)
   - **:school:Affiliation:** Mannheim University of Applied Sciences, Germany
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** 
8. 

### Fusion of 4D Radar & LiDAR

1. **InterFusion: Interaction-based 4D Radar and LiDAR Fusion for 3D Object Detection (22'IROS)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9982123)
   - **:school:Affiliation:** Tsinghua University (Li Wang)
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 
2. **Multi-Modal and Multi-Scale Fusion 3D Object Detection of 4D Radar and LiDAR for Autonomous Driving (23'TVT)** 
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/9991894)
   - **:school:Affiliation:** Tsinghua University (Li Wang)
   - **:file_folder:Dataset:** Astyx
   - **:book:Note:** 
3. **L4DR: LiDAR-4DRadar Fusion for Weather-Robust 3D Object Detection (24'arXiv)**
   - **:link:Link:** [paper](https://arxiv.org/pdf/2408.03677)
   - **:school:Affiliation:** Xiamen University
   - **:file_folder:Dataset:** VoD, K-Radar
   - **:book:Note:** For the K-Radar dataset, we preprocess the 4D radar spar setensor by selecting only the top 10240 points with high power measurement. This paper is submitted to 25'AAAI. 
4. **Robust 3D Object Detection from LiDAR-Radar Point Clouds via Cross-Modal Feature Augmentation (24'ICRA)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10610775)  [code](https://github.com/DJNing/See_beyond_seeing)
   - **:school:Affiliation:** University of Edinburgh (Chris Xiaoxuan Lu)
   - **:file_folder:Dataset:** VoD
   - **:book:Note:** 

### Fusion of 4D Radar & RGB Camera

1. **LXL: LiDAR Excluded Lean 3D Object DetectionWith 4D Imaging Radar and Camera Fusion (24'TIV)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10268601)
   - **:school:Affiliation:** Beihang University (Bing Zhu)
   - **:file_folder:Dataset:** VoD, TJ4DRadSet
   - **:book:Note:** 
2. **RCFusion: Fusing 4-D Radar and Camera With Bird’s-Eye View Features for 3-D Object Detection (23'TIM)**
   - **:link:Link:** [paper](https://ieeexplore.ieee.org/abstract/document/10138035)
   - **:school:Affiliation:** Tongji University
   - **:file_folder:Dataset:** VoD, TJ4DRadSet
   - **:book:Note:** 


### Others

1. **Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions (24'CVPR)**
   - **:link:Link:** [paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html)  [code](https://github.com/yujeong-star/RL_3DOD)
   - **:school:Affiliation:** KAIST
   - **:file_folder:Dataset:** K-Radar
   - **:book:Note:** This method takes LiDAR point cloud, 4D **radar tensor (not point cloud)** and image as input.



## Basic Knowledge

### Different Radar Data Representations

- PC: point cloud
- ADC: analog-to-digital converter signal
- RT: Radar Tensor



## Representative researchers

- [**Li Wang**](https://scholar.google.com/citations?hl=zh-CN&user=kLTnwAsAAAAJ&view_op=list_works&sortby=pubdate) (Postdoctoral Fellow) and his co-leader **Xinyu Zhang** @Tsinghua University
- [**Bing Zhu**](https://shi.buaa.edu.cn/zhubing/zh_CN/index.htm) @Beihang University
- [**Lin Yang**](https://me.sjtu.edu.cn/teacher_directory1/2080.html) @Shanghai Jiao Tong University
- [**Chris Xiaoxuan Lu**](https://christopherlu.github.io) @University College London (UCL)
- 













