# Classifying Images with CNN:

This project aims to build a Convolutional Neural Network (CNN) that will be able to classify images that consists of clothing articles. These images are primarily taken from the Zalando Research Dataset. Generally, this project will go through creating an image-classification model, cross-validating it and then explore methods to improve on the model. 

## Breakdown of this Project:
- Image-Feature Extration
- CNN:
    - Network Topology
    - Convolutional Layers and Filters
    - Max Pooling Layers
    - Flattening
    - Fully-connected Layers and output
- Building the CNN model with KERAS:
    - Train using the Zalando research dataset
    - Classify the images

## Dataset:

The Zalando Research data obtained for this project can be found from: https://github.com/zalandoresearch/fashion-mnist.
## Sanpshot:

Diagram of an example CNN model:
- Source:https://www.mathworks.com/help/deeplearning/ug/introduction-to-convolutional-neural-networks.html

![CNN architecture 2](https://github.com/ylee9107/CNN_ClassifyingImages/blob/master/CNN%20Architecture%20Images/CNN%20architecture%202.png)

Diagram of the CNN model used:

![CNN_model_2](https://github.com/ylee9107/CNN_ClassifyingImages/blob/master/CNN_model_2.png)

## Required Libraries:

1. Pandas
2. Numpy
3. Matplotlib
4. OS
5. SYS
6. IPyhon (Jupyter notebook image display)
7. Keras
8. PlaidML (for AMD GPU only)
9. PIL
10. mnist_reader
11. Pydot
12. Seaborn
13. Tensorflow


## Summary:

This project has been a good one, where I was able to revise what I had learnt about CNN and its internal functions. The project also covered aspects such as extracting features from the dataset images, build a CNN model and applying to classify 10 classes of clothing articles. After which, the model performance would be evaluated and improved upon by introducing regularisation techniques to overcome the issue of overfitting. 

