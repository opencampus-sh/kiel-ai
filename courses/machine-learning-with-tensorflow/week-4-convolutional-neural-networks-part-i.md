# Week 4 - Working with Text Using Hugging Face

### This week you will...

* Build an end-to-end NLP pipeline that classifies AG News articles into World, Sports, Business, or Sci/Tech.
* Use a pretrained DistilBERT tokenizer to convert raw text into model-ready inputs such as token IDs, attention masks, and labels.
* Implement a custom PyTorch `Dataset`, dynamic padding with a data collator, and `DataLoader`s for efficient training and validation.
* Fine-tune DistilBERT using partial layer freezing, tune key hyperparameters, evaluate performance, and save the trained model safely.

### Slides

{% file src="../../.gitbook/assets/251113_CNN_Part_I.pdf" %}

### Additional Learning Resources

* [What is NLP](https://www.youtube.com/watch?v=fLvJ8VdHLA0) (9 min)
* [NLP Zero to Hero Part 1](https://www.youtube.com/watch?v=fNxaJsNG3-s\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=1) (5 min)
* [NLP Zero to Hero Part 2](https://www.youtube.com/watch?v=r9QjkdSJZ2g\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=2) (6 min)
* [NLP Zero to Hero Part 3](https://www.youtube.com/watch?v=Y_hzMnRXjhI\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=3) (8 min)
* [Embeddings explained](https://www.youtube.com/watch?v=wgfSDrqYMJ4\&t) (8 min)
* [ML with RNNs (NLP Zero to Hero - Part 4)](https://www.youtube.com/watch?v=OuYtk9Ymut4\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=4) \[6 Min]
* [LSTM for NLP (NLP Zero to Hero - Part 5)](https://www.youtube.com/watch?v=A9QVYOBjZdY\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=5) \[5 Min]
* [Training an AI to create poetry (NLP Zero to Hero - Part 6)](https://www.youtube.com/watch?v=ZMudJXhsUpY\&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S\&index=6) \[8 Min]

### Until next week you should...

* Prepare questions for your projects for the feedback sessions
* Already get started on the new content
