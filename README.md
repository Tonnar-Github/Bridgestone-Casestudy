# Bridgestone-Casestudy

This project was assigned to the our team by Bridgestone tire company. Unforuntetly the data for this study is to much to host on github and is not publicly avaliable. The purpose of this case study was to assist Bridgestone in targeting customers for a fall sale. Currently, Bridgestone was taking a carpetbombing approach to marketing with an accucary(response rate) of 8%. Our team wanted to create a model that could beat that target.

## Data Cleaning
The original dataset due to its size of nearly 50 gigabytes was very difficult to clean as such we used the vroom library. Here you can see some of hte main features that we cleaned were car names. 

## Feature Engineering
The folder contains (created_data)[https://github.com/Tonnar-Github/Bridgestone-Casestudy/tree/main/feature_engineering/created_data] which contains some of the created data from the main data that is allowed to be shared with the public, (feature_engineering)[https://github.com/Tonnar-Github/Bridgestone-Casestudy/tree/main/feature_engineering/feature_engineering] which is a relatively straight forward folder, and the creation of the (target variable)[https://github.com/Tonnar-Github/Bridgestone-Casestudy/tree/main/feature_engineering/response_variable]

## Model
Here you will find the final two models that were pushed into production before deciding on the xgb with pca. 

## Sampling
As mentioned above the dataset in this case was very large but was still somewhat unbalanced. This folder contains our attempt to reconcile it

##Results
Our model performed with nearly 12% accucary maining to correctly predict who would be a good target. This would generate bridgestone nearly a million dollars in extra revenue.
