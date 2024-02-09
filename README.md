# Project Name
> Outline a brief description of your project.


## Table of Contents
* What's Skin Cancer Detection
* Python and its libraries

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In skin cancer test, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process is manual and takes significant amount of time to arrive at a conclusion of the biopsy test. The main aim is to reduce this time of examination to help patients and doctors. The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Dataset
- The dataset has 2686 files belonging to 9 classes

## CNN Approach
- Rescalling Layer - To rescale an input in the [0, 255] range to be in the [0, 1] range.
- Convolutional Layer - Convolutional layers apply a convolution operation to the input, passing the result to the next layer. A convolution converts all the pixels in its receptive field into a single value. 
- Pooling Layer - Pooling layers are used to reduce the dimensions of the feature maps. Thus, it reduces the number of parameters to learn and the amount of computation performed in the network. 
- Dropout Layer - The Dropout layer randomly sets input units to 0 with a frequency of rate at each step during training time, which helps prevent overfitting.
- Flatten Layer - Flattening is converting the data into a 1-dimensional array for inputting it to the next layer. 
- Dense Layer - The dense layer is a neural network layer that is connected deeply, which means each neuron in the dense layer receives input from all neurons of its previous layer.
- Activation Function(ReLU) - The rectified linear activation function overcomes the vanishing gradient problem, allowing models to learn faster and perform better.
- Activation Function(Softmax) - The softmax function is used as the activation function in the output layer of neural network for classification
  
## Conclusions
- Solve Overfitting issue using Augmentor and Class Imbalance
- Training and Validation accuracy increases by the above

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Contact
Created by [@ghoshjyotirmoy] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
