## 2021年
### 2021冬季
#### 2021年11月26日
#### 周远银
- **论文名字** : Hierarchical Vision Transformer using Shifted Windows;
- **论文来源** : 2021ICCV ;
- **代码地址** : [链接](https://github.com/microsoft/Swin-Transformer) 或者 https://github.com/microsoft/Swin-Transformer;
- **方法简称** : Swin-T;
- **方法方向** : 目标检测 ;
- **快速获取** :
```powershell
git clone https://github.com/microsoft/Swin-Transformer
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
| SwinTransformer作为2021 ICCV最佳论文，性能优于DeiT、ViT和EfficientNet等主干网络，已经替代经典的CNN架构，成为了计算机视觉领域通用的backbone。它基于了ViT模型的思想，创新性的引入了滑动窗口机制，让模型能够学习到跨窗口的信息，同时也。同时通过下采样层，使得模型能够处理超分辨率的图片，节省计算量以及能够关注全局和局部的信息，微软官方公开源码涵盖图像分类、目标检测以及语义分割任务。|

#### 张晓馨
- **论文名字** : Structural Deep Clustering Network;
- **论文来源** : 2020WWW ;
- **代码地址** : [链接](https://github.com/bdy9527/SDCN) 或者 https://github.com/bdy9527/SDCN ;
- **方法简称** : SDCN ;
- **方法方向** : 深度聚类 ;
- **快速获取** :
```powershell
git clone https://github.com/bdy9527/SDCN
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
| 深度聚类的基本思想是将深度学习强大的表征能力融入到聚类的目标中。因此，有效的学习数据的表征是深度聚类的关键前提。本文提出了一个结构化的深度聚类网络（SDCN），用来将结构化的信息整合到深度聚类中。设计了一个传递算子将autoencoder学习到的表示传递到相应的GCN层，并设计了双重自监督机制来统一这两种不同的深层神经结构并指导整个模型的更新。 |

#### 2021年12月3日
#### 孟运动
- **论文名字** :  Heterogeneous Graph Structure Learning for Graph Neural Networks ;
- **论文来源** : 2021AAAI ;
- **代码地址** : [链接](https://github.com/Andy-Border/HGSL) 或者 https://github.com/Andy-Border/HGSL ;
- **方法简称** : HGSL ;
- **方法方向** : 异质图神经网络;
- **快速获取** :
```powershell
git clone https://github.com/Andy-Border/HGSL
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
| 现有的HGNN的成功依赖于原始异质图结构良好且适合下游任务的这个假设，然而这种假设因为以下原因经常不成立：1.由于异质图通常是根据一些预先定义的规则从复杂的交互系统中提取得出，这些交互系统本身不可避免地包含了一些不确定的信息或错误。2.异质图的提取通常要经过一些预定义的规则经过数据清洗、特征提取和特征转换等过程，这些过程通常独立于下游任务，导致提取的图结构与下游任务之间存在差距。因此，如何为异质图神经网络学习一个合适的图结构而不是依赖于原始图结构是一个关键问题。为解决这个问题，本文首次研究了异质图结构学习问题，并提出了一个新的框架HGSL，该框架根据下游任务对异质图结构和GNN参数进行联合学习。|

#### 郭海洋
- **论文名字** :  Self-Supervised Learning of Physics-Guided;
- **论文来源** : 2020 Magnetic resonance in medicine ;
- **代码地址** : [链接](https://github.com/byaman14/SSDU) 或者 https://github.com/byaman14/SSDU ;
- **方法简称** : SSDU;
- **方法方向** :图像重建 ;
- **快速获取** :
```powershell
git clone https://github.com/byaman14/SSDU
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
|开发一种无需完全采样数据集数据库的物理引导MRI重建神经网络训练策略。用于物理引导深度学习（DL）重建的基于采样下数据的自监督学习（SSDU）将可用测量划分为两个不相交的集合，其中一个用于展开网络中的数据一致性单元，另一个用于定义训练损失。将不使用完全采样数据的拟议训练与使用地面真实数据的完全监督训练以及使用公开可用的fastMRI膝关节数据库的传统压缩感知和并行成像方法进行比较。建议的SSDU和监督训练均使用相同的物理引导神经网络。SSDU训练还应用于不同加速率下前瞻性2倍加速高分辨率大脑数据集，并与并行成像进行比较。|

#### 2021年12月11日
#### 张学良
- **论文名字** :  TAM：Temporal Adaptive Module for Video Recognition ;
- **论文来源** : 2021 ICLR ;
- **代码地址** : [链接](https://github.com/liu-zhy/temporal-adaptive-module.) 或者 https://github.com/liu-zhy/temporal-adaptive-module. ;
- **方法简称** : TAM ;
- **方法方向** : 行为识别 ;
- **快速获取** :
```powershell
git clone https://github.com/liu-zhy/temporal-adaptive-module.
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
| 由于摄像机运动、速度变化和不同活动等因素的影响，视频数据具有复杂的时间动态特性。随着视频数据不断增长，其中内容的也会变得越来越多样。为了有效地捕获这种不同的运动模式，本文提出了一种新的时间自适应模块 （TAM)，该模块基于自身的特征映射生成视频特定的时间核。TAM提出了一种独特的两级自适应建模方案，将动态核解耦为位置敏感的重要性映射和位置不变的聚合权重。在局部时间窗口中学习重要性图以获取短期信息，而聚合权重则从全局视图生成，重点关注长期结构。 |

#### 颜煜宸
- **论文名字** : Cross-Modal Collaborative Representation Learning and a Large-Scale
RGBT Benchmark for Crowd Counting;
- **论文来源** : 2021CVPR  ;
- **代码地址** : [链接](https://github.com/chen-judge/RGBTCrowdCounting) 或者 https://github.com/chen-judge/RGBTCrowdCounting ;
- **方法简称** : RGBT-CC;
- **方法方向** :人群计数 ;
- **快速获取** :
```powershell
git clone https://github.com/chen-judge/RGBTCrowdCounting.
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
|人群计数旨在自动估计在各种场景中的人数，在交通管理和视频监控等方面有很大的应用潜力。特别是在疫情时期，可以帮助控制社交距离。大多数以前的方法仅利用RGB图像的有限信息，这可能无法在光照不足或其他限制性的环境中发现潜在的行人或错把类似人形的物体当作行人。而在这项工作中通过结合光学和热学信息可以极大地帮助识别行人。 |

#### 2021年12月24日
#### 程蕾磊
- **论文名字** :  Appearance and Motion Enhancement for Video-Based Person Re-Identification ;
- **论文来源** : 2020 AAA ;
- **代码地址** : [链接](None) 或者 None;
- **方法简称** : AMEM;
- **方法方向** : 行人重识别 ;
- **快速获取** :
```powershell
None
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
| 行人的重识别(ReID)是指在非重叠摄像机拍摄的视频中匹配一个人的图像。人体姿态变化、遮挡和不同的摄像机视角等问题是ReID中很大的挑战。
目前行人重识别的突出进展主要是在静态图像上，它大多利用静态图像及其空间信息来进行匹配，它与基于视频的方法相比，存在许多不足之处。
一方面，单幅图像对姿态变化和遮挡非常敏感；另一方面，仅使用单幅图像难以捕捉到人的运动模式，而人的运动模式是除外表以外识别身份的重要线索。 |

#### 王振雨
- **论文名字** : HDMI High-order Deep Multiplex Infomax;
- **论文来源** : 2021 WWW ;
- **代码地址** : [链接](https://github.com/baoyujing/hdmi) 或者 https://github.com/baoyujing/hdmi ;
- **方法简称** : HDMI;
- **方法方向** :高阶深度多层网络Infomax ;
- **快速获取** :
```powershell
git clone https://github.com/baoyujing/hdmi.
```

| 方法介绍                                                     |
| :----------------------------------------------------------- |
|HDMI:以自监督方式学习在多层网络中学习节点嵌入
1.通过高阶互信息设计一种包含外部内部MI的联合监督signal
2.引入High-order Deep Infomax (HDI)优化signal
3.引入attention机制的融合模块来结合 multiplex network 中不同层之间的node embedding
4.通过无监督聚类和监督分类评价模型 |