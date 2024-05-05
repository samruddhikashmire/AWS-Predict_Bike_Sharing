# Report: Predict Bike Sharing Demand with AutoGluon Solution
Samruddhi Kashmire

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
We had to remove the negatives

### What was the top ranked model that performed?
WeightedEnsemble_L2

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
By separate out the datetime into hour, day, or month parts

### How much better did your model preform after adding additional features and why do you think that is?
it did not performed well

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
Due to less resourses i could not prefrom the hyper parameters

### If you were given more time with this dataset, where do you think you would spend more time?
ON getting the domain knowledge of the dataset



### Create a line plot showing the top model score for the three (or more) training runs during the project.
![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

![model_test_score.png](img/model_test_score.png)
