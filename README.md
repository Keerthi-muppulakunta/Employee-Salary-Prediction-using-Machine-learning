# Salary Prediction

## Introduction
This project aims to predict salaries based on various factors, such as age, gender, education level, job title, and years of experience. We have used a dataset containing 6704 rows and 6 columns to develop and evaluate our salary prediction model.

## Data Preprocessing

### Handling Missing Values
We checked for missing values in the dataset and removed rows with missing data, ensuring a clean dataset for modeling.

## Data Visualization


### Top 10 Highest Earning Professions
![Gender Distribution](<img width="1189" height="790" alt="Top10" src="https://github.com/user-attachments/assets/3d5042bb-7b63-40f3-8346-2269a7d70e3f" />)

*A Bar plot depicting the highest paying job titles versus the mean salary.*

### Distribution of Continuous Variables
![Age Distribution](<img width="1189" height="1489" alt="Distribution" src="https://github.com/user-attachments/assets/8d54420c-0f8d-4810-9943-92914f4e07a5" />)

*This histogram shows the distribution of continuous variables in the dataset.*

### Distribution of EduEducation and Gender
 (<img width="1489" height="490" alt="ed gender_distribution" src="https://github.com/user-attachments/assets/fc8b36cb-8262-46b9-afa4-136d1fa524b1" />)
![Salary vs. Education]()
*A plot displaying the Education Level and Gender.*

### Correlation Heatmap
![Correlation Heatmap](<img width="831" height="790" alt="Heatmap" src="https://github.com/user-attachments/assets/e087c785-31ce-4ac5-a8c3-e6608126986d" />)

*A heatmap illustrating the correlation between different features.*

## Model Building and Evaluation

### Model Selection
We explored various machine learning algorithms, including Linear Regression, Decision Trees, and Random Forests, to build our salary prediction model. Hyperparameter tuning was performed using GridSearchCV to find the best model configuration.

### Model Evaluation

Each model's performance was evaluated using several regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score. These metrics help assess the accuracy and reliability of the predictions.

### Feature Importance
![Feature Importance](<img width="1095" height="699" alt="Feature_Imp" src="https://github.com/user-attachments/assets/3e07af84-9ced-4684-ab49-4bfce851f53c" />)

*A bar chart depicting the importance of different features in predicting salary.*

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

