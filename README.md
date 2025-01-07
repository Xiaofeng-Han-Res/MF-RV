# MF-RV
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/Xiaofeng-Han-Res/MF-RV?color=green) 
[![](https://img.shields.io/badge/PRs-Welcome-%23FF4500)](https://github.com/Xiaofeng-Han-Res/MF-RV)
![](https://img.shields.io/github/stars/Xiaofeng-Han-Res/MF-RV?color=yellow)
![](https://img.shields.io/github/forks/Xiaofeng-Han-Res/MF-RV?color=lightblue) 

<div style="text-align: justify">

This is a compilation on "Multimodal Fusion for Robot Vision," including state-of-the-art benchmarks and datasets.  

</div>

## News

## Overview

## Table of Contents
- [MF-RV](#MF-RV)
  - [News](#news)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Related Surveys](#related-surveys)
  - [Awesome Benchmarks](#awesome-benchmarks)
  - [Embodied Large Language Models](#embodied-large-language-models)

## Related Surveys

## :bar_chart:Awesome Benchmarks

### Scene Understanding Datasets
<table>
  <thead>
    <tr>
      <th>Datasets</th>
      <th>Scene</th>
      <th>Multimodal Data</th>
      <th>Venue</th>
      <th>Year</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_360x_A_Panoptic_Multi-modal_Scene_Understanding_Dataset_CVPR_2024_paper.pdf">360+x</a></td>
      <td>Indoor/Outdoor</td>
      <td>Video/Audio</td>
      <td>CVPR</td>
      <td>2024</td>
    </tr>
     <tr>
      <td><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Azuma_ScanQA_3D_Question_Answering_for_Spatial_Scene_Understanding_CVPR_2022_paper.pdf">ScanQA</a></td>
      <td>Indoor</td>
      <td>RGB/Text</td>
      <td>CVPR</td>
      <td>2022</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Roberts_Hypersim_A_Photorealistic_Synthetic_Dataset_for_Holistic_Indoor_Scene_Understanding_ICCV_2021_paper.pdf">Hypersim</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>ICCV</td>
      <td>2021</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf">NuScenes</a></td>
      <td>Urban street</td>
      <td>RGB/Lidar/Radar</td>
      <td>CVPR</td>
      <td>2020</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Scalability_in_Perception_for_Autonomous_Driving_Waymo_Open_Dataset_CVPR_2020_paper.pdf">Waymo</a></td>
      <td>Outdoor</td>
      <td>RGB/Lidar</td>
      <td>CVPR</td>
      <td>2020</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Behley_SemanticKITTI_A_Dataset_for_Semantic_Scene_Understanding_of_LiDAR_Sequences_ICCV_2019_paper.pdf">Semantickitti</a></td>
      <td>Urban street</td>
      <td>RGB/Lidar</td>
      <td>ICCV</td>
      <td>2019</td>
    </tr>
    <tr>
      <td><a href="https://arxiv.org/pdf/1709.06158">Matterport3D</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>arxiv</td>
      <td>2017</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf">ScanNet</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>CVPR</td>
      <td>2017</td>
    </tr>
    <tr>
      <td><a href="https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf">Cityscapes</a></td>
      <td>Urban street</td>
      <td>RGB/Depth</td>
      <td>CVPR</td>
      <td>2016</td>
    </tr>
    <tr>
      <td><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/shkf_eccv2012.pdf">NYUDv2</a></td>
      <td style="text-align: center;">Indoor</td>
      <td>RGB/Depth</td>
      <td>ECCV</td>
      <td>2012</td>
    </tr>
  </tbody>
</table>

### Robot Manipulation Dataset
* Grasp-Anything++: Language-driven Grasp Detection(CVPR, 2024) [[paper]](https://arxiv.org/abs/2406.09489)
* Grasp-Anything-6D: Language-Driven 6-DoF Grasp Detection Using Negative Prompt Guidance(ECCV, 2024) [[paper]](https://arxiv.org/abs/2407.13842)
* Real-to-Sim Grasp: Rethinking the Gap between Simulation and Real World in Grasp Detection(CORL, 2024) [[paper]](https://arxiv.org/abs/2410.06521)
* Open X-Embodiment: Robotic Learning Datasets and RT-X Models(ICRA, 2024) [[paper]](https://arxiv.org/abs/2310.08864)
* DROID: A Large-Scale In-The-Wild Robot Manipulation Dataset(ICRA, 2024) [[paper]](https://arxiv.org/abs/2403.12945)
* Objectfolder 2.0: A multisensory object dataset for sim2real transfer (CVPR, 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_ObjectFolder_2.0_A_Multisensory_Object_Dataset_for_Sim2Real_Transfer_CVPR_2022_paper.pdf)
* Touch and Go: Learning from Human-Collected Vision and Touch Supplementary Material (NuerIPS, 2022) [[paper]](https://arxiv.org/pdf/2211.12498)
* Connecting Touch and Vision via Cross-Modal Prediction (CVPR, 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Connecting_Touch_and_Vision_via_Cross-Modal_Prediction_CVPR_2019_paper.pdf)
* Rt-1: Robotics transformer for real-world control at scale (arXiv, 2022) [[paper]](https://arxiv.org/pdf/2212.06817)
  
### Manipulation Benchmarks
  | **Title** | **Venue** | **Date** |
|----------------------------|-------------------|------------|
| **Manipulation in Home Environment** | | |
| [HomeRobot: Open-Vocabulary Mobile Manipulation](https://arxiv.org/abs/2306.11565) | CoRL 2023 | 2023-06-20 |
| [ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks](https://arxiv.org/abs/1912.01734) | CVPR 2020 | 2019-12-03 |
| **Manipulation in On-Table Environment** | | |
| [OBSBench: Point Cloud Matters: Rethinking the Impact of Different Observation Spaces on Robot Learning](https://arxiv.org/abs/2402.02500) | NeurIPS 2024 | 2024-02-04 |
| [LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning](https://arxiv.org/abs/2306.03310) | NeurIPS 2023 | 2023-06-05 |


## Embodied Large Language Models
| 数据集名称             | 核心模态              | 数据规模              | 创新点与优势                                   | 适用场景                             |
|-----------------------|--------------------|-------------------|------------------------------------------|----------------------------------|
| DROID                | RGB、深度、语言       | 76,000轨迹         | 多视角相机与语言标注，多任务、多场景适配          | 多任务学习，多场景泛化                     |
| R2SGrasp             | 深度、抓取           | 64,000 RGB-D图像  | “Real-to-Sim”框架，消除模拟与现实之间的噪声差距   | 精确抓取检测，模拟到现实迁移                 |
| RT-1                 | RGB、语言           | 130,000轨迹        | Transformer架构，实时多任务控制                 | 高效泛化，适用于复杂任务                   |
| Touch and Go         | 视觉、触觉           | 未明确             | 自监督学习，关联视觉和触觉                     | 跨模态感知，触觉信号预测                    |
| VisGel               | GelSight触觉、视觉   | 12,000触摸交互      | 跨模态双向生成（视觉到触觉，触觉到视觉）           | 跨模态学习，触觉增强视觉                    |
| ObjectFolder 2.0     | 视觉、音频、触觉       | 1,000虚拟对象模型    | 隐式神经表示，高效多模态渲染                   | 多模态学习，虚拟到现实迁移                   |
| Grasp-Anything-6D    | 点云、语言           | 1M点云场景          | 负提示策略，提升6自由度抓取的语言控制能力         | 复杂多物体场景下的语言驱动抓取               |
| Grasp-Anything++     | 点云、语言           | 1M样本，10M抓取指令 | 细粒度抓取标注，支持局部抓取                   | 细粒度抓取，零样本任务                     |
| Open X-Embodiment    | RGB、深度、语言，多机器人形态 | 多机构数据整合        | 任务无关采集方式，多机器人系统的统一数据支持       | 跨机器人系统的泛化与迁移学习                |

* Rt-2: Vision-language-action models transfer web knowledge to robotic control (arXiv, 2023) [[paper]](https://arxiv.org/pdf/2307.15818)
* Open x-embodiment: Robotic learning datasets and rt-x models (arXiv, 2023) [[paper]](https://arxiv.org/pdf/2310.08864)
* Rt-h: Action hierarchies using language (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2403.01823)
* Autort: Embodied foundation models for large scale orchestration of robotic agents (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2401.12963)
* Gr-2: A generative video-language-action model with web-scale knowledge for robot manipulation (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2410.06158)
* Voxposer: Composable 3d value maps for robotic manipulation with language models (arXiv, 2023) [[paper]](https://arxiv.org/pdf/2307.05973)
* Rdt-1b: a diffusion foundation model for bimanual manipulation (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2410.07864)
* Rekep: Spatio-temporal reasoning of relational keypoint constraints for robotic manipulation (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2409.01652)
* Copa: General robotic manipulation through spatial constraints of parts with foundation models (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2403.08248)
* OpenVLA: An Open-Source Vision-Language-Action Model (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2406.09246)
* Palm-e: An embodied multimodal language model (arXiv, 2023) [[paper]](https://arxiv.org/pdf/2303.03378)
* Π0: A Vision-Language-Action Flow Model for General Robot Control (arXiv, 2024) [[paper]](https://arxiv.org/pdf/2410.24164?)
