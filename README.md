
<div id="header" align="center">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHhiNmlvbnd2NHE5YnFqajh1dzFzdngwYXdjMXZicjFoYXl5MXdxZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/P0bSQ1lpUx3eODngpC/giphy.gif" width="400" />
    <h1 align="center"> PROJECT: UDEMY AND THE SUCCESS IN SALES OF ITS COURSES. PREDICTION USING PYTHON </h1>
</div>



## A. DATASET INFORMATION

### A.1. Context

- *Udemy* (www.udemy.com) is an online marketplace that offers distance learning courses on various topics related to technology and business. The site operates as a marketplace where instructors can publish the courses they have developed and earn money when any Udemy student purchases them.
- The number of *Udemy* courses has grown rapidly due to the success of distance education. However, the courses have had very diverse demands; some have been bestsellers while others have had so few students that they do not justify the investment made in them.

### A.2. Project Objective
**The ultimate goal is to predict which of the courses to be launched in 2023 will be *bestsellers*, through the analysis of data from courses published in Spanish between 2012 and 2022.**

## B. ABOUT THE PROJECT DOCUMENTATION 

### B.1. How to Read the Documentation?

- Read the file named "Project_Final_Udemy.ipynb" where you can visualize the Python code in Google Colaboratory.
- Within the Python code, you will find an organized outline with interpretations and analyses developed.
  
### B.2. Documentation Outline

#### 1. PROJECT STORYTELLING
#### 2. DATASET INFORMATION
#### 3. EXPLORATORY DATA ANALYSIS (EDA)
#### 4. DATA CLEANING AND TRANSFORMATION (Data Wrangling)
#### 5. CONNECTION WITH PUBLIC APIS
#### 6. CLASSIFICATION AND REGRESSION ALGORITHMS & CLUSTERING ALGORITHMS I
#### 7. CLUSTERING ALGORITHMS II & ALGORITHM SELECTION AND MODEL TRAINING I
#### 8. ALGORITHM SELECTION AND MODEL TRAINING II & MODEL VALIDATION - METRICS
#### 9. MACHINE LEARNING MODELS IMPROVEMENT I AND II
#### 10. TRAINING WITH MULTIPLE MODELS
#### 11. BOOSTING
#### 12. CONCLUSIONS

### C.

#### Matplotlib:

'import matplotlib as mpl'
import matplotlib.pyplot as plt
#### Seaborn:

import seaborn as sns
#### Pandas:

import pandas as pd
#### NumPy:

import numpy as np
#### Scikit-learn:

import sklearn as sk
from sklearn import model_selection
from sklearn import ensemble
from sklearn import metrics
from sklearn import tree
from sklearn.decomposition import PCA
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error
from sklearn.metrics import accuracy_score
from sklearn.model_selection import GridSearchCV
from sklearn.model_selection import RandomizedSearchCV
from sklearn.experimental import enable_halving_search_cv
from sklearn.model_selection import HalvingGridSearchCV
from sklearn.model_selection import HalvingRandomSearchCV
from sklearn.preprocessing import LabelEncoder
from sklearn.metrics import accuracy_score, classification_report
from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
from sklearn.tree import DecisionTreeClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.svm import SVC
from sklearn.ensemble import VotingClassifier
from sklearn.model_selection import GridSearchCV
from sklearn.feature_selection import SelectFromModel
from sklearn.ensemble import StackingClassifier, BaggingClassifier, AdaBoostClassifier, VotingClassifier
from sklearn.metrics import recall_score, precision_score, accuracy_score
from sklearn.model_selection import LeaveOneOut, cross_val_score
#### XGBoost:

import xgboost as xgb
