# EIP4


# Assignment 1

## score-- [0.038846943631432485, 0.9929]

## Convolution
Convolution is the process of convolving two matrix, highlight the important feature and reduce the size. For eg In 5x5 image, we can use 3x3 filter for the convolution
and that filters extract important feature like horizontal line, vertical line etc from the actual image.

## Filters/Kernels
These are matrix of nxn where <b>1<=n<=size of image</b>, usually it is 3x3. It act as a feature extractor from an image or feature map generator. It extracts lots of important feature from image, like horizontal line, vertical line, gradients etc.

## Epochs

Epochs means how many times our network has run through our dataset.

## 1x1 Convolution
It convolves with 1 pixel of image or previous layer, until it goes through all the pixel. It combines the feature which are contextually linked to each other and helps in reducing the number of channels.

## 3x3 Convolution
It looks at 9 pixel of image at once. for eg our filter of 3*3 convolves with image until it went through all the pixel. It helps in extracting feature and reducing the size of the image but not channels.

## Receptive Field
Receptive field basically contains the information about the object in an image.
Receptive field is of two type: <br>
a)Local Receptive Field- It gives the information about the pixels convolved in the nearest layer <br>
b)Global Receptive field- It gives the information about the how many pixels we have convolved. It actually contains the main information or features of the image or we can also say it contains the information related to the object.

## Activation Function

Activation function can be seen as booster to the network, it helps in discarding lot of irrelevant information and fasten the calculation. We can also say it as a squasher, for eg- In relu any number less than equal to 0 is 0, while nummber greter than 0 is the number itself. In this way relu helps in discarding lots of irrelevant information.

## Feature Maps

When we convolve a filter with an image or previous layer, it gives out some important information i.e called feature map. Filters are the feature map extractor.

