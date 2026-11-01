# Week 1 – Introduction to Data Science

**Estimated workload:** about 6.5 hours (session 1.75 h, videos 1.7 h, tasks 3 h)

**Question of the week (from Anna):** _Should the bakery start selling its seasonal bread (product group 6) in October or only in November?_

**Canvas focus:** blocks 1–4 (Problem) · **Skills:** `/setup-ds-project`, `/grill-question`

### This week you will ...

* distinguish data science, machine learning, AI and AI agents, and relate them to everyday examples,
* get to know the course structure, the flipped classroom format, the project and our client Anna,
* translate a real-life question into blocks 1–4 of the [Agentic Data Science Canvas](https://github.com/steffen74/agentic-data-science/tree/main/canvas),
* use a coding agent to import data, compute descriptive statistics and run a first significance test.

### Until next week you should ...

* [x] **Set up your practice repository:** run `/setup-ds-project` in your clone of the [template repository](https://github.com/opencampus-sh/repo-template-intro-to-data-science-and-ml).<br>
* [x] **Sharpen Anna’s question before you code:** run `/grill-question` and type Anna’s question right after the command, for example\
  `/grill-question Our client Anna asks: should the bakery start selling its seasonal bread (product group 6) in October or only in November?`\
  Answer the agent’s questions until blocks 1–4 of `CANVAS.md` are filled. Disagree with at least one of the agent’s recommended answers, and say why.<br>
* [x] **Answer the question with the data:** use [`umsatzdaten_gekuerzt.csv`](https://github.com/opencampus-sh/intro-to-data-science-and-ml/tree/main/data/bakery) to find out when the seasonal bread was sold in past years, compare the average daily sales in October and November, and test whether they differ significantly.<br>
* [x] **Check before you conclude:** let the agent generate the code, then ask it to explain each step and check the results for plausibility. What can the data tell Anna, and what not? (For example: on which October days was the bread actually sold?)<br>
* [x] **Watch the videos** listed below (≈ 69 minutes) and post your questions about them in the Element course room by the day before the next session.

{% hint style="info" %}
**Deliverable for Anna:** a three-sentence answer with one supporting number and a clear recommendation. Bring it to the next session; we discuss the answers in class.
{% endhint %}

### Videos and materials

| Lesson / material | Source | Min |
| --- | --- | --- |
| [Adding Features](https://learn.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant/lesson/zzhtb/adding-features) | Claude Code course | 17 |
| [Testing, Error Debugging and Code Refactoring](https://learn.deeplearning.ai/courses/claude-code-a-highly-agentic-coding-assistant/lesson/33kzc/testing%2C-error-debugging-and-code-refactoring) | Claude Code course | 12 |
| [Beyond lists](https://learn.deeplearning.ai/specializations/data-analytics/lesson/jrorg/beyond-lists) | Python for Data Analytics, M2 | 3 |
| [Importing modules](https://learn.deeplearning.ai/specializations/data-analytics/lesson/lhqs2/importing-modules) | Python for Data Analytics, M2 | 3 |
| [Pandas](https://learn.deeplearning.ai/specializations/data-analytics/lesson/oxc1j/pandas) | Python for Data Analytics, M2 | 2 |
| [Reading CSV into Python](https://learn.deeplearning.ai/specializations/data-analytics/lesson/lfhe9/reading-csv-into-python) | Python for Data Analytics, M2 | 4 |
| [DataFrames](https://learn.deeplearning.ai/specializations/data-analytics/lesson/zuw7l/dataframes) | Python for Data Analytics, M2 | 4 |
| [Attributes and methods](https://learn.deeplearning.ai/specializations/data-analytics/lesson/s745h/attributes-and-methods) | Python for Data Analytics, M2 | 2 |
| [Selecting columns](https://learn.deeplearning.ai/specializations/data-analytics/lesson/bqn2c/selecting-columns) | Python for Data Analytics, M2 | 4 |
| [Counts, sums, & histograms](https://learn.deeplearning.ai/specializations/data-analytics/lesson/rol4w/counts%2C-sums%2C-%26-histograms) | Python for Data Analytics, M2 | 3 |
| [Confidence intervals](https://learn.deeplearning.ai/specializations/data-analytics/lesson/hy1rp/confidence-intervals) | Python for Data Analytics, M4 | 6 |
| [One-sample t-tests](https://learn.deeplearning.ai/specializations/data-analytics/lesson/idzac/one-sample-t-tests) | Python for Data Analytics, M4 | 5 |
| [Two-sample t-tests](https://learn.deeplearning.ai/specializations/data-analytics/lesson/yi6xo/two-sample-t-tests) | Python for Data Analytics, M4 | 4 |
| **Total** | | **69** |

**Example code:** [comparing average temperatures in July and May](https://github.com/opencampus-sh/intro-to-data-science-and-ml/blob/main/01_introduction/temperature_comparison_july_may.ipynb) (import, descriptive statistics and a t-test).

**Self-study:** lessons 1 and 2 of [Learn it in seven lessons](https://github.com/steffen74/agentic-data-science/blob/main/docs/lessons.md) explain the canvas and `/grill-question` step by step.

### Optional

* The practice notebooks of Python for Data Analytics, Module 2: “Practice with DataFrames” and “Dictionaries and NumPy arrays” (≈ 40 min).
* Continue the Python track (see [Preparation](preparation.md#optional-python-track)).
