Convolution Operation

# Padding 

### What? ###
It's adding some extra elements (usually 0) around the borders of the data structure before applying the convolutional operation. 

## Why? ###
* By multiple convolutional operations, the image size shrinks and in a very deep neural network, the image size will be considerably small which will create problems in training and tuning the model
*  Pixels are not evenly used, the pixels at center get more filters than the one at corners which can result in loss of information at the borders

### Types of Padding ###
* valid: Convolutional operation with no padding
*  same: Convolutional operation in which the input and output dimensions are the same
