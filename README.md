# Forest_Trees

This project is a collaboration between Ahilan and Abigail Sixto.

## Analysis

The analysis is based on the data published by US Forest Service (USFS). Each observation contains information of type of tree coverage of a (30 x 30 meter cell) at four wilderness areas located in the Roosevelt National Forest of Northern Colorado. Each cell contains a number of features including information about the soil type, elevation, and sunlight conditions, and there are a total of 7 possible types of trees. 
 
These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

The purpose of our analysis is to determine a model based on those categorical features and provide our customer with a tool to identify possible areas to grow Lodgepole Pine with the least human intervention. Our customer would like to explore areas outside this particular forest, therefore we would remove from the dataset the relevant columns regarding specific areas of this forest and check if we obtain a good prediction model.

## The steps we follow are :

1. Data Understanding
2. Data Visualization
3. Data Preparation
4. Modelling
   - Baseline Model via Logistic Regression
   - Optimised Logistic Regression
   - Optimised Decision Tree
   - Optimised Random Forest
   - Adaboost
   - XGBoost
   - Voting
   - Stacking
5. Model Selection
6. Threshold Selection
7. Evaluation

## Contents of Repository
- ``Superseded  ``       :   Folder containing previous work
- ``Classification.py `` :   Python file with classifcation class utilised in index.ipynb
- ``Ensemble.py  ``      :   Python file with ensemble class utilised in index.ipynb
- ``Fores_trees.pdf ``   :   PDF containing project presentation
- ``READMEmd  ``         :   Markdown file with executive summay of project
- ``covtype.csv  ``      :   CSV file with data used for project
- ``index.ipynb   ``     :   Python Notebook containing main conent for project (code,visualisations,modelling,evaluation)
