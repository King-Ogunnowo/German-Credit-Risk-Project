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

<b>Results</b>
RandomForestClassifier(random_state=42) 
 RandomForestClassifier test Score : 0.8857142857142857 
 recall_Score : 0.8285714285714286 
 f1_Score : 0.8787878787878788 
 precision_Score : 0.9354838709677419 
 [[132   8]
 [ 24 116]] 
 
 *****************************
 
GradientBoostingClassifier(random_state=42) 
 GradientBoostingClassifier test Score : 0.7928571428571428 
 recall_Score : 0.75 
 f1_Score : 0.7835820895522388 
 precision_Score : 0.8203125 
 [[117  23]
 [ 35 105]] 
 
 *****************************
 
DecisionTreeClassifier(random_state=42) 
 DecisionTreeClassifier test Score : 0.8071428571428572 
 recall_Score : 0.7 
 f1_Score : 0.7839999999999999 
 precision_Score : 0.8909090909090909 
 [[128  12]
 [ 42  98]] 
 
 *****************************
 
ExtraTreesClassifier(random_state=42) 
 ExtraTreesClassifier test Score : 0.8821428571428571 
 recall_Score : 0.8428571428571429 
 f1_Score : 0.8773234200743494 
 precision_Score : 0.9147286821705426 
 [[129  11]
 [ 22 118]] 
 *****************************
