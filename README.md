# Django Web Application Audi Car Price Prediction
Django web application to predict Audi Car prices from Kaggle datasets using Random Forest Regression trained model.

## About
In a real-world scenario, a business owner selling a lot of used cars needs to know a fair price based on the characteristics of the car itself. To solve the problem, we must
collect a lot of data to create a tool or model that is able to make price predictions based on previously collected data. That's why I decided to develop a Django web app for
provides users with interactive U/I to make Audi Car price predictions.

## Machine Learning Details
 
  - Type of Problem : Supervised Machine Learning (Regression Problem)
  - Model to Use   : Random Forest Regression

## Dataset
Dataset obtained from [Here](https://www.kaggle.com/adityadesai13/used-car-dataset-ford-and-mercedes) with title '100,000 UK Used Car Data set', in this project i just use
Audi Car Dataset to train machine learning model to make car price prediction.

## Pipeline Diagram
   
   - Model development is built using pipelines to help automate machine learning workflows. The figure below shows a diagram of how the pipeline works, where numerical and categorical data have their own treatment. To prevent overfitting and find the best param to minimize errors we can use GridSearchCV to do cross-validation with the total number of folds is 5.
   
        ![Diagram Pipeline](screenshot/diagram_pipeline.PNG)
   
   Source: https://scikit-learn.org/stable/auto_examples/compose/plot_column_transformer_mixed_types.html
  
## Evaluation of the Model

  - Score Based on Mean Absolute Error (MAE) : 1853.550

## Web App Built with
* Python 3.9.6
* Django 3.2.11
* DB SQLite
* Bootstrap Framework

## Dependencies
* Can be seen [Here](requirements.txt)

## Preview of the Web App

### Features
* CRUD Feature
* Predict New Data
* Export to (Json, CSV, XlS/Excel)

### Login

   ![Login](screenshot/login.png)


### Predict

   ![Insert Data](screenshot/predict_insert.png)
   
   
   ![Result Insert](screenshot/predict_result_1.png)

### Result

   ![Result Data](screenshot/predict_result_2.png)
   
   
### Export

   ![Export Data](screenshot/export_data.png)
