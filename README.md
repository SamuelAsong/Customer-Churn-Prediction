# Customer-Churn-Prediction
The project's goal is to help a telecom company understand customer data to predict churn, calculate each customer's lifetime value, and identify factors influencing churn. Achieving these objectives will enable the company to implement targeted strategies to improve retention and maximize profitability.
### Table of Contents


1.  [Business Understanding](#BusinessUnderstanding)
2.  [Data Understanding](#DataUnderstanding)
3.  [Data Preperation](#DataPreperation)
4.  [Modelling](#Modelling)
5.  [Evaluation](#Evaluation)









### Introduction

#### Telecommunication companies face significant challenges with customer retention. The primary problem is to identify which customers are likely to churn (i.e., stop using the service) and understand the factors influencing this behavior. This insight will help in implementing targeted strategies to improve customer retention.


### Business Understanding
    - Problem Statement
    - Goal and Objectives
    - Stakeholders
    - Key Metrics and Success Criteria
    - Hypothesis (Null and Alternate)
    - Analytical Questions
    - Scope and Constraints

### Data Understanding
    1. Importation
    2. Load Dataset
    3. EDA
        1. Data Quality Assessment & Exploring data (info, duplicated, null values, describe)
        2. Univariate
        3. Bi-variate
        4. Multi-variate Analysis 
        5. Test hypothesis
        6. Give your insights
        5. Test hypothesis
        6. Give your insights
### Data Preperation
        1. Split data set into X, y
        2. Split data set into training and evaluation
        3. Feature Engineering (Creating New Features, (binning & bucketing), Handling Missing Data, Encoding, Standardization, 
           Normalization, Scaling)
           a. Create a pipeline to preprocess the data
             1. Separate inpute features into numeric and categorical for different pipelines
             2. Handle missing values using imputation Techniques
             3. Scaling or normalize numeric features
             4. Encode categorical features
             5. Transformations for skewed data (log, power, custom, etc)
             6. Balance dataset (depending on what you see)

### Modelling
        1.   Fit data to the pipeline and train Model
             a.Train Model 1 - Distance based model
             b.Train Model 2 - Gradient Descent model
             c.Train Model 3 - Tree based model
             d.Train Model 4 - Neural Network

### Evaluation
        1. Advance Model Evaluation and Visualizing Model Performance: (ROC curves, AUC, precision-recall curves, and confusion matrices).
        2. Feature Importance and Selection
        3. Hyperparameter Tuning: (GridSearchCV, RandomizedSearchCV, or Bayesian optimization.)
        4. Final Model Comparison & Selection: (Consider trade-offs and choose most apropriate)
        5. Retrain Model with best paramaters
        5. Business Impact Assessment and Documentation of the Model (How does what you choose affect the business?)
        6. Model Persistence     
        







## Acknowledgements
- [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)


- **Azubia Africa / Cohort 7 / Team Guyana  :** I acknowledge our role in conceptualizing, implementing, and documenting this project.

- **Python Community:** I acknowledge the Python community for developing the libraries and tools used in this project, including pandas, scikit-learn, matplotlib, and seaborn.


- **Azubia Africa:** I acknowledge [Azubia Africa](https://www.azubiafrica.org) for providing support and resources for this project.

## License
[MIT](https://choosealicense.com/licenses/mit/)


This project is licensed under the MIT License



