

## 3D Capsule Networks for Point Sets
Created by <a href="http://campar.in.tum.de/Main/YongHengZhao" target="_blank">Yongheng Zhao</a>, <a href="http://campar.in.tum.de/Main/TolgaBirdal" target="_blank">Tolga Birdal</a>, <a href="http://campar.in.tum.de/Main/HaowenDeng" target="_blank">Haowen Deng</a>, <a href="http://campar.in.tum.de/Main/FedericoTombari" target="_blank">Federico Tombari </a> from TUM.

This repository contains the implementation of our [CVPR 2019 paper *3D Point Capsule Networks*](https://arxiv.org/abs/1812.10775). In particular, we release code for training and testing a 3D-PointCapsNet network for classification, reconstruction, part interpolation and extraction of 3d local descriptors as well as the pre-trained models for quickly replicating our results. 

For an intuitive explanation of the 3D point capsule networks, please check out [Tolga's CVPR tutorial](https://www.youtube.com/watch?v=fbhbuH9mUx0).

![](https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/teaser.png )

##### Part Interpolation 
<a href="url"><img src="https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/airplane_wing_interpolation.gif"  height="210" width="260" ></a>
<a href="url"><img src="https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/chair2.gif" height="220" width="145" ></a>
<a href="url"><img src="https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/tableleg2.gif" height="110" width="228" ></a>
<a href="url"><img src="https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/table_surface2.gif" height="173" width="179" ></a>

##### Distribution of capsule reconstruction 
![](https://github.com/yongheng1991/3D-point-capsule-networks/blob/master/docs/spatial_attention.png )

#### Abstract
In this paper, we propose 3D point capsule networks, an auto-encoder designed to process sparse 3D point clouds while preserving spatial arrangements of the input data. 3D capsule networks arise as a direct consequence of our novel unified 3D auto-encoder formulation. Their dynamic routing scheme and the peculiar 2D latent space deployed by our approach bring in improvements for several common point cloud-related tasks, such as object classification, object reconstruction and part segmentation as substantiated by our extensive evaluations. Moreover, it enables new applications such as part interpolation and replacement.

### Citations
If you find our work useful in your research, please consider citing:
		  
		  @inproceedings{zhao20193d, 
			author={Zhao, Yongheng and Birdal, Tolga and Deng, Haowen and Tombari, Federico}, 
			booktitle={Conference on Computer Vision and Pattern Recognition (CVPR)}, 
			title={3D Point 
			Capsule Networks}, 
			organizer={IEEE/CVF},
			year={2019}
		  }
   
### License
Our repositories are released under the MIT license (see LICENSE file for details).

### References
Our source codes are based upon many helpful packages and libraries. The chamfer distance package is based on <a href="https://github.com/fxia22/pointGAN/tree/master/nndistance" target="_blank">nndistance</a>. The necessary modifications have been done to this repository in order to run it with PyTorch 1.0.0. The capsule layer is based upon and modified from <a href="https://github.com/higgsfield/Capsule-Network-Tutorial" target="_blank">Capsule-Network-Tutorial</a>. Our capsule decoder is based upon the decoder of <a href="https://github.com/ThibaultGROUEIX/AtlasNet" target="_blank">AtlasNet</a>.
