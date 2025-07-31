# Salary Prediction

## Introduction
This project aims to predict salaries based on various factors, such as age, gender, education level, job title, and years of experience. We have used a dataset containing 6704 rows and 6 columns to develop and evaluate our salary prediction model.

## Data Preprocessing

### Handling Missing Values
We checked for missing values in the dataset and removed rows with missing data, ensuring a clean dataset for modeling.

## Data Visualization


### Top 10 Highest Earning Professions
*A Bar plot depicting the highest paying job titles versus the mean salary.*
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/6f7c4c5a-f7e4-47fd-b4e9-14d65872bd86" />


### Distribution of Continuous Variables
*This histogram shows the distribution of continuous variables in the dataset.*
<img width="1189" height="1489" alt="image" src="https://github.com/user-attachments/assets/e8027e59-27a9-451b-8848-fa1a4f925a8a" />
<img width="1189" height="1489" alt="image" src="https://github.com/user-attachments/assets/e61b5bbe-a35d-48fb-8f84-f8e1389f22f6" />



### Distribution of Education and Gender
*A plot displaying the Education Level and Gender.*
<img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/f1d8fe99-60ab-4b96-8007-8563ecd7a5db" /> <img width="1489" height="490" alt="image" src="https://github.com/user-attachments/assets/11b9c418-591e-4d65-a274-dde276aa9a23" />


### Correlation Heatmap
![Correlation Heatmap](images/Heatmap.png)
*A heatmap illustrating the correlation between different features.*

## Model Building and Evaluation

### Model Selection
We explored various machine learning algorithms, including Linear Regression, Decision Trees, and Random Forests, to build our salary prediction model. Hyperparameter tuning was performed using GridSearchCV to find the best model configuration.

### Model Evaluation

Each model's performance was evaluated using several regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score. These metrics help assess the accuracy and reliability of the predictions.

### Feature Importance
*A bar chart depicting the importance of different features in predicting salary.*
<img width="1095" height="699" alt="image" src="https://github.com/user-attachments/assets/1ad29d8e-fe61-432b-ba6a-766f6be9ae9a" />

## Results

1. The Random Forest model achieved the highest R-squared score and the lowest error metrics (MSE, MAE, RMSE), indicating superior predictive performance compared to the other models.
2. The Decision Tree model also performed well but had higher errors than the Random Forest.
3. The Linear Regression model, while simple, had the lowest R-squared score and the highest errors, suggesting limitations in capturing complex relationships.

## Conclusion

In conclusion, the Random Forest model demonstrated the best predictive capability for salary estimation in this dataset. Its feature importance analysis revealed the most influential factors.

The model evaluation and feature importance analysis provided valuable insights for understanding salary determinants and highlighted the importance of choosing the appropriate machine learning model for regression tasks.

This salary prediction model can be used to make informed salary estimates based on individual characteristics, making it a valuable tool for HR analytics and compensation planning.In conclusion, our salary prediction model, trained on a well-preprocessed dataset, successfully predicts salaries based on various factors. This project demonstrates the importance of data preprocessing, feature engineering, and model selection in creating an accurate predictive model.

## Usage

To use our salary prediction model, you can follow these steps:

1. Clone this repository.
2. Install the required libraries listed in the `requirements.txt` file.
3. Run the provided Jupyter notebook or Python script to load the model and make predictions on new data.
