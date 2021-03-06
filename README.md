[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JasonManesis/Convolutional-Neural-Network-Classifier-MNIST/blob/main/CNN_MNIST_PyTorch_VISUALS.ipynb)

# Convolutional Neural Network - MNIST Dataset
**Convolutional neural network classifier for MNIST handwritten digits.**

## Model Architecture

![](/model_architecture.png)

## Model Performance

The model achieved 98.67% accuracy.

Confusion Matrix:
<p align="center">
<img width="500" height="500" src="/confusion_matrix.png">
</p>   


## Filter kernels and feature map visualization of the first convolutional block:

*Input Image:*
<p align="center">
<img width="400" height="400" src="/Project_Image.png">
</p>   


*Kernels of the first convolutional layer:*
<img align="center" src="/Filter_Kernels_CL1.png">


*First convolutional layer feature maps:*
<img align="center" src="/Feature_Maps_CL1.png">


*First convolutional layer activated feature maps:*
<img align="center" src="/Activated_Feature_Maps_CL1.png">


*First convolutional layer pooled feature maps:*
<img align="center" src="/Pooled_Feature_Maps_CL1.png">

## Requirements

<pre>
 Pandas                                Seaborn                                NumPy                          
 PyTorch                               Matplotlib                             scikit-learn        
                                                                 
</pre> 
