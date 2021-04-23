# Convolutional_Neural_Network_MNIST
**Convolutional neural network classifier for MNIST handwritten digits.**


## Model Performance

The model achieved 98.67% accuracy.

<kbd><img height="600" src="/confusion_matrix.png"></kbd>

## Model Architecture

![](/model_architecture.png)

## Requirements

<pre>
 Pandas                                Seaborn                                NumPy                          
 PyTorch                               Matplotlib                             scikit-learn        
                                                                 
</pre> 

## Filter kernels and feature map visualization of the first convolutional block
*Input Image:*
<p align="center">
<img width="500" height="500" src="/Project_Image.png">
</p>   


*Kernels of the first convolutional layer:*
<img align="center" src="/Filter_Kernels_CL1.png">


*First convolutional layer feature maps:*
<img align="center" src="/Feature_Maps_CL1.png">


*First convolutional layer activated feature maps:*
<img align="center" src="/Activated_Feature_Maps_CL1.png">


*First convolutional layer pooled feature maps:*
<img align="center" src="/Pooled_Feature_Maps_CL1.png">
