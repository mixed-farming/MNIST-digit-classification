# MNIST-digit-classification

## Project: Recognizing handwritten digits
- We will discover the MNIST handwritten digit recognition problem and we will develop a deep learning model in Python using the Keras API with TensorFLow.
- The MNIST dataset is a collection of handwritten digits from 0-9. It consists of 70,000 labeled 28x28 pixel grayscale images of hand-written digits. The dataset is split into 60,000 training images and 10,000 test images. There are 10 classes (one for each of the 10 digits). The task at hand is to train a model using the 60,000 training images and subsequently test its classification accuracy on the 10,000 test images. <br> ![sample dataset](https://user-images.githubusercontent.com/94393300/209102991-d0f297a8-1999-4cf1-8c52-2cee4ab66bd1.png)
- Every image is of size 28 X 28 pixels. <br> ![sample image](https://user-images.githubusercontent.com/94393300/209103039-6e0ee4e6-2bbc-4e0c-a24d-d9e1ee983e0a.png)
- The model is 2 layer (hidden layers) sequential fully connected neural network as depicted below. <br> ![1_15](https://user-images.githubusercontent.com/94393300/209107358-959e3c92-3604-4e67-af74-4ebdc24a4d44.png)

## Libraries used:
- Tensorflow
- Keras
- Numpy
- Matplotlib

## Evaluation:
The model gets loss a of 0.0497 and an accuracy of 98.55% while evaluating on the test set. If you don't have a GPU powered machine it might take a little longer, you can try reducing the epochs (iterative steps) to reduce computation.

## Reference:
- Coursera <br>
Course ID: https://coursera.org/verify/Y47Q79THGXNC
