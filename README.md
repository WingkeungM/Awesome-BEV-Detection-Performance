# Awesome-BEV-Detection-Performance
Collect the Performance of 3D Object Detection Methods from Multi-View Camera Images (BEV Perception).


## nuScenes Val Set
| Method | Venue | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDepth]   |  | ResNet50 | 256x704 | 0.315 | 0.367 | 0.702 | 0.271 | 0.621 | 1.042 | 0.315 |
| []

| [FCOS3D] |  | ResNet50 |  | N | N | - | 0.299 | 0.373 | 0.785 | 0.268 | 0.557 | 1.396 | 0.154 |

| Method | Venue | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [FCOS3D] |  | ResNet101 |  | N | N | - | 0.299 | 0.373 | 0.785 | 0.268 | 0.557 | 1.396 | 0.154 |
| [DETR3D] |  | ResNet101 |  | N | N | - | 0.303 | 0.374 | 0.860 | 0.278 | 0.437 | 0.967 | 0.235 | 
| [BEVDet] |  | ResNet101 |  | N | N | - | 0.330 | 0.396 | 0.702 | 0.272 | 0.534 | 0.932 | 0.251 | 
| [PETR]   |  | ResNet101 |  | N | N | - | 0.357 | 0.421 | 0.710 | 0.270 | 0.490 | 0.885 | 0.224 | 
| [SimMOD] |  | ResNet101 | 1600x900 | N | N | - | 0.351 | 0.435 | 0.717 | 0.267 | 0.388 | 0.849 | 0.187 |
| [BEVDepth]| | ResNet101 | 256x704  | - | N | N | 0.320 | 0.381 | 0.682 0.272 0.562 0.997 0.284 | 


| [FCOS3D]     |  | ResNet101 |  | Y | N | - | 0.321 | 0.393 | 0.746 | 0.265 | 0.503 | 1.351 | 0.160 |
| [DETR3D]     |  | ResNet101 |  | Y | N | - | 0.346 | 0.425 | 0.773 | 0.268 | 0.383 | 0.842 | 0.216 | 
| [PolarDETR]  |  | ResNet101 |  | Y | N | - | 0.365 | 0.444 | 0.742 | 0.269 | 0.350 | 0.829 | 0.197 | 
| [BEVFormer-S]|  | ResNet101 |  | Y | N | - | 0.375 | 0.448 | 0.725 | 0.272 | 0.391 | 0.802 | 0.200 | 
| [PETR]       |  | ResNet101 |  | Y | N | - | 0.370 | 0.442 | 0.711 | 0.267 | 0.383 | 0.865 | 0.190 | 
| [SimMOD]     |  | ResNet101 | 1600x900 | Y | N | - | 0.366 | 0.455 | 0.698 | 0.264 | 0.340 | 0.784 | 0.197 |


| [PETR] | ECCV2022 | ResNet50 | Y | N |

| Method | Venue | backbone | temporal | external data | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|




| [PETR](https://arxiv.org/pdf/2203.05625.pdf) | ECCV2022 | ResNet101 | Y | N | |

| Method | Venue | backbone | temporal | external data | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|

| [PETR](https://arxiv.org/pdf/2203.05625.pdf) | ECCV2022 | V2-99 | Y | N | |




| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|
| [PETR](https://arxiv.org/pdf/2203.05625.pdf) | ECCV2022 | ResNet50 | Y | Y | |

| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|
| [PETR](https://arxiv.org/pdf/2203.05625.pdf) | ECCV2022 | ResNet101 | Y | Y | |

| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|
| [PETR](https://arxiv.org/pdf/2203.05625.pdf) | ECCV2022 | V2-99 | Y | Y | |

## nuScenes Test Set
| Method | Venue | backbone | temporal | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|
| [FCOS3D] |  | ResNet101 | N | 0.358 | 0.428 | 0.690 | 0.249 | 0.452 | 1.434 | 0.124 |
| [PETR] |  | ResNet101 | N | 0.391 | 0.455 | 0.647 | 0.251 | 0.433 | 0.933 | 0.143 |
| [BEVFormer-S] | ResNet101 | N | 0.409 | 0.462 | 0.650 | 0.261 | 0.439 | 0.925 | 0.147 |
| [Graph-DETR3D] | ResNet101 | N | 0.418 | 0.472 | 0.668 | 0.250 | 0.440 | 0.876 | 0.139 |
| [SimMOD] |  | ResNet101 | N | 0.382 | 0.464 | 0.623 | 0.252 | 0.394 | 0.863 | 0.132 |

| [DETR3D] |  | V2-99 | N | 0.412 | 0.479 | 0.641 | 0.255 | 0.394 | 0.845 | 0.133 |
| [BEVDet] |  | V2-99 | N | 0.424 | 0.488 | 0.524 | 0.242 | 0.373 | 0.950 | 0.148 |
| [PolarDETR] |  | V2-99 | N | 0.431 | 0.493 | 0.588 | 0.253 | 0.408 | 0.845 | 0.129 |
| [PETR] |  | V2-99 | N | 0.441 | 0.494 | 0.593 0.249 | 0.383 | 0.808 | 0.132 |
| [BEVFormer-S] |  | V2-99 | N | 0.435 | 0.495 | 0.589 | 0.254 | 0.402 | 0.842 | 0.131 |
| [Graph-DETR3D] |  | V2-99 | N | 0.425 | 0.495 | 0.621 | 0.251 | 0.386 | 0.790 | 0.128 |
| [SimMOD] |  | V2-99 | N | 0.417 | 0.494 | 0.570 | 0.248 | 0.387 | 0.813 | 0.126 |
