# Week 4 – Versioning with Git (Part 2) and Feature Engineering

**Estimated workload:** about 11.3 hours (session 1.75 h, videos and readings 1.5 h, tasks 8 h)

**Question of the week (from Anna):** _What does Anna know the day before that could predict tomorrow’s sales?_

**Canvas focus:** blocks 6 and 7 (Known in advance, Data decisions) · **Skills:** `leakage`, `/to-analysis-plan`

### This week you will ...

* collaborate in a team repository: push, pull, resolve conflicts, and commit only what passes the checks,
* encode categorical variables with one-hot encoding, and explain embeddings as learned dense representations,
* distinguish features known in advance from features only known afterwards (a first look at data leakage),
* apply feature engineering: binning, joining categories, interaction effects.

### Until next week you should ...

* [x] **Create the three features** your team chose and add them to the data preparation folder of your repository.<br>
* [x] **Analyse the time series** of the six product groups: moving averages, percent change, seasonality.<br>
* [x] **Create a [Kaggle](https://www.kaggle.com/) account** and review the [course competition](https://www.kaggle.com/t/d832497c95d744de915ad9eb80ad9ed6).<br>
* [x] **Check on EduHub** that your team is confirmed and every member is listed as an author.<br>
* [x] **Agree on checks before code:** run `/to-analysis-plan` and confirm the checkpoints. For each check, name a source of truth that the pipeline does not compute itself, and replace any check that would pass by construction.<br>
* [x] **Watch the videos and do the readings** listed below (≈ 73 minutes).

{% hint style="info" %}
**Deliverable for Anna:** three findings about trends and seasonality, each with one chart and one sentence on what it means for production planning.
{% endhint %}

### Videos and materials

| Lesson / material | Source | Min |
| --- | --- | --- |
| [DateTimes](https://learn.deeplearning.ai/specializations/data-analytics/lesson/yt06e/datetimes) | Python for Data Analytics, M5 | 5 |
| [Using DateTimes as Indices](https://learn.deeplearning.ai/specializations/data-analytics/lesson/xtibp/using-datetimes-as-indices) | Python for Data Analytics, M5 | 3 |
| [Moving Averages](https://learn.deeplearning.ai/specializations/data-analytics/lesson/n5vs5/moving-average) | Python for Data Analytics, M5 | 5 |
| [Percent Change](https://learn.deeplearning.ai/specializations/data-analytics/lesson/icu5f/percent-change) | Python for Data Analytics, M5 | 4 |
| [Segmentation](https://learn.deeplearning.ai/specializations/data-analytics/lesson/n5s9q/segmentation) | Python for Data Analytics, M5 | 5 |
| [Encoding categorical data](https://learn.deeplearning.ai/specializations/data-analytics/lesson/htxtl/encoding-categorical-data) | Python for Data Analytics, M4 | 3 |
| [Modeling with categorical data](https://learn.deeplearning.ai/specializations/data-analytics/lesson/r7nt2/modeling-with-categorical-data) | Python for Data Analytics, M4 | 5 |
| [Categorical data: one-hot encoding](https://developers.google.com/machine-learning/crash-course/categorical-data/one-hot-encoding) (reading) | Google ML Crash Course | 15 |
| [Embeddings](https://developers.google.com/machine-learning/crash-course/embeddings), first pages (reading) | Google ML Crash Course | 15 |
| [Word Representation](https://learn.deeplearning.ai/specializations/deep-learning/lesson/pqt4m/word-representation) | Deep Learning Specialization, C5 W2 | 10 |
| [Embedding Matrix](https://learn.deeplearning.ai/specializations/deep-learning/lesson/r4twj/embedding-matrix) | Deep Learning Specialization, C5 W2 | 3 |
| **Total** | | **73** |

**Self-study:** lesson 4 of [Learn it in seven lessons](https://github.com/steffen74/agentic-data-science/blob/main/docs/lessons.md) covers `/to-analysis-plan`.

### Optional

* Spec-Driven Development course: Project replanning (6 min), The second feature phase (6 min), The MVP (3 min).
* Deep Learning Specialization, C5 W2: Using Word Embeddings (9 min), Properties of Word Embeddings (11 min).
* The first two lessons of the short course “Embedding Models: from Architecture to Implementation” (DeepLearning.AI).
