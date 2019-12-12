# keras-examples

Image vision examples using machine learning, including

 - inpainting
 - superresolution
 - deblurring
 
 All examples delivered as jupyter notebook and running on vanilla keras (with both plaidml/theano and tensorflow/google colab as backend).

## results
(1. degraded image, 2. neural net output, 3. ground truth)

#### inpainting
![alt text](https://github.com/BenjaminWegener/keras-examples/raw/master/inpainting.png "inpainting result")

#### superresolution
![alt text](https://github.com/BenjaminWegener/keras-examples/raw/master/superresolution.png "superresolution result")

#### deblurring
![alt text](https://github.com/BenjaminWegener/keras-examples/raw/master/deblurring.png "deblurring result")

## to run...
...just upload to google/colab OR locally call
`git clone https://github.com/BenjaminWegener/Keras-examples`

## references
- channel attention mechanism [[paper]](https://arxiv.org/abs/1807.02758)
- residual in residual architecture [[paper]](https://arxiv.org/abs/1505.04597)
- subpixel convolution / pixelshuffle [[paper]](https://arxiv.org/abs/1609.05158)
- running on [tensorflow/google colab](https://colab.research.google.com/) AND on [plaidml](https://www.intel.ai/plaidml/)
- using the famous [Set14](https://www.google.com/search?q=set14) dataset ONLY (with heavy augmentation) - no validation needed
