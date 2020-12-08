# DMML_CW2_Group_20

This is a project on investigating overfitting.The main lesson being a classifier doing well on training data does not gurantee that it will do well on the test data.
Investigations were also carried out from the point of view of the relationship between overfitting and complexity of the classifier, i.e the more degrees of freedom in the model the more likely that the model overfits the data.

Another interesting analysis was on how the the size of the data relates/corelates with the size of the data.


Algorithms used in this project:

1.Decision Trees - J48 (C4.5), Random Forests 

2.Linear classifier   , this was our base comparison

3.Multi layer perceptron

4.Convolutional Neural Networks

The data size generally affected the accuracy of the classifiers but the behaviour with CNN was quite interesting as the classifer still performed suprisingly too well.

The training data was modified in 2 ways:

1: Removing 4000 instances and adding them to the test data; this meant reducing the size of the training data

2: Removing a futher 9000 and adding the to the test data; this meant an even smaller training set



From the experiements CNN was more capable of generalising too well on unseen data being able to reach as high as 90% +
-------------
