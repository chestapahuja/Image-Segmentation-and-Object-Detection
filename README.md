# Image-Segmentation-and-Object-Detection
Image Segmentation and Object Detection using Isometric Learning
Though training deep convolutional networks is inherently difficult, but designing architecture for
them is also not an easy task. Initialisation, normalization, residual connections, etc. are indispensable
components of modern ConvNets, one can not imagine to train them without these components and
achieve good performance. This project work aims to show that deep ConvNets can achieve good performance without using normalization nor skip connections. This can be achieved with the help of isometric learning where we enforce the convolution kernels to be near isometric during initialization and
training, we also use SReLU non-linear activation to maintain isometry in the network. In addition to
the ISONet and R-ISONet that were proposed in the original work, we created ISO-UNet which can be
used for semantic image segmentation task.Our contributions:

•	Proposed and implemented ISO-UNet, improved accuracy(mean IoU) by 0.85% (compared to UNet)  on Brain MRI  for image segmentation task using Isometric Learning- Training very deep neural networks without normalization or skip connections
•	First public implementation of R-ISOnet + Faster RCNN framework based on ‘Deep Isometric Learning for Visual Recognition’ by Haozhi Qi et. al. for object detection on COCO dataset, R-ISOnet performs at par with ResNet backbone using ImageNet pre-trained weights
