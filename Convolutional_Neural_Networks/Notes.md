Convolution Operation

Padding

Why?
1. By multiple convolutional operations, the image size shrinks and in a very deep neural network, the image size will be considerably small which will create problems in training and tuning the model
2. Pixels are not evenly used, the pixels at center get more filters than the one at corners which can result in loss of information

Types of Padding
1. valid: Convolutional operation with no padding
2. same: Convolutional operation in which the input and output dimensions are the same
