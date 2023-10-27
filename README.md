# EfficientFormer Detection

This project is a deep learning model for object detection based on Mask R-CNN and EfficientFormer as a backbone.
It is planned to deploy this model on a Jetson for the First Robotics Competition.


# EfficientFormer

EfficientFormer is a deep learning model for object detection using the EfficientFormer architecture created by researchers at Snap Research and Northeastern. The model's goal was to be fast and efficient while bringing the high accuracy of other Vision Transformers, making it suitable for real-time applications on resource-constrained (edge) hardware such as the 

### Basis
EfficientFormer is based on the Vision Transformer (ViT) architecture, which has shown rapid progress in computer vision tasks. However, ViT-based models are generally slower than lightweight convolutional networks due to their massive number of parameters and attention mechanism. Recent efforts to reduce the computation complexity of ViT through network architecture search or hybrid design with MobileNet block have not been able to achieve satisfactory inference speed.

### Solution
To address this challenge, the authors of the paper introduced a dimension-consistent pure transformer (without MobileNet blocks) as a design paradigm and performed latency-driven slimming to get a series of final models dubbed EfficientFormer. Extensive experiments show the superiority of EfficientFormer in performance and speed on mobile devices. 

Overall, EfficientFormer represents a significant advancement in the field of computer vision and has the potential to enable a wide range of real-time applications on mobile devices. 