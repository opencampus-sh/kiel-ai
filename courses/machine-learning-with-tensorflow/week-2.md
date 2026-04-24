# Week 2 - Introduction to PyTorch

### This week you will...

* get an introduction into PyTorch and how to build a model using the right PyTorch classes
* you will also learn how to train a model over several epochs and how non-linear activation functions increase the expressive power of neural networks, allowing them to learn non-linear relationships in the data
* the course material also includes a section how the shapes of the learnable parameters (weights and biases) of a PyTorch model translate into the mathematical expressions PyTorch applies under the hood

### Learning Resources

{% file src="../../.gitbook/assets/2026_04_23_Introduction to PyTorch.pdf" %}

* [Machine Learning Explained in 100 Seconds](https://www.youtube.com/watch?v=PeMlggyqz0Y) (Fireship, 2:30 min)
* [Backpropagation, intuitively | Deep Learning Chapter 3](https://www.youtube.com/watch?v=Ilg3gGewQ5U\&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi\&index=4) (3Blue1Brown, 13 min)\
  How the parameters of the model influence the prediction quality and how **Backpropagation** uses the gradients of the **Cost Function** (also known as the **Loss Function**) to update the weights and biases
* [What is a Loss Function? Understanding How AI Models Learn](https://www.youtube.com/watch?v=v_ueBW_5dLg) (IBM Technology, 10 min)\
  How **Loss Functions** are used to quantify predictions and guide model training and which **Loss Function** to choose based on the data and task (**Regression** vs. **Classification**) an hand
* [Validation data: How it works and why you need it](https://www.youtube.com/watch?v=NPWlj9G1Si8) (Galaxy Inferno Codes, 5:40 min)\
  Why we need **Training**, **Validation** and **Test** datasets and what **Overfittting** and **Data Leakage** are&#x20;

**Additional Resources (going beyond this week's topics)**&#x20;

* [Parameters vs Hyperparameters](https://www.youtube.com/watch?v=32tNAhQ8x7M) (Pankaj Kumar Porwal, 5:40 min)\
  Discusses the difference between learnable **Parameters** (weights and biases) and **Hyperparameters** that are not learned, but specified when defining the model or training

### Until next week you should... (⚠️ Section has not yet been updated)

{% hint style="info" %}
**IMPORTANT NOTE**

This section has **NOT** yet been updated! It will be updated shortly and you will get notified in the chat.
{% endhint %}

* Watch the following videos:
  * [Cross Validation](https://alan-turing-institute.github.io/Intro-to-transparent-ML-course/05-cross-val-bootstrap/cross-validation.html) (StatQuest Video, 6 min)
    * The video is **mandatory**
    * The accompanying notebook is **optional**
  * [Bias and Variance (Overfitting)](https://www.youtube.com/watch?v=EuBBz3bI-aA) (StatQuest, 7 min)&#x20;
  * [Model Evaluation (Confusion Matrix)](https://www.youtube.com/live/Kdsp6soqA7o) (StatQuest, 7 min)
  * [Callback Functions in TensorFlow](https://www.youtube.com/watch?v=wkwtIeq9Ljo) (DigitalSreeni, 10 min)
* Decide on a project for the course and form groups
* Complete the two assignments in the following notebooks:
  * [Assignment Notebook 1](https://colab.research.google.com/github/opencampus-sh/course-material/blob/main/machine-learning-with-tensorflow/week-02/Week2_Notebook1_Cats_and_Dogs.ipynb)
  * [Assignment Notebook 2](https://colab.research.google.com/github/opencampus-sh/course-material/blob/main/machine-learning-with-tensorflow/week-02/Week2_Notebook2_CIFAR-10.ipynb)

