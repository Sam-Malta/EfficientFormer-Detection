# EfficientFormer Detection

This project is a deep learning model for object detection based on Mask R-CNN and EfficientFormer as a backbone.
It is planned to deploy this model on a Jetson for the First Robotics Competition.


# EfficientFormer

EfficientFormer is a deep learning model for object detection using the EfficientFormer architecture created by researchers at Snap Research and Northeastern. The model's goal was to be fast and efficient while bringing the high accuracy of other Vision Transformers, making it suitable for real-time applications on resource-constrained (edge) hardware such as the 

### Basis
EfficientFormer is based on the Vision Transformer (ViT) architecture, which has shown rapid progress in computer vision tasks. However, ViT-based models are generally slower than lightweight convolutional networks due to their massive number of parameters and attention mechanism. Recent efforts to reduce the computation complexity of ViT through network architecture search or hybrid design with MobileNet block have not been able to achieve satisfactory inference speed.

### Solution
To make Vision Transformers (ViT) faster and more efficient for real-time applications on mobile devices, the authors of the paper introduced a new design paradigm. This involved using a type of transformer that is more consistent in size and doesn't use MobileNet blocks, and then making the models smaller and faster by removing unnecessary parts. 

## Citation


Li, Y., Yuan, G., Wen, Y., Hu, J., Evangelidis, G., Tulyakov, S., Wang, Y., & Ren, J. (2022). EfficientFormer: Vision Transformers at MobileNet Speed. arXiv preprint arXiv:2206.01191. [Link](https://doi.org/10.48550/arXiv.2206.01191)
