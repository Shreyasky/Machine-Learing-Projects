# Machine-Learing-Projects
Project Title: Sonar Data Analysis and Classification

##Tools Used:
Python
Pandas
NumPy
Scikit-learn (for machine learning)
Project Overview:
The project involves the analysis and classification of sonar data. The dataset is loaded using Pandas, and initial exploration is performed by displaying the first few rows of the data. The dataset consists of 208 samples with 61 features.

##Data Preprocessing:
The dataset is divided into features (X) and target labels (Y).
The target labels are categorical values ('M' for Mine and 'R' for Rock).
Training and Test sets are created using Scikit-learn's train_test_split function.

##Model Training:
Logistic Regression is chosen as the classification model.
The model is trained using the training dataset.

##Model Evaluation:
The accuracy of the model is evaluated on both the training and test datasets.
The accuracy on the training data is approximately 83.42%.
The accuracy on the test data is approximately 76.19%.

##Prediction System:
Two examples of input data are provided to showcase the prediction system.
The first set of input data is classified as 'Rock' ('R').
The second set of input data is classified as 'Mine' ('M').
##Conclusion:
The logistic regression model demonstrates reasonable accuracy in classifying sonar data as either a rock or a mine. Further improvements and fine-tuning can be explored for enhancing model performance.
