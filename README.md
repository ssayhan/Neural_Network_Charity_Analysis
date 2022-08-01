# Neural_Network_Charity_Analysis

Deep Learning ML

## Project Overview
In this project, we will use Neural Networks Machine Learning algorithms with Beks’. We will create an unsupervised binary classifier that is capable of predict whether applicants will be successful if funded by Alphabet Soup. We will use Tensor Flow library to create  binary classifier.
We will start with ML process with cleaning, manipulating and data preprocessing.

## Resources
•	Dataset charity_data.csv
•	Software: Jupyter Notebook
•	Languages: Python
•	Libraries: Scikit-learn, TensorFlow, Pandas
•	Environment: Python

## Results

### Processing
•	For this project we use  “IS_SUCCESSFULL” column as our variable
•	APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT columns used for features for our model.

### Compiling, Training and Evaluating the Model
•	We used 3 layers to optimize the ML module. Because I didn’t reach %75 accuracy with two layers. Adding layers methods is not always give the better result.
•	We used 150 neurons for first layer and 75 neurons for second layer.
•	We trained model with 50 epochs instead of 500.
After the these configurations we reach the %75.57 accuracy.

<img width="930" alt="Screen Shot 2022-07-31 at 11 48 00 PM (2)" src="https://user-images.githubusercontent.com/77603561/182083735-af2ef006-ce1b-43ea-9429-6dfcdb13e049.png">

 


##Summary
Loss score is equal to 0.5187. the model reached the required criteria. So it means. This data is not the perfect model. 
Accuracy score is 0.7552, so it means model accurate %75.51
