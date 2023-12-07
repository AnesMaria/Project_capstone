# Project_capstone : Building a Student Intervention System

# Introduction
The goal of this project is to use machine learning techniques to develop a student intervention system. selecting students who are susceptible to benefiting from early intervention before they drop out of school is the purpose.
# Project Overview
The identification of students who need intervention to improve their academic performance is a problem that educational institutions frequently face. The goal of this project is to develop a predictive model that can identify students who may dropout.

# Dataset
This project's dataset contains a variety of information based  on academic achievement as well as demographics and familial profil and relationshep.
The detailed list of colomns is :  'school', 'sex', 'age', 'address', 'famsize', 'Pstatus', 'Medu', 'Fedu',        'Mjob', 'Fjob', 'reason', 'guardian', 'traveltime', 'studytime',
       'failures', 'schoolsup', 'famsup', 'paid', 'activities', 'nursery', 'higher', 'internet', 'romantic', 'famrel', 'freetime', 'goout', 'Dalc',        'Walc', 'health', 'absences', 'passed'

# Technologies Used
Python
Scikit-learn
Pandas, NumPy
Jupyter Notebook

# Models Evaluated
Decision Tree Classifier
Support Vector Machine (SVM/SVC)
Random Forest Classifier

# Model Selection and Evaluation
We trained and evaluated the three models following a preprocessing and exploratory data analysis stage. In order to ensure an accurate evaluation, each model was evaluated using the F1 score while taking into account the training and testing datasets.

# Optimizing the Best Model
The model with the highest F1 score on the testing dataset was selected. We performed grid search optimization to fine-tune the model parameters, aiming to improve the performance further.

# Results
The final tuned model showed improved F1 scores, indicating better performance in identifying students who require intervention.

# Conclusions
This project illustrates how machine learning can be used in education by giving administrators and teachers a tool to use when making data-driven decisions that will most effectively meet students' needs.

Link to the Blog : https://medium.com/p/4ca9cadf3ced/edit

# Future Work
Integration with real-time educational data systems and on line learning platforme to prevent the droping out school.
Exploration of more advanced models in the deep learning domain . 
