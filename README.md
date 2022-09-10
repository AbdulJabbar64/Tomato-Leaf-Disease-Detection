# Tomato-Leaf-Disease-Detection
The data has different types of diseases for tomato leaves. Here goes the list:

* Tomatomosaicvirus
* Target_Spot
* Bacterial_spot
* TomatoYellowLeafCurlVirus
* Late_blight
* Leaf_Mold
* Early_blight
* Spidermites Two-spottedspider_mite
* Tomato___healthy
* Septorialeafspot
# Accuracy
* Best Validation Accuracy: 98.5%
* Best Validation Accuracy: 96.7%

# There are Two Architecture in this Project
- VGG16
- ResNet152V2
# What Is Transfer Learning?
Transfer learning is one of the handiest tools to use if you’re working on any sort of image classification problem. But what exactly is it? How can you implement it? How accurate is it? This will go in-depth into transfer learning and show you how to apply it using the Keras library.

Note that a prerequisite to learning transfer learning is to have basic knowledge of convolutional neural networks (CNN) since image classification calls for using this algorithm.

CNNs make use of convolution layers that utilize filters to help recognize the important features in an image. These features, of which there are many, help distinguish a particular image. Whenever you train a CNN on a bunch of images, all these features are learned internally. In addition, when you use a deep CNN, the number of parameters that are being learned - also called weights - can be in the millions. Therefore, when numerous parameters need to be learned, it takes time. And this is where transfer learning helps.

# VGG16:

A convolutional neural network is also known as a ConvNet, which is a kind of artificial neural network. A convolutional neural network has an input layer, an output layer, and various hidden layers. VGG16 is a type of CNN (Convolutional Neural Network) that is considered to be one of the best computer vision models to date. The creators of this model evaluated the networks and increased the depth using an architecture with very small (3 × 3) convolution filters, which showed a significant improvement on the prior-art configurations. They pushed the depth to 16–19 weight layers making it approx — 138 trainable parameters.

# What is VGG16 used for
VGG16 is object detection and classification algorithm which is able to classify 1000 images of 1000 different categories with 92.7% accuracy. It is one of the popular algorithms for image classification and is easy to use with transfer learning.

# VGG16 Architecture
![](https://miro.medium.com/max/875/0*0M8CobXpNwFDCmOQ)
![](https://miro.medium.com/max/875/0*6VP81rFoLWp10FcG)

# RestNet50v2 
In 2012 at the LSVRC2012 classification contest AlexNet won the the first price, After that **ResNet** was the most interesting thing that happened to the computer vision and the deep learning world.

Because of the framework that **ResNets** presented it was made possible to train ultra deep neural networks and by that i mean that i network can contain hundreds or thousands of layers and still achieve great performance

**ResNet-50** is a convolutional neural network that is 50 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals

