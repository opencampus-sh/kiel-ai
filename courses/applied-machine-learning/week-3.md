# Week 3 - Introduction to TensorFlow,Part II

### This week you will...

* see how to improve the basic neural network for computer vision you learned last week.
* learn about what happens if your data is more complex; if the images are larger, or if the features are not always in the same place, and how to handle such issues.

### Learning Resources

{% file src="../../.gitbook/assets/250508_Introduction-to-TensorFlow-Part-II (1).pdf" %}

* [Cross Validation](https://alan-turing-institute.github.io/Intro-to-transparent-ML-course/05-cross-val-bootstrap/cross-validation.html) (StatQuest Video, 6 min)
* [Bias and Variance (Overfitting)](https://www.youtube.com/watch?v=EuBBz3bI-aA) (StatQuest, 7 min)&#x20;
* [Model Evaluation (Confusion Matrix)](https://www.youtube.com/live/Kdsp6soqA7o) (StatQuest, 7 min)
* [Callback Functions in TensorFlow](https://www.youtube.com/watch?v=wkwtIeq9Ljo) (DigitalSreeni, 10 min)

### Until next week you should...

* Watch the following videos:
  * Theory:
    * [Neural Networks Part 8: Image Classification with Convolutional Neural Networks (CNNs) ](https://www.youtube.com/watch?v=HGwBXDKFk9I\&list=PLblh5JKOoLUIxGDQs4LFFD--41Vzf-ME1\&index=15)(StatQuest with Josh Starmer, 15 min)
    * [C4W1L04 Padding](https://www.youtube.com/watch?v=smHa2442Ah4\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=5) (DeepLearningAI, 9:50 min)
    * [C4W2L10 Data Augmentation](https://www.youtube.com/watch?v=JI8saFjK84o\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=22) (DeepLearningAI, 9:30 min)
  * Practice:
    * [TensorFlow Tutorial 4 - Convolutional Neural Networks with Sequential and Functional API](https://www.youtube.com/watch?v=WAciKiDP2bo\&list=PLhhyoLH6IjfxVOdVC1P1L5z5azs0XjMsb\&index=5) (Aladdin Persson, **first 10 min**)
      * **Note**: After the first 10 min, the functional API is covered, which you likely will not need for your projects. Of course, you are free to optionally also watch the rest of the video.
    * [TensorFlow Tutorial 18 - Custom Dataset for Images](https://www.youtube.com/watch?v=q7ZuZ8ZOErE) (Aladdin Persson, **first 7 min**)
      * **Note**: The second method presented in the video (minutes 8 through 14) is deprecated and should no longer be used. The methods presented in the remainder of the video are not relevant to this week's assignment but may be interesting if you're doing a computer-vision project.
    * [Data Augmentation - Deep Learning with Tensorflow | Ep. 19](https://www.youtube.com/watch?v=yke3zUGgQ-w) (Kody Simpson, 23 min)
      * **Note**: Don't be confused by the alternative approach to do data augmentation that is shown first in the video. The presentation of the method relevant for this week's assignment starts at around timestamp 9:30.
* Set up a repository for your project following the instructions given [here](https://opencampus.gitbook.io/opencampus-machine-learning-program/projects/requirements)
* Conduct a literature review according to the instructions given [here](https://github.com/opencampus-sh/ml-project-template/blob/main/0_LiteratureReview/INSTRUCTIONS.md)
* Document your findings on the literature review according to the instructions of above
* Complete the assignment in the following notebook:
  * [Assignment Notebook](https://colab.research.google.com/github/opencampus-sh/course-material/blob/main/machine-learning-with-tensorflow/week-03/Assignment_Week3_Fast_Food_Image_Classification.ipynb)
* Optional:
  * To get a better theoretical understanding of Convolutional Neural Networks, the [playlist](https://www.youtube.com/watch?v=ArPaAX_PhIs\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=1) from DeepLearningAI from which some of the videos for this week were taken is generally a good source. In particular, you may find the videos [C4W1L06 Convolutions Over Volumes](https://app.gitbook.com/u/WWDikjQ3eVgvMfPm7LVskOEkgST2) (11 min) and [C4W1L11 Why Convolutions](https://www.youtube.com/watch?v=ay3zYUeuyhU\&list=PLkDaE6sCZn6Gl29AoE31iwdVwSG-KnDzF\&index=12) (9:40 min) interesting. Naturally, you are free to watch more videos.
