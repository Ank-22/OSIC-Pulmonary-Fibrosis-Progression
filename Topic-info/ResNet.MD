# ResNet
``` This markdown will help you understand what ResNet and provide you with the link of the referance, plus if possible then where and how to implement the ResNet in your project ``` 
ResNet is One of the best deep neural network for computer vision.

ResNet, is short for residual networks. It is classic neural network used as a backbone for many computer vision task. This model was winner of ImageNet challenge in 2015. The fundamental breakthrough with ResNet was it allowed us to train extremely deep neural networks with 150+layers successfully. Prior to ResNet training very deep neural networks was difficult due to the problem of vanishing gradients.

AlexNet, the winner of ImageNet 2012 and the model that apparently kick started the focus on deep learning had only 8 convolutional layers, the VGG network had 19 and Inception or GoogleNet had 22 layers and ResNet 152 had 152 layers. In this blog we will code a ResNet-50 that is a smaller version of ResNet 152 and frequently used as a starting point for transfer learning.