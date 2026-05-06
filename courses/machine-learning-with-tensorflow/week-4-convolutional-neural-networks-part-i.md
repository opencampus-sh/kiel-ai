# Week 4 - Working with Text Using Hugging Face

### This week you will...

* Build an end-to-end NLP pipeline that classifies AG News articles into World, Sports, Business, or Sci/Tech.
* Use a pretrained DistilBERT tokenizer to convert raw text into model-ready inputs such as token IDs, attention masks, and labels.
* Implement a custom PyTorch `Dataset`, dynamic padding with a data collator, and `DataLoader`s for efficient training and validation.
* Fine-tune DistilBERT using partial layer freezing, tune key hyperparameters, evaluate performance, and save the trained model safely.

### Slides

{% file src="../../.gitbook/assets/251113_CNN_Part_I.pdf" %}

### Learning Resources

* [Neural Networks Part 8: Image Classification with Convolutional Neural Networks (CNNs) ](https://www.youtube.com/watch?v=HGwBXDKFk9I\&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1\&index=15)(StatQuest with Josh Starmer, 15 min)
* [C4W1L04 Padding](https://www.youtube.com/watch?v=smHa2442Ah4\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=5) (DeepLearningAI, 9:50 min)
* [C4W2L10 Data Augmentation](https://www.youtube.com/watch?v=JI8saFjK84o\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=22) (DeepLearningAI, 9:30 min)
* [TensorFlow Tutorial 4 - Convolutional Neural Networks with Sequential and Functional API](https://www.youtube.com/watch?v=WAciKiDP2bo\&list=PLhhyoLH6IjfxVOdVC1P1L5z5azs0XjMsb\&index=5) (Aladdin Persson, first 10 min)
* [TensorFlow Tutorial 18 - Custom Dataset for Images](https://www.youtube.com/watch?v=q7ZuZ8ZOErE) (Aladdin Persson, first 7 min)
* [Data Augmentation - Deep Learning with Tensorflow | Ep. 19](https://www.youtube.com/watch?v=yke3zUGgQ-w) (Kody Simpson, 23 min)

### Until next week you should...

* Investigate the characteristics of your project's dataset according to the instructions given [here](https://github.com/opencampus-sh/ml-project-template/blob/main/1_DatasetCharacteristics/INSTRUCTIONS.md)
* Document your findings on the dataset characteristics according to the instructions of above
