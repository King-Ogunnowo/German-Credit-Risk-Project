# German-Credit-Risk-Project
This repository contains my solution to Kaggle's German Credit Risk Project

<b>Objective:</b> To build identify hidden insights in the data and build a model that can predict the credit risk of an individual

<b>Tools:</b> 
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. theta (custom built data processing package. built on pandas, numpy, matplotlib, seaborn and sklearn ml libraries)
6. sklearn ML Library 
7. imblearn
8. IPython

<b>Methods</b>
This project employs a benchmarking approach to compare the performance of different algorithms on the dataset. The best algorithm is then picked
Feature importance as tool for model explainability to explain how the model makes predictions. See notebook for this. 

<b>Results:</b>
1. RandomForestClassifier(random_state=42) 
 a. RandomForestClassifier test Score : 0.8857142857142857 
 b. recall_Score : 0.8285714285714286 
 c. f1_Score : 0.8787878787878788 
 d. precision_Score : 0.9354838709677419 
 e. Confusion matrix:
 [[132   8]
 [ 24 116]] 
 
 *****************************
 
2. GradientBoostingClassifier(random_state=42) 
 a. GradientBoostingClassifier test Score : 0.7928571428571428 
 b. recall_Score : 0.75 
 c. f1_Score : 0.7835820895522388 
 d. precision_Score : 0.8203125 
 e. Confusion matrix:
 [[117  23]
 [ 35 105]] 
 
 *****************************
 
3. DecisionTreeClassifier(random_state=42) 
 a. DecisionTreeClassifier test Score : 0.8071428571428572 
 b. recall_Score : 0.7 
 c. f1_Score : 0.7839999999999999 
 d. precision_Score : 0.8909090909090909 
 e. Confusion matrix:
 [[128  12]
 [ 42  98]] 
 
 *****************************
 
4. ExtraTreesClassifier(random_state=42) 
 a. ExtraTreesClassifier test Score : 0.8821428571428571 
 b. recall_Score : 0.8428571428571429 
 c. f1_Score : 0.8773234200743494 
 d. precision_Score : 0.9147286821705426 
 e. Confusion matrix
 [[129  11]
 [ 22 118]] 
 *****************************
