# Project 1 

The project entails analyzing an automobile dataset sourced from the class git repository, containing information such as mileage, horsepower, model year, and other technical specifications for cars.

### Part 1: Exploratory Data Analysis
- Identify the shape and size of the raw data.
- Examine data types and perform datatype conversion as needed, such as converting horsepower variable from string to float type.
- Drop non-important columns, e.g., car_name, which are irrelevant for the calculation.
- Check for missing data in any columns.
- Derive statistical information to identify outliers.
- Perform one-hot encoding of categorical data.
- Visualize the dataset through various univariate and bivariate analysis plots.
- Analyze correlations between different columns.
- Provide insights into variables affecting fuel efficiency.

### Part 2: Linear Regression Modeling
- Split the dataset into Training and Test sets.
- Fit Linear Regression model.
- Calculate accuracy for both training and test data.
- Determine the most relevant measure for this problem statement.

### Part 3: Report
Submit a 2-page report covering:
- Data preparation steps.
- Insights gained from data preparation.
- Model training procedure.
- Model performance in predicting fuel efficiency.
- Confidence level in the model's predictions.


#####
# Project 2
This dataset comprises various features related to a classification problem, with preprocessing steps applied to handle missing values, encode categorical variables, and scale numerical features before training multiple classification models.
## Data Preparation and Model Evaluation

- **Data Preparation:**
  - Checked and dropped missing values, null values, non-numerical, and string values.
  - Scaled numerical features and analyzed each variable using data plot visualization.
  - Encoded categorical string variables and dropped the "breast" variable.

- **Model Training Techniques:**
  - Employed various classification supervised learning techniques:
    - Logistic regression
    - Decision trees
    - Random forests
    - K-nearest neighbor classifiers.
  - Used hyperparameter tuning techniques like grid search or random search.

- **Model Performance Evaluation:**
  - K Nearest Neighbor (KNN) and Logistic Regression classifier accuracy: 0.87.
  - Random Forest Classifier and Decision Tree Classifier accuracy: 0.98.
  - Logistic Regression and KNN showed similar performance, while Random Forest and Decision Tree outperformed in capturing underlying patterns.

