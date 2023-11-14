# ML Sonar Rock vs Mine Prediction

Problem Statement : There is a war going on in between 2 countries and a submarine is going under the water and it needs to detect if there are any water mines in the ocean which is placed by other country. So I have developed a model which predicts if the object is mine or a rock from submarines SONAR waves.


Workflow : 

1. Sonar Data : We collect sonar data where we have data about whether object is a Rock or Metal(mine).
2. Data Processing : Clean the data if there any null values, process and load the data into a pandas dataframe.
3. Train Test Split : We have to split the data we processed into train and test data. 90% of data wll be used for training the model and 10% of data will be used for testing the model.
4. Logistic Regression Model : Here we use this model as it is a supervised learning algorithm and our problem statement is a binary classification model. Logistic Regression Model works accuratly for this kind of task.


Input_data --> trained logistic regression model --> output as Mine(M) or Rock(R)



