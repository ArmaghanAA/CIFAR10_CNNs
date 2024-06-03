The `CIFAR-10` dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class.

In this project, the Convolutional Neural Netowork has been used to classify CiFAR10 dataset. The CNN diagram is:

![](https://github.com/ArmaghanAA/CIFAR10_CNNs/blob/main/003_images/CiFAR-10%20CNN_sequential_model.png)


The CNN contains 4 convolution layers, 2 pooling layers, 4 dropout layers, 1 felattening layer and 3 fully connected layers. The diagram shows all information about filter sizes and units. it should be mentioned that convolution layers take in a channel of dimension 3 since the images are RGB. 'RelU' activation function is used for hidden layers and 'softmax' is applied in the output layer.
This project contains two parts:

*   CNN model
*   CNN model with Augmentation

 In order to improve the result (78%), data augmentation is applied which is resulted in 82% accuracy.
