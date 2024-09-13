Awesom high definition map methods collection with detailed interpretations of some key papers.

## 1. Online HD Map

### 1.1 Roadmap

![image-20240911151131406](HDMap_Survey.assets/image-20240911151131406.png)

### 1.2 Paper list

#### 2024

StreamMapNet: Streaming Mapping Network for Vectorized Online HD Map Construction [[code](https://github.com/yuantianyuan01/StreamMapNet)] [WACV2024](https://openaccess.thecvf.com/content/WACV2024/papers/Yuan_StreamMapNet_Streaming_Mapping_Network_for_Vectorized_Online_HD_Map_Construction_WACV_2024_paper.pdf)

SuperFusion: Multilevel LiDAR-Camera Fusion for Long-Range HD Map Generation [[code](https://github.com/haomo-ai/SuperFusion)] [ICRA2024](https://arxiv.org/pdf/2211.15656)

EAN-MapNet: Efficient Vectorized HD Map Construction with Anchor Neighborhoods [Arxiv](https://arxiv.org/pdf/2402.18278)

MGMap: Mask-Guided Learning for Online Vectorized HD Map Construction [[code](https://github.com/xiaolul2/MGMap)] [CVPR2024](https://arxiv.org/abs/2404.00876)

HIMap: HybrId Representation Learning for End-to-end Vectorized HD Map Construction[[code](https://github.com/BritaryZhou/HIMap), not release] [CVPR2024](https://arxiv.org/abs/2403.08639)

MapVision: CVPR 2024 Autonomous Grand Challenge Mapless Driving Tech Report [CVPR2024](https://arxiv.org/abs/2406.10125)

HybriMap: Hybrid Clues Utilization for Effective Vectorized HD Map Construction [Arxiv](https://arxiv.org/abs/2404.11155)

MapTracker: Tracking with Strided Memory Fusion for Consistent Vector HD Mapping [[code](https://github.com/woodfrog/maptracker)] [ECCV2024](https://arxiv.org/abs/2403.15951) **oral**

ADMap: Anti-disturbance framework for reconstructing online vectorized HD map [[code](https://github.com/hht1996ok/ADMap)] [ECCV2024](https://arxiv.org/pdf/2403.15951)

MapQR: Leveraging Enhanced Queries of Point Sets for Vectorized Map Construction [[code](https://github.com/HXMap/MapQR)] [ECCV2024](https://arxiv.org/pdf/2402.17430)

HRMapNet: Enhancing Vectorized Map Perception with Historical Rasterized Maps [[code](https://github.com/HXMap/HRMapNet)] [ECCV2024](https://arxiv.org/abs/2409.00620)

Mask2Map: Vectorized HD Map Construction Using Bird’s Eye View Segmentation Masks [[code](https://github.com/SehwanChoi0307/Mask2Map) ,not release] [ECCV2024](https://arxiv.org/pdf/2407.13517)

MapBEVPrediction: Accelerating Online Mapping and Behavior Prediction via Direct BEV Feature Attention [[code](https://github.com/alfredgu001324/MapBEVPrediction)] [ECCV2024](https://arxiv.org/abs/2407.06683)

DTCLMapper: Dual Temporal Consistent Learning for Vectorized HD Map Construction [[code](https://github.com/lynn-yu/DTCLMapper)] [IEEE T-ITS2024](https://arxiv.org/abs/2405.05518)

PrevPredMap: Exploring Temporal Modeling with Previous Predictions for Online Vectorized HD Map Construction [[code](https://github.com/pnnnnnnn/PrevPredMap)] [WACV2025](https://arxiv.org/abs/2407.17378)

PriorMapNet: Enhancing Online Vectorized HD Map Construction with Priors [Arxiv](https://www.arxiv.org/abs/2408.08802)

Neural HD Map Generation from Multiple Vectorized Tiles Locally Produced by Autonomous Vehicles [Arxiv](https://www.arxiv.org/abs/2409.03445)

#### 2023

VectorMapNet: End-to-end Vectorized HD Map Learning [[code](https://github.com/Mrmoore98/VectorMapNet_code)] [ICML2023](https://arxiv.org/abs/2206.08920)

MapTR: Structured Modeling and Learning for Online Vectorized HD Map Construction [[code](https://github.com/hustvl/MapTR)] [ICLR2023](https://arxiv.org/abs/2208.14437)

MapTRv2: An End-to-End Framework for Online Vectorized HD Map Construction [[code](https://github.com/hustvl/MapTR/tree/maptrv2)] [Arxiv](https://arxiv.org/abs/2308.05736)

MapVR: Online Map Vectorization for Autonomous Driving: A Rasterization Perspective[[code](https://github.com/jiahaoLjh/MapVectorizationEvalToolkit)1, [code2](https://github.com/ZhangGongjie/MapVR)] [NIPS2023](https://arxiv.org/abs/2306.10502)

BeMapNet: End-to-End Vectorized HD-Map Construction With Piecewise Bezier Curve [[code](https://github.com/er-muyue/BeMapNet)] [CVPR2023](https://arxiv.org/pdf/2306.09700)

PivotNet: Vectorized Pivot Learning for End-to-end HD Map Construction ICCV2023 [[code](https://github.com/wenjie710/PivotNet)] [ICCV2023](https://arxiv.org/abs/2308.16477)

#### Before 2023

HDMapNet: An Online HD Map Construction and Evaluation Framework [[code](https://github.com/Tsinghua-MARS-Lab/HDMapNet)] [ICRA2022,CVPR2021](https://arxiv.org/abs/2107.06307)

### 1.3 Auxiliary Knowledge or methods (Distillation) 

MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation [[code](https://github.com/Ricky-Developer/MapDistill)] [ECCV2024](https://arxiv.org/abs/2407.11682)

P-MapNet: Far-seeing Map Constructer Enhanced by both SDMap and HDMap Priors [[code](https://github.com/jike5/P-MapNet)] [ICLR2024](https://arxiv.org/abs/2403.10521) (reject)

SatForHDMap: Complementing Onboard Sensors with Satellite Map: A New Perspective for HD Map Construction [[code](https://github.com/xjtu-cs-gao/SatforHDMap)] [ICRA2024](https://arxiv.org/pdf/2308.15427)

Enhancing Online Road Network Perception and Reasoning with Standard Definition Maps [Arxiv](https://www.arxiv.org/abs/2408.01471)

Driving with Prior Maps: Unified Vector Prior Encoding for Autonomous Vehicle Mapping [Arxiv](https://arxiv.org/abs/2409.05352v2)

## 2. 衍生工作

### 2.1 鲁棒性

Is Your HD Map Constructor Reliable under Sensor Corruptions? [[code](https://github.com/mapbench/toolkit)] [Arxiv](https://arxiv.org/abs/2406.12214) 这篇蛮有意思，后续工作适合做场景迁移、半监督学习

### 2.2 矢量化场景表示

VAD: Vectorized Scene Representation for Efficient Autonomous Driving [[code](https://github.com/hustvl/VAD)] [ICCV2023](https://arxiv.org/abs/2303.12077) (MapTR同作)

Is Ego Status All You Need for Open-Loop End-to-End Autonomous Driving? [[code](https://github.com/NVlabs/BEV-Planner)] [CVPR2023](https://arxiv.org/abs/2312.03031) VAD -> BEV-Planner

### 2.3 车道线角度角度

OpenLane-V2: A Topology Reasoning Benchmark for Unified 3D HD Mapping [[code](https://github.com/OpenDriveLab/OpenLane-V2)] [NeurIPS2023](https://arxiv.org/abs/2304.10440)

### 2.4 AIGC相关

Panacea: Panoramic and Controllable Video Generation for Autonomous Driving [[code](https://panacea-ad.github.io/)] [CVPR2024](https://arxiv.org/abs/2311.16813)

Panacea+: Panoramic and Controllable Video Generation for Autonomous Driving [[code](https://panacea-ad.github.io/)] [Arxiv](https://arxiv.org/abs/2408.07605)

### 2.5 众包建图优化

CrowdSourcing Live High Definition Map via Collaborative Computation in Automotive Edge Computing [T-VT2024](https://ieeexplore.ieee.org/document/10508471)

VI-Map: Infrastructure-Assisted Real-Time HD Mapping for Autonomous Driving [MobiCom2023](https://yanzhenyu.com/assets/pdf/VI-Map-MobiCom23.pdf)

Edgemap: Crowdsourcing high definition map in automotive edge computing [ICC2022](https://arxiv.org/abs/2201.07973)



## 3. 资源开销统计

| 算法        | 训练资源                                                     |
| ----------- | ------------------------------------------------------------ |
| BEVFormer   | 8 GPUs  后续较多工作都是基于BEVFormer，基本都是8卡起步       |
| BEVDistill  | 8 NVIDIA A100 GPUs                                           |
| HDMapNet    | 这篇是属于分割方法论的，所以训练开销明显少一些，bs默认4      |
| MapTR v1/v2 | 8 NVIDIA GeForce RTX 3090 GPUs                               |
| MapDistill  | 8 NVIDIA RTX A6000 GPUs                                      |
| HRMapNet    | 8 NVIDIA A100 GPUs bs 8 × 4                                  |
| P-MapNet    | 4 NVIDIA GeForce RTX 3090 GPUs，基于HDMapNet，所以开销也不高 |
| MGMap       | 8 NVIDIA Tesla **V100** GPUs bs 8x6                          |

## 4. Reference Repo

https://github.com/LoveFaFa2333/Awesome-Online-HDMap

https://github.com/Honminden/awesome-hd-map-construction
