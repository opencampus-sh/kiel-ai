# Week 8 – Neural Networks

**Estimated workload:** about 13.8 hours (session 1.75 h, videos and exercises 2 h, tasks 10 h)

**Question of the week (from Anna):** _Is a neural network worth the extra complexity compared with the linear model?_

**Canvas focus:** block 9 (Experiments) · **Skills:** `/implement-experiment`, `debug-training`

### This week you will ...

* name the main frameworks (TensorFlow/Keras, PyTorch, Hugging Face Transformers) and their roles,
* prepare data for a neural network, and train a first network with training and validation loss curves,
* weigh accuracy against interpretability and maintenance effort when recommending a model,
* optionally: replace one-hot inputs with an embedding layer and compare the results.

### Until next week you should ...

* [x] **Examine all model variables** for missing and implausible values.<br>
* [x] **Encode all categorical features** correctly, and remove rows with missing values for a first clean run.<br>
* [x] **Improve your neural network** and keep the loss curves. If it does not learn as expected, work through `debug-training` step by step.<br>
* [x] **Watch the videos and do the exercise** listed below (≈ 1.7 hours).

{% hint style="info" %}
**Deliverable for the data team:** a short comparison table in your README: baseline, linear model and neural network, with the MAPE overall and per product group.
{% endhint %}

### Videos and materials

| Lesson / material | Source | Min |
| --- | --- | --- |
| [Dropout layers](https://www.youtube.com/watch?v=ARq74QuavAo) | YouTube | 7 |
| [Normalizing inputs](https://www.youtube.com/watch?v=FDCfw-YqWTE) | YouTube | 5 |
| [Diagnosing bias and variance](https://learn.deeplearning.ai/specializations/machine-learning/lesson/y39ou/diagnosing-bias-and-variance) | Advanced Learning Algorithms, W3 | 11 |
| [Bias/variance and neural networks](https://learn.deeplearning.ai/specializations/machine-learning/lesson/svfir/bias-variance-and-neural-networks) | Advanced Learning Algorithms, W3 | 10 |
| [Error analysis](https://learn.deeplearning.ai/specializations/machine-learning/lesson/hvdzc/error-analysis) | Advanced Learning Algorithms, W3 | 8 |
| [Dealing with Missing Data in Python](https://campus.datacamp.com/courses/dealing-with-missing-data-in-python/), chapter 1 (interactive) | DataCamp | 60 |
| **Total** | | **101** |

**Example code:** [data preparation for a neural network](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/08_neural_networks/neural_net_data_preparation.ipynb), [estimating a neural network](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/08_neural_networks/neural_net_estimation.ipynb) and [the same with dropout](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/08_neural_networks/neural_net_estimation_with_dropout.ipynb).

### Optional

* **Stretch task:** use a Keras embedding layer for weekday and product group, compare the MAPE with one-hot encoding, and plot the learned weekday embeddings.
* PyTorch Fundamentals, Modules 1–2 (from the PyTorch for Deep Learning certificate), if you plan to continue with the course “Applied Machine Learning”.
* Advanced Learning Algorithms, W3: Evaluating a model (10 min), Model selection and training/cross validation/test sets (13 min), Learning curves (11 min).
