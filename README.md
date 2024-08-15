# Awesome-3D-Detection-with-4D-Radar



## Overview





## Datasets

|      Dataset       |                Sensors                 | Radar Data  |   Source   |   Annotations    |                             url                              |        Other         |
| :----------------: | :------------------------------------: | :---------: | :--------: | :--------------: | :----------------------------------------------------------: | :------------------: |
|       Astyx        |         4D Radar,LiDAR, Camera         |     PC      |  19'EuRAD  |     3D bbox      | [github](https://github.com/under-the-radar/radar_dataset_astyx/)  [paper](https://ieeexplore.ieee.org/abstract/document/8904734) |     ~500 frames      |
|       RADIal       |         4D Radar,LiDAR, Camera         | PC, ADC, RT |  22'CVPR   |   2D bbox, seg   | [github](https://github.com/valeoai/RADIal)  [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Rebut_Raw_High-Definition_Radar_for_Multi-Task_Learning_CVPR_2022_paper.pdf) | 8,252 labeled frames |
| View-of-Delft(VoD) |     4D Radar,LiDAR, Stereo Camera      |     PC      |  22'RA-L   |     3D bbox      | [website](https://tudelft-iv.github.io/view-of-delft-dataset/) |     8,693 frames     |
|     TJ4DRadSet     |      4D Radar,LiDAR, Camera, GNSS      |     PC      |  22'ITSC   | 3D bbox, TrackID | [github](https://github.com/TJRadarLab/TJ4DRadSet)  [paper](https://ieeexplore.ieee.org/abstract/document/9922539) |     7,757 frames     |
|      K-Radar       | 4D Radar,LiDAR, Stereo Camera, RTK-GPS |     RT      | 22'NeurIPS | 3D bbox, TrackID | [github](https://github.com/kaist-avelab/k-radar)  [paper](https://arxiv.org/pdf/2206.08171) |      35K frames      |
|     Dual Radar     |      dual 4D Radars,LiDAR, Camera      |     PC      |  23'arXiv  | 3D bbox, TrackID |          [paper](https://arxiv.org/pdf/2310.07602)           |      10K frames      |
|                    |                                        |             |            |                  |                                                              |                      |

## SOTA Papers

### From 4D Radar Point Cloud

- RadarPillars: Efficient Object Detection from 4D Radar Point Clouds[arxiv.org/pdf/2408.05020](https://arxiv.org/pdf/2408.05020)

### Fusion of 4D Radar & LiDAR

1. Towards Robust 3D Object Detection with LiDAR and 4D Radar Fusion in Various Weather Conditions
   - :link:: ​[paper](https://openaccess.thecvf.com/content/CVPR2024/html/Chae_Towards_Robust_3D_Object_Detection_with_LiDAR_and_4D_Radar_CVPR_2024_paper.html)

### Fusion of 4D Radar & RGB Camera







## Basic Knowledge

### Different Radar Data Representations

- PC: point cloud
- ADC: analog-to-digital converter signal
- RT: Radar Tensor