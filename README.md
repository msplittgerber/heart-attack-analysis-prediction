# heart-attack-analysis-prediction
### Table of Contents

1. [Installation](#installation)
2. [Project Description](#project)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code can be run using Python versions 3.* and all necessary libraries.

## Project Description <a name="project"></a>

In this project, different models from classical statistics and machine learning are used to predict the occurrence of heart disease (narrowing of the coronary arteries). Various demographic variables and health status parameters were used as predictors. First, the data set was read in and preprocessed. This was followed by the construction of various prediction models: 1. logistic regression, 2. support vector machines, 3. decision tree, 4. random forest. Finally, the model quality of the different approaches was compared. An overview of the steps used can be found below. The dataset used comes from the UCI Machine Learning Repository and was prepared and made available by David W. Aha. It is also located in various places on Kaggle, which is where it was obtained for this project (Kaggle dataset ). The original dataset contained 75 variables (created in 1988). Based on this, a data set with 14 variables was extracted, which has already been the basis of various publications and machine learning approaches and was also used for this project.

## File Descriptions <a name="files"></a>
The project contains a jupyter notebook with all code that has been used for analyses and a copy of the kaggle dataset.

## Results <a name="results"></a>
With the exception of the decision tree, all models perform about equally well. For Random Forest and SVM, the differences between Precision and Recall are greater than for logistic regression. It hardly makes a difference whether the missing values were imputed or whether cases with missing values were excluded from the analysis (this can be explained by the small number of cases with missing values).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset) as well as at the UCI Machine Learning Repository [here](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).
