# Awesome-BEV-Detection-Performance
Collect the Performance of 3D Object Detection Methods from Multi-View Camera Images (BEV Perception).


## nuScenes Val Set
### ResNet50
| Method | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :----- | :-----:  |  :-----:   |    :---:        |   :---:  | :--: |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)     | ResNet50 | 256x704  | N | N | - | 0.298 | 0.379 | 0.725 | 0.279 | 0.589 | 0.860 | 0.245 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)       | ResNet50 | 1056x384 | N | N | Y | 0.313 | 0.381 | 0.768 | 0.278 | 0.564 | 0.923 | 0.225 |
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)   | ResNet50 | 256x704  | - | N | - | 0.315 | 0.367 | 0.702 | 0.271 | 0.621 | 1.042 | 0.315 |
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)     | ResNet50 | 1056x384 | N | N | - | 0.318 | 0.389 | 0.718 | 0.272 | 0.553 | 0.897 | 0.258 |
| [PolarDETR](https://arxiv.org/pdf/2206.10965.pdf)  | ResNet50 | 1600x900 | - | N | - | 0.338 | 0.409 | 0.768 | 0.284 | 0.443 | 0.883 | 0.221 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)       | ResNet50 | 1408x512 | N | N | Y | 0.339 | 0.403 | 0.748 | 0.273 | 0.539 | 0.907 | 0.203 |

### ResNet50 + temporal
| Method | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :-----:   |    :---:        |   :---:  | :--: |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)   | ResNet50 | 256x704  | - | Y | - | 0.351 | 0.475 | 0.639 | 0.267 | 0.479 | 0.428 | 0.198 |
| [PolarDETR-T](https://arxiv.org/pdf/2206.10965.pdf)  | ResNet50 | 1600x900 | - | Y | - | 0.354 | 0.458 | 0.748 | 0.277 | 0.432 | 0.539 | 0.197 |

### ResNet101
| Method | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :-----:   |    :---:        |   :---:  | :--: |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)  | ResNet101 | 704x256  | N | N | - | 0.302 | 0.381 | 0.722 | 0.269 | 0.543 | 0.900 | 0.269 |
| [SpatialDETR](https://markus-enzweiler.de/downloads/publications/ECCV2022-spatial_detr.pdf)|ResNet101|-        | N | N | N | 0.303 | 0.369 | 0.849 | 0.282 | 0.522 | 0.941 | 0.229 |
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)| ResNet101 | 256x704  | - | N | - | 0.320 | 0.381 | 0.682 | 0.272 | 0.562 | 0.997 | 0.284 | 
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)  | ResNet101 | 1056x384 | N | N | - | 0.330 | 0.396 | 0.702 | 0.272 | 0.534 | 0.932 | 0.251 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)    | ResNet101 | 1056x384 | N | N | Y | 0.333 | 0.399 | 0.735 | 0.275 | 0.559 | 0.899 | 0.205 |
| [FCOS3D](https://arxiv.org/pdf/2104.10956.pdf)  | ResNet101 | 1600x900 | Y | N | N | 0.343 | 0.415 | 0.725 | 0.263 | 0.422 | 1.292 | 0.153 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)    | ResNet101 | 1056x384 | Y | N | Y | 0.347 | 0.423 | 0.736 | 0.269 | 0.448 | 0.844 | 0.202 |
| [DETR3D](https://proceedings.mlr.press/v164/wang22b.html)  | ResNet101 | 1600x900 | Y | N | Y | 0.349 | 0.434 | 0.716 | 0.268 | 0.379 | 0.842 | 0.200 |
| [SpatialDETR](https://markus-enzweiler.de/downloads/publications/ECCV2022-spatial_detr.pdf)|ResNet101|-        | Y | N | N | 0.351 | 0.425 | 0.772 | 0.274 | 0.395 | 0.847 | 0.217 |
| [SimMOD](https://arxiv.org/pdf/2208.10035.pdf)  | ResNet101 | 1600x900 | N | N | - | 0.351 | 0.435 | 0.717 | 0.267 | 0.388 | 0.849 | 0.187 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)    | ResNet101 | 1408x512 | N | N | Y | 0.357 | 0.421 | 0.710 | 0.270 | 0.490 | 0.885 | 0.224 |
| [PolarDETR](https://arxiv.org/pdf/2206.10965.pdf) | ResNet101 | 1600x900 | - | N | - | 0.365 | 0.444 | 0.742 | 0.269 | 0.350 | 0.829 | 0.197 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)    | ResNet101 | 1408x512 | Y | N | Y | 0.366 | 0.441 | 0.717 | 0.267 | 0.412 | 0.834 | 0.190 |
| [SimMOD](https://arxiv.org/pdf/2208.10035.pdf)  | ResNet101 | 1600x900 | Y | N | - | 0.366 | 0.455 | 0.698 | 0.264 | 0.340 | 0.784 | 0.197 |
| [PGD](https://arxiv.org/pdf/2107.14160.pdf)     | ResNet101 | 1600x900 | N | N | N | 0.369 | 0.428 | 0.683 | 0.260 | 0.439 | 1.268 | 0.185 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)    | ResNet101 | 1600x900 | Y | N | Y | 0.370 | 0.442 | 0.711 | 0.267 | 0.383 | 0.865 | 0.201 |
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)| ResNet101 | 512x1408 | - | N | - | 0.376 | 0.408 | 0.659 | 0.267 | 0.543 | 1.059 | 0.335 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| ResNet101 | 1600x900 | Y | N | - | 0.396 | 0.458 | 0.700 | 0.269 | 0.375 | 0.839 | 0.245 |


### ResNet101 + temporal
| Method | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :----- | :-----:  |  :-----:   |    :---:        |   :---:  | :--: |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [PolarDETR-T](https://arxiv.org/pdf/2206.10965.pdf) | ResNet101 | 1600x900 | - | Y | - | 0.383 | 0.488 | 0.707 | 0.269 | 0.344 | 0.518 | 0.196 |
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)   | ResNet101 | 512x1408 | - | Y | - | 0.412 | 0.535 | 0.565 | 0.266 | 0.358 | 0.331 | 0.190 |
| [BEVFormer-S](https://arxiv.org/abs/2203.17270)|ResNet101  | -        | - | Y | - | 0.416 | 0.517 | 0.673 | 0.274 | 0.372 | 0.394 | 0.198 |


### Other Backbone
| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- |:-----:| :-----:  |  :-----: |:----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)     | Swin-T | 704x256  | N | - | 0.312 | 0.392 | 0.691 | 0.272 | 0.523 | 0.909 | 0.247 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)       | Swin-T | 512x1408 | N | - | 0.361 | 0.431 | 0.732 | 0.273 | 0.497 | 0.808 | 0.185 |
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)     | Swin-B | 1600x640 | N | - | 0.393 | 0.472 | 0.608 | 0.259 | 0.366 | 0.822 | 0.191 |
| [DETR3D](https://proceedings.mlr.press/v164/wang22b.html) | V2-99 | 1600x900 | N | - | 0.445 | 0.509 | 0.687 | 0.261 | 0.271 | 0.727 | 0.191 |
| [PolarDETR](https://arxiv.org/pdf/2206.10965.pdf)  | V2-99  | 1600x900 | N | - | 0.462 | 0.532 | 0.628 | 0.262 | 0.263 | 0.658 | 0.180 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| V2-99  | 1600x900 | Y | N | - | 0.500 | 0.562 | 0.583 | 0.262 | 0.247 | 0.601 | 0.193 |


### Other Backbone + temporal
| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- |:-----:| :-----:  |  :-----: |:----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDet4D](https://arxiv.org/abs/2203.17054)   | Swin-T | 704x256  | Y | - | 0.338 | 0.476 | 0.672 | 0.274 | 0.460 | 0.337 | 0.185 |
| [BEVDet4D](https://arxiv.org/abs/2203.17054)   | Swin-B | 1600x640 | Y | - | 0.421 | 0.545 | 0.579 | 0.258 | 0.329 | 0.301 | 0.191 |




## nuScenes Test Set
### ResNet101 
| Method | backbone | temporal | test time aug | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :----:  |     :-----:   |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [FCOS3D](https://arxiv.org/pdf/2104.10956.pdf)      | ResNet101 | N | Y | 0.358 | 0.428 | 0.690 | 0.249 | 0.452 | 1.434 | 0.124 |
| [SimMOD](https://arxiv.org/pdf/2208.10035.pdf)      | ResNet101 | N | - | 0.382 | 0.464 | 0.623 | 0.252 | 0.394 | 0.863 | 0.132 |
| [PGD](https://arxiv.org/pdf/2107.14160.pdf)         | ResNet101 | N | Y | 0.386 | 0.448 | 0.626 | 0.245 | 0.451 | 1.509 | 0.127 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)        | ResNet101 | N | N | 0.391 | 0.455 | 0.647 | 0.251 | 0.433 | 0.933 | 0.143 |
| [BEVFormer-S](https://arxiv.org/abs/2203.17270) | ResNet101 | N | - | 0.409 | 0.462 | 0.650 | 0.261 | 0.439 | 0.925 | 0.147 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| ResNet101  | N | - | 0.415 | 0.470 | 0.657 | 0.263 | 0.405 | 0.911 | 0.139 |
| [Graph-DETR3D](https://arxiv.org/abs/2204.11582)| ResNet101 | N | - | 0.418 | 0.472 | 0.668 | 0.250 | 0.440 | 0.876 | 0.139 |
| [SpatialDETR](https://markus-enzweiler.de/downloads/publications/ECCV2022-spatial_detr.pdf) | ResNet101 | N | - | 0.424 | 0.486 | 0.613 | 0.253 | 0.402 | 0.857 | 0.131 | 


### V2-99
| Method | backbone | temporal | test time aug | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :----:  |     :-----:   |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [DETR3D](https://proceedings.mlr.press/v164/wang22b.html)      | V2-99     | N | N | 0.412 | 0.479 | 0.641 | 0.255 | 0.394 | 0.845 | 0.133 |
| [SimMOD](https://arxiv.org/pdf/2208.10035.pdf)      | V2-99     | N | - | 0.417 | 0.494 | 0.570 | 0.248 | 0.387 | 0.813 | 0.126 |
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)      | V2-99     | N | - | 0.424 | 0.488 | 0.524 | 0.242 | 0.373 | 0.950 | 0.148 |
| [Graph-DETR3D](https://arxiv.org/abs/2204.11582)| V2-99     | N | - | 0.425 | 0.495 | 0.621 | 0.251 | 0.386 | 0.790 | 0.128 |
| [PolarDETR](https://arxiv.org/abs/2206.10965)   | V2-99     | N | - | 0.431 | 0.493 | 0.588 | 0.253 | 0.408 | 0.845 | 0.129 |
| [BEVFormer-S](https://arxiv.org/abs/2203.17270) | V2-99     | N | - | 0.435 | 0.495 | 0.589 | 0.254 | 0.402 | 0.842 | 0.131 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)        | V2-99     | N | - | 0.441 | 0.504 | 0.593 | 0.249 | 0.383 | 0.808 | 0.132 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| V2-99  | N | - | 0.455 | 0.503 | 0.592 | 0.258 | 0.389 | 0.870 | 0.132 |

### Other Backbone
| Method | backbone | temporal | test time aug | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :----:  |     :-----:   |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf)      | Swin-S    | N | N | 0.398 | 0.463 | 0.556 | 0.239 | 0.414 | 1.010 | 0.153 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)        | Swin-T    | N | N | 0.411 | 0.450 | 0.664 | 0.256 | 0.522 | 0.971 | 0.137 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)        | Swin-S    | N | N | 0.434 | 0.481 | 0.641 | 0.248 | 0.437 | 0.894 | 0.143 |
| [PETR](https://arxiv.org/pdf/2203.05625.pdf)        | Swin-B    | N | N | 0.445 | 0.483 | 0.627 | 0.249 | 0.449 | 0.927 | 0.141 |

### Temporal
| Method | backbone | temporal | test time aug | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :------- | :-----:  |  :----:  |     :-----:   |:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [BEVFormer](https://arxiv.org/abs/2203.17270)   | ResNet101 | Y | - | 0.445 | 0.535 | 0.631 | 0.257 | 0.405 | 0.435 | 0.143 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| ResNet101  | Y | - | 0.457 | 0.543 | 0.612 | 0.257 | 0.392 | 0.467 | 0.129 | 
| [BEVFormer](https://arxiv.org/abs/2203.17270)   | V2-99     | Y | - | 0.481 | 0.569 | 0.582 | 0.256 | 0.375 | 0.378 | 0.126 |
| [PETRv2](https://arxiv.org/pdf/2206.01256.pdf) | V2-99 | Y | N | 0.490 | 0.582 | 0.561 | 0.243 | 0.361 | 0.343 | 0.120 |
| [PolarFormer](https://arxiv.org/pdf/2206.15398.pdf)| V2-99  | Y | - | 0.493 | 0.572 | 0.556 | 0.256 | 0.364 | 0.440 | 0.127 |  
| [BEVDepth](https://arxiv.org/pdf/2206.10092v1.pdf)    | -         | Y | - | 0.503 | 0.600 | 0.445 | 0.245 | 0.378 | 0.320 | 0.126 |


  

   
