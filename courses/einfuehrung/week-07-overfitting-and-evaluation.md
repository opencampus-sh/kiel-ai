# Week 7 – Overfitting and Model Evaluation

**Estimated workload:** about 11.6 hours (session 1.75 h, videos 1.8 h, tasks 8 h)

**Question of the week (from Anna):** _Which forecast errors hurt the bakery more: leftover bread or sold-out shelves?_

**Canvas focus:** block 4 revisited (Success) · **Skills:** `/review-results`, `diagnose-surprise`

### This week you will ...

* recognise overfitting and counter it with regularization,
* choose a quality criterion (MAE, MAPE, RMSE, R²) that reflects the client’s real costs,
* explain batches, steps and epochs and the basic structure of a neural network.

### Until next week you should ...

* [x] **Extend your dataset** with additional variables relevant for the sales forecast.<br>
* [x] **Keep testing** your baseline model’s predictions on Kaggle.<br>
* [x] **Plant a leak and see whether it is caught:** on a copy of your branch, shuffle the data before splitting (or add a feature that is only known afterwards). Check whether `/review-results` or `diagnose-surprise` catches it, then delete the copy.<br>
* [x] **Watch the videos** listed below (≈ 73 minutes).

{% hint style="info" %}
**Deliverable for Anna:** one paragraph explaining which error measure you use and why it matches her costs.
{% endhint %}

### Videos and materials

| Lesson / material | Source | Min |
| --- | --- | --- |
| [Welcome!](https://learn.deeplearning.ai/specializations/machine-learning/lesson/uyfti/welcome!) | Advanced Learning Algorithms, W1 | 2 |
| [Demand Prediction](https://learn.deeplearning.ai/specializations/machine-learning/lesson/pe1tg/demand-prediction) | Advanced Learning Algorithms, W1 | 16 |
| [Inference in Code](https://learn.deeplearning.ai/specializations/machine-learning/lesson/v1elo/inference-in-code) | Advanced Learning Algorithms, W1 | 6 |
| [Data in TensorFlow](https://learn.deeplearning.ai/specializations/machine-learning/lesson/l30eb/data-in-tensorflow) | Advanced Learning Algorithms, W1 | 11 |
| [Building a neural network](https://learn.deeplearning.ai/specializations/machine-learning/lesson/pwzk4/building-a-neural-network) | Advanced Learning Algorithms, W1 | 8 |
| [TensorFlow implementation](https://learn.deeplearning.ai/specializations/machine-learning/lesson/xb6c8/tensorflow-implementation) | Advanced Learning Algorithms, W2 | 3 |
| [Training Details](https://learn.deeplearning.ai/specializations/machine-learning/lesson/p9qte/training-details) | Advanced Learning Algorithms, W2 | 13 |
| [Choosing activation functions](https://learn.deeplearning.ai/specializations/machine-learning/lesson/v1drv/choosing-activation-functions) | Advanced Learning Algorithms, W2 | 8 |
| [Advanced Optimization (Adam)](https://learn.deeplearning.ai/specializations/machine-learning/lesson/qj0t1/advanced-optimization) | Advanced Learning Algorithms, W2 | 6 |
| **Total** | | **73** |

**Example code:** [the effect of overfitting and regularization](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/07_overfitting/overfitting.ipynb). To try out small neural networks in the browser: [TensorFlow Playground](https://playground.tensorflow.org/).

**Self-study:** lesson 6 of [Learn it in seven lessons](https://github.com/steffen74/agentic-data-science/blob/main/docs/lessons.md) covers `/review-results` and `diagnose-surprise`.

### Optional

* Advanced Learning Algorithms, W1: Neurons and the brain (10 min), Example: Recognizing Images (6 min).
* Supervised ML, W2: Feature scaling, parts 1 and 2 (13 min), as preparation for normalization.
