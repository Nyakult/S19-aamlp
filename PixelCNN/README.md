# Using TensorFlow to Generate Images with PixelRNNs

This repo hosts the code associated with the O'Reilly article, ["Using Tensorflow to Generate Images with PixelRNNs: How to generate novel images using neural networks"](https://www.oreilly.com/ideas/using-tensorflow-to-generate-images-with-pixelrnns).

In this article, we walk through creating a generative model to produce realistic-looking images using recurrent neural networks in Tensorflow. Specifically, we use a PixelRNN architecture trained on MNIST to generate images that look like handwritten digits.

### Requirements

In order to run this notebook, you will need to install [TensorFlow v1.0](https://www.tensorflow.org/), [Jupyter](http://jupyter.org/), and [NumPy](http://www.numpy.org/).

The notebook also uses [TQDM](https://pypi.python.org/pypi/tqdm) to display nice progress bars during training.

There are two easy ways to install these libraries and their dependencies:

### How to use

1. Download and unzip [this entire repo from GitHub](https://github.com/Nyakult/S19-aamlp/tree/master/PixelCNN), either interactively, or by entering
    ```bash
    git clone https://github.com/Nyakult/S19-aamlp/tree/master/PixelCNN
    ```

2. Open the ipynb and follow the instruction
