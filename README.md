
# Module 3 Project
By David Cuervo

## Background

Build a classifier to accurately predict the condition of water wells in Tanzania. 

<img width="934" alt="Tanzania_Water_Well_plot_map" src="https://user-images.githubusercontent.com/57383419/118528070-88a37580-b707-11eb-8429-945b29976dc1.png">

## Contents of Repository

- Folder containing the original data sets from DrivenData
- CSV of cleaned data
- Data_Cleaning Notebook: contains the code for exploring and cleaning the original data set
- Modeling Notebook: contains code for building the best classifier
- PNG image of Tanzania and the wells plotted
- PDF of project presentation
- Rubric for Module 3 Project

## Approach

- Began by downloading the data from DrivenData
- Worked through data set column by column to deal with missing data, outliers, and catigorical variables
- Exported cleaned data and used it so begin building classifiers
- Used Boruta as feature selection
- Used the features selected through Boruta to build logistic regression, decision tree, and random forest models

## Conclusions

![feature_importance_tanzania](https://user-images.githubusercontent.com/57383419/118529197-da98cb00-b708-11eb-887d-668871ed6319.png)

- Construction year, waterpoint type, and GPS height were the most important features in the model

![gps_height_well_function](https://user-images.githubusercontent.com/57383419/118529211-dec4e880-b708-11eb-9a65-0308193411d4.png)
![waterpoint_type_status](https://user-images.githubusercontent.com/57383419/118529218-e08eac00-b708-11eb-9cd1-da3c1074be0f.png)




