# Digit-Recognizer by CNN

MNIST (“Modified National Institute of Standards and Technology”) is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

## Data
Data set  contain gray-scale images of hand-drawn digits, from zero through nine

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

Scaling of the images is done.

###  Dataset  is split into Training, Testing, and Validation Sets
x_train shape: (55000, 28, 28)
55000 train samples
10000 test samples
5000 validation samples

# Model creation 

4 layers of convolution and 4 layers  of pooling
Dropout is used to reduce the overfitting of neural networks.
The dense layer is used to classify images based on output from convolutional layers.
Model is traines on 100 epochs

# Result
#### Model accuracy is 94%. The model is performming pretty well.
 
 
