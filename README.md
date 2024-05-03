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
  * Remember to follow the training steps below:  
![plot](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/images/instruction.png)
  * [train.ipynb](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/samples/train.ipynb) is the main function of training and fine-tuning.
  * [outputs.ipynb](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/MRCNN_KD/outputs.ipynb) illustrates the KD pipeline and the model separation.
  * [inspect_model_new.ipynb](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/samples/coco/inspect_model_new.ipynb) provides the model evaluation, including the critera of mAP and mIoU.
  * [model_new.py](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/mrcnn/model_new.py): the standard model implementation.
  * [model_final.py](https://github.com/sdsle0123/KD_Based_Mask-RCNN/blob/main/mrcnn/model_final.py): the lightweight version implementation.
