# Glossary

&#x20;A field of computer science that aims to make computers exhibit intelligent human-like behavior. There are many approaches to achieving this goal, including machine learning and deep learning.During your study of Machine Learning you will come across many different terms such as artificial intelligence, machine learning, neural network, and deep learning. But what do these key words actually mean?

Below we will give a brief intro to all the different words in the AI lingua:

**Artificial Intelligence:**

* **Machine Learning:** A set of related techniques in which computers are trained with examples to perform a particular task rather than by explicitly programming them.
* **Neural Network:** A construct in Machine Learning inspired by the network of neurons (nerve cells) in the human brain. Neural networks are the core of deep learning!
* **Deep Learning:** A subfield of machine learning that uses multi-layered neural networks. Often, “machine learning” and “deep learning” are used interchangeably.

So you now know how to distinguish the big terms in AI. Below we introduce you to all other important key words:

_Use Ctrl + f to search for a specific word_

* **Feature:** The input(s) to our model (e.g. value of a pixel, price of a house, sex of the person, etc.)
* **Examples:** An input/output pair used for training
* **Labels:** The output of the model
* **Layer:** A collection of nodes(single neurons) connected together within a neural network.
* **Model:** The representation of your neural network
* **Dense and Fully Connected (FC):** Each node in one layer is connected to each node in the previous layer.
* **Weights and biases:** The internal variables of model
* **Loss:** The discrepancy between the desired output and the actual output
* **MSE:** Mean squared error, a type of loss function that counts a small number of large discrepancies as worse than a large number of small ones.
* **Gradient Descent:** An algorithm that changes the internal variables a bit at a time to gradually reduce the loss function.
* **Optimizer:** A specific implementation of the gradient descent algorithm. (There are many algorithms for this. In this course we will only use the “Adam” Optimizer, which stands for _ADAptive with Momentum_. It is considered the best-practice optimizer.)
* **Learning rate:** The “step size” for loss improvement during gradient descent.
* **Batch:** The set of examples used during training of the neural network
* **Epoch:** A full pass over the entire training dataset
* **Forward pass:** The computation of output values from input
* **Backward pass (backpropagation):** The calculation of internal variable adjustments according to the optimizer algorithm, starting from the output layer and working back through each layer to the input.
* **Flattening:** The process of converting a 2d image into 1d vector
* **ReLU:** An activation function that allows a model to solve nonlinear problems
* **Softmax:** A function that provides probabilities for each possible output class
* **Classification:** A machine learning model used for distinguishing among two or more output categories
* **Training Set:** The data used for training the neural network.
* **Test set:** The data used for testing the final performance of our neural network.
* **CNNs:** Convolutional neural network. That is, a network which has at least one convolutional layer. A typical CNN also includes other types of layers, such as pooling layers and dense layers.
* **Convolution:** The process of applying a kernel (filter) to an image
* **Kernel / filter:** A matrix which is smaller than the input, used to transform the input into chunks
* **Padding:** Adding pixels of some value, usually 0, around the input image
* **Pooling** The process of reducing the size of an image through downsampling.There are several types of pooling layers. For example, average pooling converts many values into a single value by taking the average. However, maxpooling is the most common.
* **Maxpooling**: A pooling process in which many values are converted into a single value by taking the maximum value from among them.
* **Stride:** the number of pixels to slide the kernel (filter) across the image.
* **Downsampling:** The act of reducing the size of an image
* **Early Stopping**: In this method, we track the loss on the validation set during the training phase and use it to determine when to stop training such that the model is accurate but not overfitting.
* **Image Augmentation**: Artificially boosting the number of images in our training set by applying random image transformations to the existing images in the training set.
* **Dropout**: Removing a random selection of a fixed number of neurons in a neural network during training.
* **Transfer Learning**: A technique that reuses a model that was created by machine learning experts and that has already been trained on a large dataset. When performing transfer learning we must always change the last layer of the pre-trained model so that it has the same number of classes that we have in the dataset we are working with.
* **Freezing Parameters**: Setting the variables of a pre-trained model to non-trainable. By freezing the parameters, we will ensure that only the variables of the last classification layer get trained, while the variables from the other layers of the pre-trained model are kept the same.
