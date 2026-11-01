# Week 5 – Time Series Analysis and Introduction to Machine Learning

**Estimated workload:** about 8.3 hours (session 1.75 h, videos and readings 1.5 h, tasks 5 h)

**Question of the week (from Anna):** _How would Anna know whether to trust a forecast before she uses it?_

**Canvas focus:** blocks 4 and 8 (Success, Checks) · **Skills:** `data-checks`, `/review-results`, `/to-experiments`, `/implement-experiment`

### This week you will ...

* identify trend, seasonality and autocorrelation, and use differencing and lag variables,
* describe the machine learning procedure: training, validation and test data, parameters and hyperparameters,
* split time series data without leakage, and verify agent-generated analysis code with explicit checks instead of reading every line.

### Until next week you should ...

* [x] **Download the Kaggle test dataset** and merge it with your data.<br>
* [x] **Build experiment card 1, the end-to-end baseline,** with `/implement-experiment`: watch the new checks go red before they go green, and read the log entry it writes. Commit only what passes the checks.<br>
* [x] **Watch the videos and do the readings** listed below (≈ 68 minutes).

{% hint style="info" %}
**Deliverable for the data team:** a short paragraph in your README that explains to a technical reader how your data is split and which checks guarantee that the forecast is evaluated fairly.
{% endhint %}

### Videos and materials

| Lesson / material | Source | Min |
| --- | --- | --- |
| [What is linear regression?](https://learn.deeplearning.ai/specializations/data-analytics/lesson/d211v/what-is-linear-regression%3F) | Python for Data Analytics, M4 | 6 |
| [Choosing an independent variable](https://learn.deeplearning.ai/specializations/data-analytics/lesson/iz6c1/choosing-an-independent-variable) | Python for Data Analytics, M4 | 3 |
| [Training the model](https://learn.deeplearning.ai/specializations/data-analytics/lesson/qqstl/training-the-model) | Python for Data Analytics, M4 | 5 |
| [Interpreting the output of a regression model](https://learn.deeplearning.ai/specializations/data-analytics/lesson/mqma9/interpreting-the-output-of-a-regression-model) | Python for Data Analytics, M4 | 4 |
| [Prediction](https://learn.deeplearning.ai/specializations/data-analytics/lesson/wjniq/prediction) | Python for Data Analytics, M4 | 4 |
| [Multiple linear regression](https://learn.deeplearning.ai/specializations/data-analytics/lesson/syrdh/multiple-linear-regression) | Python for Data Analytics, M4 | 3 |
| [Training a multiple linear regression model](https://learn.deeplearning.ai/specializations/data-analytics/lesson/t3lwv/training-a-multiple-linear-regression-model) | Python for Data Analytics, M4 | 4 |
| [Interpreting multiple linear regression](https://learn.deeplearning.ai/specializations/data-analytics/lesson/pxhvm/interpreting-multiple-linear-regression) | Python for Data Analytics, M4 | 4 |
| [Prediction: Multiple Linear Regression](https://learn.deeplearning.ai/specializations/data-analytics/lesson/ck910/prediction%3A-multiple-linear-regression) | Python for Data Analytics, M4 | 2 |
| [Evaluating your model](https://learn.deeplearning.ai/specializations/data-analytics/lesson/f3dsf/evaluating-your-model) | Python for Data Analytics, M4 | 5 |
| [LLMs for model iteration](https://learn.deeplearning.ai/specializations/data-analytics/lesson/y4eqr/llms-for-model-iteration) | Python for Data Analytics, M4 | 6 |
| [The linear regression process](https://learn.deeplearning.ai/specializations/data-analytics/lesson/mcybm/the-linear-regression-process) | Python for Data Analytics, M4 | 2 |
| [Nonlinear transformations](https://learn.deeplearning.ai/specializations/data-analytics/lesson/ohxav/nonlinear-transformations) (reading) | Python for Data Analytics, M4 | 10 |
| [Interaction features](https://learn.deeplearning.ai/specializations/data-analytics/lesson/xuh1n/interaction-features) (reading) | Python for Data Analytics, M4 | 10 |
| **Total** | | **68** |

**Example code:** [time series predictions](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/05_time_series/time_series_predictions.ipynb).

**Self-study:** lesson 5 of [Learn it in seven lessons](https://github.com/steffen74/agentic-data-science/blob/main/docs/lessons.md) covers the end-to-end baseline.

### Optional

* The practice lab “London housing prices – Regression with categorical data” (≈ 30 min).
