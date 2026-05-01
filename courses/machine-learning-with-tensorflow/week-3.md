# Week 3 - Data Management and Neural Network Components

### This week you will...

* Set up a custom `Dataset` and `DataLoader` to load, transform, and batch data.
* Split the complete dataset into **Subsets for training, validation, and testing** and witness the impact of **Distribution Shift**.
* Explore why **Architectural Bias** in **Convolutional Neural Networks** acts as **Automated Feature Engineering** by learning **Convolution Filters** (or Kernels), allowing them to be more parameter-efficient compared to standard **Multi-Layer Perceptrons**.
* Understand what **Loss Surfaces** are and how **Gradient Descent** and batch size influence model optimization.

### Learning Resources

{% file src="../../.gitbook/assets/2026_04_30_Data Management and Neural Network Components.pdf" %}

#### **Optional Resourcesthat**

* [MIT 6.S191: Introduction to Deep Learning](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)\
  This is a full course and absolutely optional. \
  We recommed it as a resource **after completing DeepLearning.AI's** **PyTorch for Deep Learning**\
  (feel free to use it at your dicretion, if you want another perspective on e.g., CNNs.)
* [3Blue1Brown's Neural Network Playlist](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) (thanks for sharing!)<br>

#### **Additional Resources (going beyond this week's topics)**

* [Cross Validation](https://alan-turing-institute.github.io/Intro-to-transparent-ML-course/05-cross-val-bootstrap/cross-validation.html) (StatQuest Video, 6 min)\
  How to split the available data into subsets for training and testing and how **Cross Validation** is used to process different splits to evaluate your model's performance
*   [Bias and Variance (Overfitting)](https://www.youtube.com/watch?v=EuBBz3bI-aA) (StatQuest, 7 min)\
    The video discusses the **Bias-Variance Tradeoff** and explains why we want to design and train models that are at the sweet spot between

    * **minimizing Bias (Underfitting)**\
      Error resulting from overly simple assumptions (the model misses the underlying pattern)
    * **minimizing Variance (Overfitting)**\
      Error resulting from the model being too sensitive to the training data. \
      High variance causes the model to "memorize" noise instead of learning the underlying distribution such that it fails to generalize on unseen data

    **Mini-Batch Gradient Descent** helps us navigate this tradeoff by introducing just enough noise to prevent the high variance (overfitting) typically seen in **Full-Batch Gradient Descent**

### Until next week you should...

* Complete [module 3](https://learn.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate/lesson/2ffyly/transformers) of the second course "PyTorch: Techniques and Ecosystem Tools"
* Set up a repository for your project following the instructions given [here](https://opencampus.gitbook.io/opencampus-machine-learning-program/projects/requirements)
* Conduct a literature review according to the instructions given [here](https://github.com/opencampus-sh/ml-project-template/blob/main/0_LiteratureReview/INSTRUCTIONS.md)
* Document your findings on the literature review according to the instructions of above
* Complete the assignment in the following notebook:
  * [Assignment Notebook](https://colab.research.google.com/github/opencampus-sh/course-material/blob/main/applied-machine-learning/week-03/Week3_AG_News_Assignment.ipynb)
