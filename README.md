# The project 1 is an individual project about analyze an automobiles dataset available from the class git repository.
### This data set provides mileage, horsepower, model year, and other technical specifications for cars.
## Part 1 (8 points): Your objective is to perform Exploratory data analysis on the dataset. Complete the following:
### Identify shape and size of the raw data
### Get information about the types of data. Does it need any datatype conversion? If needed perform the conversion. <- chatgpt helps on coverting the horse power variable from string type to float type when error comes up for using .astype function for the conversion
### Drop non-important columns if needed <- chatgpt helps insight on drop the car_name variable column as a string variables non-important for the calculation
### Is the data missing in any of the columns?
### Derive statistical information from the data: can you predict any outliers using this information?
### Perform one-hot encoding of categorical data 
### Visualize the dataset through different univariate and bivariate analysis plots.
### Find correlations between different columns
### Provide your insights on what variables affect the fuel efficiency of automobiles
## Part 2 (7 points): Fit Linear Regression models on the data to predict the fuel efficiency of cars:
### Split the dataset into Training and Test sets
### Fit Linear Regression model on it
### Calculate the accuracy for training and test data
### Which of the above measures is more relevant for this problem statement?
## Part 3 (5 points): Submit a 2 page report with the following:
### What did you do to prepare the data?
### What insights did you get from your data preparation?
### What procedure did you use to train the model?
### How does the model perform to predict the fuel efficiency?
### How confident are you in the model?

#####
# Project 2
### This dataset comprises various features related to a classification problem, with preprocessing steps applied to handle missing values, encode categorical variables, and scale numerical features before training multiple classification models.
## Data Preparation and Model Evaluation

- **Data Preparation:**
  - Checked and dropped missing values, null values, non-numerical, and string values.
  - Encoded categorical string variables and dropped the "breast" variable.
  - Scaled numerical features and analyzed each variable using data plot visualization.

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

