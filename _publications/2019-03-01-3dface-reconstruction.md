---
title: "Joint 3d face reconstruction and dense face alignment from a single image with 2d-assisted self-supervised learning"
collection: publications
permalink: /publication/2019-03-01-3dface-reconstruction
excerpt: 'Introduce a 3d face reconstruction framework assisted by 2d face images in the wild.'
date: 2019-03-01
venue: 'IEEE-TMM'
---
3D face reconstruction from a single 2D image is a challenging problem with broad applications. Recent methods typically aim to learn a CNN-based 3D face model that regresses coefficients of 3D Morphable Model (3DMM) from 2D images to render 3D face reconstruction or dense face alignment. However, the shortage of training data with 3D annotations considerably limits performance of those methods. To alleviate this issue, we propose a novel 2D-assisted self-supervised learning (2DASL) method that can effectively use “in-the-wild” 2D face images with noisy landmark information to substantially improve 3D face model learning. Specifically, taking the sparse 2D facial landmarks as additional information, 2DSAL introduces four novel self-supervision schemes that view the 2D landmark and 3D landmark prediction as a self-mapping process, including the 2D and 3D landmark self-prediction consistency, cycle-consistency over the 2D landmark prediction and self-critic over the predicted 3DMM coefficients based on landmark predictions. Using these four self-supervision schemes, the 2DASL method significantly relieves demands on the the conventional paired 2D-to-3D annotations and gives much higher-quality 3D face models without requiring any additional 3D annotations. Experiments on multiple challenging datasets show that our method outperforms state-of-the-arts for both 3D face reconstruction and dense face alignment by a large margin.
[Download paper here](https://ieeexplore.ieee.org/abstract/document/9091237)

Recommended citation: 
```
@ARTICLE{9091237,
  author={Tu, Xiaoguang and Zhao, Jian and Xie, Mei and Jiang, Zihang and Balamurugan, Akshaya and Luo, Yao and Zhao, Yang and He, Lingxiao and Ma, Zheng and Feng, Jiashi},
  journal={IEEE Transactions on Multimedia}, 
  title={3D Face Reconstruction From A Single Image Assisted by 2D Face Images in the Wild}, 
  year={2021},
  volume={23},
  number={},
  pages={1160-1172},
  doi={10.1109/TMM.2020.2993962}}
```