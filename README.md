# Supervised_Regression_SalaryPrediction
## Project Portfolio Exploratory Data Analysis
Exploratory Data Analysis (EDA) is a crucial first step in any data analysis project. EDA can help in digging deeper into the dataset, discovering hidden patterns, and understanding the overall characteristics of the data. Exploratory Data Analysis (EDA) is the first step in this salary prediction project. This project will present EDA results that include data visualization and data analysis along with report insights. This project aims to predict a person's salary using regression-based supervised learning techniques. The analysis is done by applying several regression models to the salary_data.csv dataset.

Goals:
  1. Perform exploratory data analysis (EDA) to understand data patterns.
  2. Perform data preprocessing such as handling duplicate data, missing values, and encoding categorical variables (this dataset does not have categorical columns).
  3. Build several regression models to predict salary, including Linear Regression, Decision Tree, and Random Forest models.
  4. Evaluate model performance based on training and testing data to understand potential underfitting or overfitting.
  5. Provide results in the form of brief conclusions related to the data models that have been analyzed.

Insights:
  1. Exploratory Data Analysis (EDA)
     <br>There are no missing or duplicate values in the dataset and data preprocessing has been done so that the dataset is ready to be used for model training.

  2. Model Linear Regression
     <br>This simple model shows signs of underfitting because it is not able to explain data variations well. However, this model has a fairly good generalization ability to new data.

  4. Model Decision Tree
     <br>This model performs very well on training data, but fails on testing data. This indicates an overfitting problem.

  5. Model Random Forest
     <br>Although this model also shows a little overfitting, its performance is more stable than Decision Tree and linear regression. This model is quite good at explaining data variations in both training and testing data.

Advices:
  1. Choose the Model that Suits Your Needs
     <br>Use Linear Regression if you need a simple and fast model to use in production, although the predictions may be less accurate. If the focus is on higher accuracy, choose Random Forest with optimized parameter settings.

  2. Improve Model Generalization
     <br>To avoid the overfitting problem in Decision Tree and Random Forest, perform hyperparameter tuning, such as setting the maximum depth of the tree or reducing the number of trees (n_estimators).

  3. Periodic Model Evaluation
     <br>Periodically evaluate the model with new data to ensure that the model remains relevant and can capture the latest patterns from the data.

  4. Add New Variables or Features
     <br>Consider adding variables such as competency, education level, or job location. This can improve salary prediction accuracy by adding important dimensions to the dataset.

  5. Use Additional Data for Training
     <br>If possible, add more data to train the model to produce more accurate and stable predictions.

Should you have any suggestions or feedback, feel free to reach out to me via direct message on LinkedIn or email
<br>email: ahmadihsan506@gmail.com
<br>linkedIn: https://www.linkedin.com/in/ahmadihsan-/ 
