# Mesh_RCNN_3D
3D Object Detection and Reconstruction 
All the research is here - https://arxiv.org/abs/1906.02739

Mesh R-CNN is a system that improves 3D shape prediction. 
 It's an extension of the 2D instance segmentation system, Mask R-CNN. Mesh R-CNN adds a mesh prediction branch to Mask R-CNN. 
 This branch outputs meshes with different topological structures


# Installation Requirements
Detectron2 - Object Detection

PyTorch3D - 3D Reconstruction

# Running Experiments
- Pix3D
- ShapeNet

# Model Zoo - (Download Opensource Files available on their respective Github pages)
Pix3D - https://github.com/facebookresearch/meshrcnn/blob/main/datasets/pix3d/download_pix3d.sh

ShapeNet - https://github.com/facebookresearch/meshrcnn/blob/main/datasets/shapenet/download_shapenet.sh

# Example 
![input](https://user-images.githubusercontent.com/4369065/77708628-cda99d00-6f85-11ea-949a-5dad891005ee.jpg)
![segmentation](https://user-images.githubusercontent.com/4369065/77709133-52e18180-6f87-11ea-901a-0706c3d4e3a3.png)
![rendered_output](https://user-images.githubusercontent.com/4369065/77708647-df8b4000-6f85-11ea-8d5f-4ae62ea3bf07.png)
