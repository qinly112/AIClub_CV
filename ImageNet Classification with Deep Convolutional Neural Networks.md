# ImageNet Classification with Deep Convolutional Neural Networks



## architecture of the network:	![achitecture](D:\qly\AI Club\AlexNet architecture.PNG)

- 8 layers: 5 convolutional and three fully-connected
- use 2 GPUs



## activate function:

ReLU: $f(x)=max(0,x)$

- ReLU is a non-saturating activate function while sigmoid function and tanh function are saturating function. 

- sacturating model: parameters$\geq$n  (squeeze the input)

- saturating: output is close to 0 or 1



## Normalization:

Local Response Normalization

![](D:\qly\AI Club\Normalization.PNG)



## Pooling:

Overlapping Pooling

- prevent overfitting


## Reducing Overfitting:

1. ### Data Augmentation

   - generating image translations and horizontal reflections

     extract random patches

   - altering the intensities of the RGB channels

2. ### Dropout:

   - setting to zero the output of each hidden neuron with probability 0.5

   - not contribute to the forward pass and not participate in back-propagation

​	

## Other Details:

- use stochastic gradient descent 