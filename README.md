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
      <td><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/shkf_eccv2012.pdf">NYUDv2</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>ECCV</td>
      <td>2012</td>
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
      <td><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Behley_SemanticKITTI_A_Dataset_for_Semantic_Scene_Understanding_of_LiDAR_Sequences_ICCV_2019_paper.pdf">Semantickitti</a></td>
      <td>Urban street</td>
      <td>RGB/Lidar</td>
      <td>ICCV</td>
      <td>2019</td>
    </tr>
    <tr>
      <td><a href="https://arxiv.org/pdf/2109.08238">Matterport3D</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>arxiv</td>
      <td>2019</td>
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
      <td><a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Roberts_Hypersim_A_Photorealistic_Synthetic_Dataset_for_Holistic_Indoor_Scene_Understanding_ICCV_2021_paper.pdf">Hypersim</a></td>
      <td>Indoor</td>
      <td>RGB/Depth</td>
      <td>ICCV</td>
      <td>2021</td>
    </tr>
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
  </tbody>
</table>

### Dataset
* Objectfolder 2.0: A multisensory object dataset for sim2real transfer (CVPR, 2022) [[paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Gao_ObjectFolder_2.0_A_Multisensory_Object_Dataset_for_Sim2Real_Transfer_CVPR_2022_paper.pdf)
* Touch and Go: Learning from Human-Collected Vision and Touch Supplementary Material (NuerIPS, 2022) [[paper]](https://arxiv.org/pdf/2211.12498)
* Connecting Touch and Vision via Cross-Modal Prediction (CVPR, 2019) [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Connecting_Touch_and_Vision_via_Cross-Modal_Prediction_CVPR_2019_paper.pdf)

## Embodied Large Language Models
* Rt-1: Robotics transformer for real-world control at scale (arXiv, 2022) [[paper]](https://arxiv.org/pdf/2212.06817)
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
