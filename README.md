# Rotten-Tomato-Review Using Naive Bayes Classifier


About the project: 

This project will cover a thorough method of determining the user review element utilizing a custom-built Naive Bayes Theorem.
Text data can be categorized in a variety of ways, many of which are great at providing high levels of accuracy.
However, the Naive Bayes implementation of the same in the current situation will be examined in this research.
The rotten tomatoes movie review from the Kaggle competition serves as the dataset for this.
About 480000 objects in the collection have the class type of fresh potato or rotting tomato.


Brief description of the project's steps:


Calculate each class c's prior probability. This is the likelihood that a randomly chosen data point will fall into class C, without taking any attributes into account.
Find the likely likelihood of seeing the traits x, taking each class c into consideration. This is the probability that, if the data point belongs to class c, it will have the features x.
Calculate the evidence probability P(x), which is the likelihood that the feature x will be observed. This probability can be calculated by multiplying the likelihood probability for each class by the total of the prior probability for each class.
As the projected class for the data point, pick the class having the highest posterior probability.
Installation Instructions: This does not require any specifi installations as the project is built over colab. However there are some libraries that need to be included for this project. Most of them are the basic libraries such as 'numpy' and 'pandas' which are a must include in every Machine Learning project. We need another 'nltk' for natural language processing in this project.


How to run the project: 

Open Google Colab in your web browser and sign in using your Google account.
Pull the code from the repository to your colab or you can directly click on 'https://colab.research.google.com/drive/1gGvbQw_7fB8jSQFxsvKe94e922l8wr3F?authuser=1#scrollTo=ZxpTvNx1eWxc' link for code.
This is a view only notebook and you will have to create a copy of it in your local drive for editing.
Select a runtime type by clicking on "Runtime" in the top menu, then change to "GPU" for running faster.
Download the dataset from 'https://www.kaggle.com/datasets/ulrikthygepedersen/rotten-tomatoes-reviews?resource=download' and upload it the drive. Access the dataset from the drive by mounting it.
Rest of the instructions include running every code snippet and get the output.
