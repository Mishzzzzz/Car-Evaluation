# Car-Evaluation

This model predicts the quality of the used car whether it is in a good state, very good state, accepted state, or not accepted.

The car evaluation model has two files,
1- car_data.csv which is the dataset used for training the classification model. The dataset can be found here: https://archive.ics.uci.edu/ml/datasets/Car+Evaluation
2- car_evaluation.ipynb which contains the code for the classification.


The libraries used:
pandas
numpy
matplotlib.pyplot
sklearn: svm, model_selection: train_test_split, metrics


The motivation for the project:
this project is implemented as reuired for Udacity to show the general steps when training a classification model that predicts the quality of the used car whether it is in a good state, very good state, accepted state, or not accepted. By that, the customer can decide whether to buy a specefied used car or not by providing the state and condition of the used car.

A summary of the results of the analysis:
the car_evaluation.ipynb contains the steps used to create an train the model. The following questions are answered within the notebook.
1- How to clean and prepare the dataset?
2- How to train the model?
3- Decide whether to buy or not?
At the end, the accuracy rate obtained from the classificatiob model is 91%
