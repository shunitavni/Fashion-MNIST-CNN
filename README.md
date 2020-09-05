# Fashion-MNIST-CNN

**CNN over Fasion MNIST**

In this notebook I build a convolutional network.
I train it over the Fasion MNIST data, which is a collection of 28X28 black and white images, classified into 10 different classes of clothing items.
For more information about Fashion MNIST you may refer to: https://github.com/zalandoresearch/fashion-mnist 

**following architecture:**

* Convolution with 10 3X3 filters
* Relu
* Max pool with 2X2
* Convolution with 5 3X3 filters
* Relu
* Convolution with 16 3X3 filters
* Relu
* Max pool with 2X2
* Liner, output size 128
* Relu
* Liner, output size 64
* Relu
* Liner, output size 10
