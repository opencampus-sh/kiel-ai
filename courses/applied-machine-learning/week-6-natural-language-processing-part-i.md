# Week 7 - Natural Language Processing, Part I

### This week you will...

* get an understanding for the importance of tokenization of a text when training a neural network for texts, for example, to do a sentiment analysis. Tokenization is the process of converting the text into numeric values, with a number representing a word or a character.
* learn about embeddings, where the text tokens are mapped as vectors in a high dimensional space. With embeddings and labelled examples, these vectors can then be tuned so that words with similar meaning will have a similar direction in the vector space. This will begin the process of training a neural network to understand sentiment in text -- and you'll begin by looking at movie reviews, training a neural network on texts that are labelled 'positive' or 'negative' and determining which words in a sentence drive those meanings.

### Learning Resources

{% file src="../../.gitbook/assets/241205_NLP in TensorFlow-Part-I.pdf" %}

* Week 1 and 2 of the course [Natural Language Processing in TensorFlow](https://www.coursera.org/learn/natural-language-processing-tensorflow)

### Until next week you should...

* watch [ML with RNNs (NLP Zero to Hero - Part 4)](https://www.youtube.com/watch?v=OuYtk9Ymut4\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=4) \[6 Min]
* watch [LSTM for NLP (NLP Zero to Hero - Part 5)](https://www.youtube.com/watch?v=A9QVYOBjZdY\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=5) \[5 Min]
* watch [Training an AI to create poetry (NLP Zero to Hero - Part 6)](https://www.youtube.com/watch?v=ZMudJXhsUpY\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=6) \[8 Min]<br>
* complete [this notebook](https://colab.research.google.com/github/opencampus-sh/course-material/blob/main/machine-learning-with-tensorflow/week-06/Week6_Notebook_Yoda-Corpus.ipynb) to generate text in the unique speaking style of Star Wars character Master Yoda.<br>
* watch the videos "[Why human-level performance?](https://www.youtube.com/watch?v=J3HHOwcrkK8\&list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b\&index=8)", "[Avoidable bias](https://www.youtube.com/watch?v=J3HHOwcrkK8\&list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b\&index=8)", and "[Understanding human-level performance](https://www.youtube.com/watch?v=J3HHOwcrkK8\&list=PLkDaE6sCZn6E7jZ9sN_xHwSHOdjUxUW_b\&index=8)" to help you evaluating and improving your model
* consider a baseline model or a baseline comparison for your project task according to the instructions given [here](https://github.com/opencampus-sh/ml-project-template/blob/main/1_DatasetCharacteristics/INSTRUCTIONS.md)
* document the evaluation results of your baseline model and the used metric(s) in your project repository
