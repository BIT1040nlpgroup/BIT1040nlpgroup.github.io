---
title: "Enhancing Fashion Recommendation with Visual Compatibility Relationship"
collection: conference
permalink: /conference/YangLi2020GeometryDrivenSM
date: 2020-01-01
venue: AAAI
author: Yang Li, Kan Li, Shuai Jiang, Ziyue Zhang, Congzhentao Huang, Richard Yi Da Xu.
paperurl: 'https://readpaper.com/paper/2997760858'
---
Author: Yang Li, Kan Li, Shuai Jiang, Ziyue Zhang, Congzhentao Huang, Richard Yi Da XuRuiping Yin, Kan Li, Jie Lu, Guangquan Zhang.

Published in: AAAI

### Abstract

The neural network based approach for 3D human pose estimation from monocular images has attracted growing interest. However, annotating 3D poses is a labor-intensive and expensive process. In this paper, we propose a novel self-supervised approach to avoid the need of manual annotations. Different from existing weakly/self-supervised methods that require extra unpaired 3D ground-truth data to alleviate the depth ambiguity problem, our method trains the network only relying on geometric knowledge without any additional 3D pose annotations. The proposed method follows the two-stage pipeline: 2D pose estimation and 2D-to-3D pose lifting. We design the transform re-projection loss that is an effective way to explore multi-view consistency for training the 2D-to-3D lifting network. Besides, we adopt the confidences of 2D joints to integrate losses from different views to alleviate the influence of noises caused by the self-occlusion problem. Finally, we design a two-branch training architecture, which helps to preserve the scale information of re-projected 2D poses during training, resulting in accurate 3D pose predictions. We demonstrate the effectiveness of our method on two popular 3D human pose datasets, Human3.6M and MPI-INF-3DHP. The results show that our method significantly outperforms recent weakly/self-supervised approaches.

---

Recommended citation:

```
@inproceedings{YangLi2020GeometryDrivenSM,
  title={Geometry-Driven Self-Supervised Method for 3D Human Pose Estimation.},
  author={Yang Li and Kan Li and Shuai Jiang and Ziyue Zhang and Congzhentao Huang and Richard Yi Da Xu},
  booktitle={National Conference on Artificial Intelligence},
  year={2020}
}
```
