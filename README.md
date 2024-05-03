# Knowledge Distillation-Based Lightweight Mask RCNN
This project was inspired by [Mask RCNN](https://github.com/matterport/Mask_RCNN/tree/master). This is a lightweight version of Mask R-CNN on Python 3, Keras, and TensorFlow. It utilizes a lightweight Feature Pyramid Network (LFPN) with a ResNet18 backbone. 

# Abstract
Depthwise Separable Convolutions was utilized to reduce the size of FPN. Additionally, Knowledge Distillation (KD) was applied to enhance the performance of the lightweight model. As a result, the proposed model size was reduced to 46% of the standard one, making it suitable for resource-constrained environments.

This project includes:  
  * Source code of lightweight Mask RCNN with lightweight FPN and ResNet18
  * Source code of KD of the backbone network
  * Training code for custom dataset or MS COCO  
  * Evaluation of models (mAP and mIoU)
# Instuction
