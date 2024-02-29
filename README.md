# Image Classification using CNNs on CIFAR10 Dataset

## Project Description

This project aims to classify images from the CIFAR10 dataset using Convolutional Neural Networks (CNNs). The CIFAR10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. The classes are as followings:
* `airplane`                                        
* `automobile`                                        
* `bird`                                       
* `cat`                                        
* `deer`                                        
* `dog`                                        
* `frog`                                        
* `horse`                                        
* `ship`                                        
* `truck`

## Model Architecture
The model architecture is based on a Convolutional Neural Network (CNN) which is particularly well-suited for image classification tasks. The CNN includes convolutional layers, pooling layers, dropout layers, and fully connected layers.

## Results

The Convolutional Neural Network (CNN) model, as implemented in the provided code, demonstrates a well-structured architecture for image classification tasks. Trained on the dataset for 10 epochs with a batch size of 128, the model achieves a commendable accuracy of 74.79%. The model comprises several convolutional layers followed by batch normalization and max-pooling operations, aiding in feature extraction and dimensionality reduction. Dropout layers are strategically inserted to prevent overfitting during training. The final layers consist of densely connected layers with appropriate activation functions, concluding with a softmax activation for multi-class classification. The achieved accuracy of 74% on the CIFAR-10 dataset underscores the effectiveness of this CNN architecture in tackling image classification tasks.

## License
For more details visit https://www.cs.toronto.edu/~kriz/cifar.html 
