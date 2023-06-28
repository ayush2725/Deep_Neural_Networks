Convolution Operation

# Padding 

### What is it? ###
It's adding some extra elements (usually 0) around the borders of the data structure before applying the convolutional operation. 

### Why? ###
* By multiple convolutional operations, the image size shrinks and in a very deep neural network, the image size will be considerably small which will create problems in training and tuning the model
*  Pixels are not evenly used, the pixels at center get more filters than the one at corners which can result in loss of information at the borders

### Types of Padding ###
* valid: Convolutional operation with no padding
*  same: Convolutional operation in which the input and output dimensions are the same


# Residual Networks (ResNet)

### What is it? ###
It's a Deep Neural Neural Network that uses "skip connection", every 2 layers, the input of the first layer is directly fed to the second layer.

### Why is it special? ###
* Skip connections provides shortcuts for gradient to flow (backpropogation) which helps fix the diminishing gradient problem, so even when training very deep neura networks, the performance is not heavily affected by the size of neural network
* They converge faster than other deep neural networks
