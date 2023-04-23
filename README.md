# Y127_Team2_ChioHangLim
SC1015 Project Y127 Team 2

# About our project

Our team has decided to work on heart disease, as heart disease is one of the leading causes of death globally and is a genuine cause for concern.
Early detection and accurate diagnosis of heart disease can greatly improve patient outcomes and prevent mortality.The Heart Disease Analysis dataset is a valuable resource for researchers, healthcare providers, and data analysts who are interested in studying heart disease and developing accurate predictive models. By analyzing this dataset, we can identify the most important risk factors for heart disease and develop screening tools to detect early signs of the disease.

The dataset used will be linked in one of the folders, it is a dataset from Kaggle and it consists of various clinical parameters of patients and whether or not they suffer from heart disease.


# Problem statement

To predict diagnoses based on a patient’s symptoms, and to decide on the suitable treatments to offer the patient.

# Contributors

Ranielle - Model building, EDA

Xiao En - Data Preparation, EDA

Bryan - Editing & Proofreading 

# Models used

- Logistic Regression: a statistical method for analyzing a dataset in which there are one or more independent variables that determine an outcome.
- Naive Bayes: a classification algorithm based on Bayes' theorem that assumes independence between features.
- Support Vector Machine: a supervised learning algorithm that can be used for classification or regression tasks, particularly for data with complex boundaries.
- K Nearest Neighbors: a non-parametric classification algorithm that makes predictions based on the k nearest data points in the training set.
- Random Forest: an ensemble learning method for classification, regression and other tasks, which operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes or mean prediction of the individual trees

# Performance metrics used

- ROC AUC

- F1 Score

# Conclusion

- The KDE plots were asymmetrical, which suggests that the variables are not normally distributed.
- Heatmap : Systolic and Diastolic were strongly correlated, and LDL, HDL, and cholesterol were strongly correlated.
- Random Forest performed the best out of all the models used. 
- Overfitting is not an issue as the validation and training scores and very similar and we are able to achieve a score of 96%.
- Used ensemble model as the final model to improve overall performance as there is a good ratio of correct predictions to total predicitions. 


# Learning something new  

- One-hot encoding for data preparation
- Random forest model
- K Neighbours
- Naive bayes
- Overfitting 
- Model ensembling
- ROC AUC and F1 score

# References

- https://developers.google.com/machine-learning/crash-course/classification/roc-andauc#:~:text=AUC%20stands%20for%20%22Area%20under,across%20all%20possible%20classification%20thresholds 
- https://towardsdatascience.com/essential-things-you-need-to-know-about-f1-score-dbd973bf1a3
- https://medium.com/analytics-vidhya/accuracy-vs-f1-score-6258237beca2#:~:text=Accuracy%20is%20used%20when%20the,as%20in%20the%20above%20case
- https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/
- https://c3.ai/glossary/data-science/f1-score/#:~:text=Why%20is%20the%20F1%20Score,found%20in%20the%20other%20class
- https://towardsdatascience.com/ensemble-models-5a62d4f4cb0c
- https://aws.amazon.com/what-is/overfitting/#:~:text=Overfitting%20is%20an%20undesirable%20machine,but%20not%20for%20new%20data
