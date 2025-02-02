# Datathon-2025
This repo contains the code and description of our Rice Datathon 2025 project. 

- `cleaning.ipynb` contains the data imputation code, where we tried to imputate the missing values as well as the "Unknown" from the dataset
- `Modeling.ipynb` contains the code for modeling stage, where we used Random Forest and XGBoost for our data
- `submission_file.xlsx` contains our final prediction for the scoring.csv


In this project, we imputated the data with "unknown" values as well as the ones with NAs. We then split the data into training, validation, and testing into 80%, 10%, and 10% respectively. For the modeling stage, we used two models. 

The first model we used is the Random Forest model, where we did fine tuning for the parameters and was able to achieve around 4000 for the RMSE for scoring.csv. The second model we chose was the XGBoost model, where we also did fine tuning. The model was able to achieve around 3100 in RMSE for scoring.csv. 

It turns out that the XGBoost model had a better performance, which will be our final model for this project.

