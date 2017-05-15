## Project: Image Classification

### Project Overview

In this project, we will classify images from the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The dataset consists of airplanes, dogs, cats, and other objects. The dataset will need to be preprocessed, then train a convolutional neural network on all the samples. We will normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, we will see the predictions on the sample images.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- urllib.request
- os.path
- tqdm
- tarfile
- pickle
- [numpy](http://www.numpy.org/)
- [tensorflow](https://www.tensorflow.org/)

### Run

In a terminal or command window, navigate to the top-level project directory `image_classification/` (that contains this README) and run one of the following commands:

```bash
ipython notebook image_classification.ipynb
```
or
```bash
jupyter notebook image_classification.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.
