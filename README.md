# Stroke Probability Prediction using Machine Learning

[![Python Versions](https://img.shields.io/pypi/pyversions/yt2mp3.svg)](https://pypi.python.org/pypi/yt2mp3/)

The data for training the model was obtained from [here](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv).
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. Stroke is a blood clot   or bleeds in the brain, which can make permanent damage that has an effecton mobility, cognition, sight or communication. Stroke is considered as medical  urgent situation   and can cause long-term neurological damage, complications and often death. 

This web app is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

The web app was built in Python using the following libraries and deployed in Heroku environment.
* streamlit
* pandas
* numpy
* scikit-learn
* pickle
* Imbalanced Learn

### We Experimented Outputs with Different Models: ###

* Random Forest Classifier

| Metrics  |  Score |
| :------------: | :------------: |
| accuracy_score  |  0.9706827825639707|  
|  precision_score | 0.9896551724137931  |
|  recall_score |  0.9517857142857142 |
|  f1_score |  0.9703511053315995 |

* Logistic Regression

| Metrics  |  Score |
| :------------: | :------------: |
| accuracy_score  |  0.7754918348977755| 
|  precision_score | 0.7594272076372315  |
|  recall_score |  0.811734693877551 |
|  f1_score |  0.7847102342786684 |

* Adaboost Classifier

| Metrics  |  Score |
| :------------: | :------------: |
| accuracy_score  |  0.9709399511379709| 
|  precision_score | 0.990701381509033  |
|  recall_score |  0.9512755102040816 |
|  f1_score |  0.9705882352941176 |

* SVM (SGD Classifier)

| Metrics  |  Score | 
| :------------: | :------------: |
| accuracy_score  |  0.770991384852771|
|  precision_score | 0.7462583467649091  |
|  recall_score |  0.8267857142857142 |
|  f1_score |  0.7844608495703739 |

* Voting Classifier

| Metrics  |  Score | 
| :------------: | :------------: |
| accuracy_score  |  0.9224636749389225|
|  precision_score | 0.888134799906389  |
|  recall_score |  0.9681122448979592 |
|  f1_score |  0.9264005858659832 |

* Neural Networks

| Metrics  |  Score | 
| :------------: | :------------: |
| accuracy_score  |  0.9566670952809566|
|  precision_score | 0.9396319018404908  |
|  recall_score |  0.9767857142857143 |
|  f1_score |  0.9578486554096309 |

### Literature References ###
* Artificial Neural Network Application to the Stroke Prediction. Available from: https://ieeexplore.ieee.org/document/9203638
* Performance Analysis of Machine Learning Approaches in Stroke Prediction. Available from: https://ieeexplore.ieee.org/document/9297525
