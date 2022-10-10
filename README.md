# Awesome-BEV-Detection-Performance
Collect the Performance of 3D Object Detection Methods from Multi-View Camera Images (BEV Perception).


## nuScenes Val Set
| Method | backbone | resolution | FCOS3D Pretrain | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDet]     | ResNet50 | 256x704  | N | N | - | 0.298 | 0.379 | 0.725 | 0.279 | 0.589 | 0.860 | 0.245 |
| [BEVDet]     | ResNet50 | 1056x384 | N | N | - | 0.318 | 0.389 | 0.718 | 0.272 | 0.553 | 0.897 | 0.258 |
| [PETR]       | ResNet50 | 1056x384 | N | N | Y | 0.313 | 0.381 | 0.768 | 0.278 | 0.564 | 0.923 | 0.225 |
| [PETR]       | ResNet50 | 1408x512 | N | N | Y | 0.339 | 0.403 | 0.748 | 0.273 | 0.539 | 0.907 | 0.203 |
| [BEVDepth]   | ResNet50 | 256x704  | - | N | - | 0.315 | 0.367 | 0.702 | 0.271 | 0.621 | 1.042 | 0.315 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDepth]   | ResNet50 | 256x704  | - | Y | - | 0.351 | 0.475 | 0.639 | 0.267 | 0.479 | 0.428 | 0.198 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [FCOS3D]  | ResNet101 | 1600x900 | Y | N | N | 0.343 | 0.415 | 0.725 | 0.263 | 0.422 | 1.292 | 0.153 |
| [PGD]     | ResNet101 | 1600x900 | N | N | N | 0.369 | 0.428 | 0.683 | 0.260 | 0.439 | 1.268 | 0.185 |
| [BEVDet]  | ResNet101 | 704x256  | N | N | - | 0.302 | 0.381 | 0.722 | 0.269 | 0.543 | 0.900 | 0.269 |
| [BEVDet]  | ResNet101 | 1056x384 | N | N | - | 0.330 | 0.396 | 0.702 | 0.272 | 0.534 | 0.932 | 0.251 |
| [PETR]    | ResNet101 | 1056x384 | N | N | Y | 0.333 | 0.399 | 0.735 | 0.275 | 0.559 | 0.899 | 0.205 |
| [PETR]    | ResNet101 | 1408x512 | N | N | Y | 0.357 | 0.421 | 0.710 | 0.270 | 0.490 | 0.885 | 0.224 |
| [DETR3D]  | ResNet101 | 1600x900 | Y | N | Y | 0.349 | 0.434 | 0.716 | 0.268 | 0.379 | 0.842 | 0.200 |
| [PETR]    | ResNet101 | 1056x384 | Y | N | Y | 0.347 | 0.423 | 0.736 | 0.269 | 0.448 | 0.844 | 0.202 |
| [PETR]    | ResNet101 | 1408x512 | Y | N | Y | 0.366 | 0.441 | 0.717 | 0.267 | 0.412 | 0.834 | 0.190 |
| [PETR]    | ResNet101 | 1600x900 | Y | N | Y | 0.370 | 0.442 | 0.711 | 0.267 | 0.383 | 0.865 | 0.201 |
| [SimMOD]  | ResNet101 | 1600x900 | N | N | - | 0.351 | 0.435 | 0.717 | 0.267 | 0.388 | 0.849 | 0.187 |
| [SimMOD]  | ResNet101 | 1600x900 | Y | N | - | 0.366 | 0.455 | 0.698 | 0.264 | 0.340 | 0.784 | 0.197 |
| [BEVDepth]| ResNet101 | 256x704  | - | N | - | 0.320 | 0.381 | 0.682 | 0.272 | 0.562 | 0.997 | 0.284 | 
| [BEVDepth]| ResNet101 | 512x1408 | - | N | - | 0.376 | 0.408 | 0.659 | 0.267 | 0.543 | 1.059 | 0.335 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDepth]   | ResNet101 | 512x1408 | - | Y | - | 0.412 | 0.535 | 0.565 | 0.266 | 0.358 | 0.331 | 0.190 |
| [BEVFormer-S]|ResNet101  | -        | - | Y | - | 0.416 | 0.517 | 0.673 | 0.274 | 0.372 | 0.394 | 0.198 |


| Method | Venue | backbone | temporal | CBGS | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:-----:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDet]     | Swin-T | 704x256  | N | - | 0.312 | 0.392 | 0.691 | 0.272 | 0.523 | 0.909 | 0.247 |
| [BEVDet]     | Swin-B | 1600x640 | N | - | 0.393 | 0.472 | 0.608 | 0.259 | 0.366 | 0.822 | 0.191 |
| [PETR]       | Swin-T | 512x1408 | N | - | 0.361 | 0.431 | 0.732 | 0.273 | 0.497 | 0.808 | 0.185 | 
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| [BEVDet4D]   | Swin-T | 704x256  | Y | - | 0.338 | 0.476 | 0.672 | 0.274 | 0.460 | 0.337 | 0.185 |
| [BEVDet4D]   | Swin-B | 1600x640 | Y | - | 0.421 | 0.545 | 0.579 | 0.258 | 0.329 | 0.301 | 0.191 |




## nuScenes Test Set
| Method | backbone | temporal ｜ test time aug | mAP | NDS | ATE | ASE | AOE | AVE | AAE | 
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|
| [FCOS3D]      | ResNet101 | N | Y | 0.358 | 0.428 | 0.690 | 0.249 | 0.452 | 1.434 | 0.124 |
| [PGD]         | ResNet101 | N | Y | 0.386 | 0.448 | 0.626 | 0.245 | 0.451 | 1.509 | 0.127 |
| [PETR]        | ResNet101 | N | N | 0.391 | 0.455 | 0.647 | 0.251 | 0.433 | 0.933 | 0.143 |
| [BEVFormer-S] | ResNet101 | N | - | 0.409 | 0.462 | 0.650 | 0.261 | 0.439 | 0.925 | 0.147 |
| [Graph-DETR3D]| ResNet101 | N | - | 0.418 | 0.472 | 0.668 | 0.250 | 0.440 | 0.876 | 0.139 |
| [SimMOD]      | ResNet101 | N | - | 0.382 | 0.464 | 0.623 | 0.252 | 0.394 | 0.863 | 0.132 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|
| [DD3D]        | V2-99     | N | Y | 0.418 | 0.477 | 0.572 | 0.249 | 0.368 | 1.014 | 0.124 |
| [DETR3D]      | V2-99     | N | N | 0.412 | 0.479 | 0.641 | 0.255 | 0.394 | 0.845 | 0.133 |
| [BEVDet]      | V2-99     | N | - | 0.424 | 0.488 | 0.524 | 0.242 | 0.373 | 0.950 | 0.148 |
| [PolarDETR]   | V2-99     | N | - | 0.431 | 0.493 | 0.588 | 0.253 | 0.408 | 0.845 | 0.129 |
| [PETR]        | V2-99     | N | - | 0.441 | 0.504 | 0.593 | 0.249 | 0.383 | 0.808 | 0.132 |
| [BEVFormer-S] | V2-99     | N | - | 0.435 | 0.495 | 0.589 | 0.254 | 0.402 | 0.842 | 0.131 |
| [Graph-DETR3D]| V2-99     | N | - | 0.425 | 0.495 | 0.621 | 0.251 | 0.386 | 0.790 | 0.128 |
| [SimMOD]      | V2-99     | N | - | 0.417 | 0.494 | 0.570 | 0.248 | 0.387 | 0.813 | 0.126 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|
| [BEVDet]      | Swin-S    | N | N | 0.398 | 0.463 | 0.556 | 0.239 | 0.414 | 1.010 | 0.153 |
| [PETR]        | Swin-T    | N | N | 0.411 | 0.450 | 0.664 | 0.256 | 0.522 | 0.971 | 0.137 |
| [PETR]        | Swin-S    | N | N | 0.434 | 0.481 | 0.641 | 0.248 | 0.437 | 0.894 | 0.143 |
| [PETR]        | Swin-B    | N | N | 0.445 | 0.483 | 0.627 | 0.249 | 0.449 | 0.927 | 0.141 |
| :-----|:-----:|:-----:|:---:|:---:|:---:|:---:|:----:|:-----:|:-----:|:-----:|
| [BEVDepth]    | -         | Y | - | 0.503 | 0.600 | 0.445 | 0.245 | 0.378 | 0.320 | 0.126 |
| [BEVFormer]   | ResNet101 | Y | - | 0.445 | 0.535 | 0.631 | 0.257 | 0.405 | 0.435 | 0.143 |
| [BEVFormer]   | V2-99     | Y | - | 0.481 | 0.569 | 0.582 | 0.256 | 0.375 | 0.378 | 0.126 |

  

   
