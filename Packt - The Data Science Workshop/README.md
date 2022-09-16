# Packt: The Data Science Workshop
Link: [The Data Science Workshop](https://courses.packtpub.com/courses/data-science)

## Course Curriculum
---
0. **Workshop Onboarding**
    - Welcome to The Data Science Workshop
    - Installation and Setup
    - Credits
---
1. **Introduction to Data Science in Python**
    - Overview
    - Application of Data Science
    - Overview of Python
        - Exercise 1.01: Creating a Dictionary That Will Contain Machine Learning Algorithms
    - Python for Data Science
        - Exercise 1.02: Loading Data of Different Formats into a pandas DataFrame
    - Scikit-Learn
        - Exercise 1.03: Predicting Breast Cancer from a Dataset Using sklearn
    > Activity 1.01: Train a Spam Detector Algorithm
---
2. **Regression**
    - Overview
    - Simple Linear Regression
        - Exercise 2.01: Loading and Preparing the Data for Analysis
    - The Correlation Coefficient
        - Exercise 2.02: Graphical Investigation of Linear Relationships Using Python
        - Exercise 2.03: Examining a Possible Log-Linear Relationship Using Python
    - The Statsmodels Formula API
        - Exercise 2.04: Fitting a Simple Linear Regression Model Using the Statsmodels Formula API
    - Analyzing the Model Summary
    > Activity 2.01: Fitting a Log-Linear Model Using the Statsmodels Formula API
    - Multiple Regression Analysis
        - Exercise 2.05: Fitting a Multiple Linear Regression Model Using the Statsmodels Formula API
    - Assumptions of Regression Analysis
    > Activity 2.02: Fitting a Multiple Log-Linear Regression Model
    - Explaining the Results of Regression Analysis
---
3. **Binary Classification**
    - Overview
    - Understanding the Business Context
        - Exercise 3.01: Loading and Exploring the Data from the Dataset
    - Testing Business Hypotheses Using Exploratory Data Analysis
        - Exercise 3.02: Business Hypothesis Testing for Age versus Propensity for a Term Loan
    - Intuitions from the Exploratory Analysis
    > Activity 3.01: Business Hypothesis Testing to Find Employment Status versus Propensity for Term Deposits
    - Feature Engineering
        - Exercise 3.03: Feature Engineering ? Exploration of Individual Feature
        - Exercise 3.04: Feature Engineering ? Creating New Features from Existing Ones
    - Data-Driven Feature Engineering
        - Exercise 3.05: Finding the Correlation in Data to Generate a Correlation Plot Using Bank Data
    - Skewness of Data
        - Exercise 3.06: A Logistic Regression Model for Predicting the Propensity of Term Deposit Purchases in a Bank
    > Activity 3.02: Model Iteration 2 ? Logistic Regression Model with Feature Engineered Variables
---
4. **Multiclass Classification with RandomForest**
    - Overview
    - Training a Random Forest Classifier
    - Evaluating the Model's Performance
        - Exercise 4.01: Building a Model for Classifying Animal Type and Assessing Its Performance
    - Number of Trees Estimator
        - Exercise 4.02: Tuning n_estimators to Reduce Overfitting
    - Maximum Depth
        - Exercise 4.03: Tuning max_depth to Reduce Overfitting
    - Minimum Sample in Leaf
        - Exercise 4.04: Tuning min_samples_leaf
    - Maximum Features
        - Exercise 4.05: Tuning max_features
    > Activity 4.01: Train a Random Forest Classifier on the ISOLET Dataset
---
5. **Performing Your First Cluster Analysis**
    - Overview
    - Clustering with k-means
        - Exercise 5.01: Performing Your First Clustering Analysis on the ATO Dataset
    - Interpreting k-means Results
        - Exercise 5.02: Clustering Australian Postcodes by Business Income and Expenses
    - Choosing the Number of Clusters
        - Exercise 5.03: Finding the Optimal Number of Clusters
    - Initializing Clusters
        - Exercise 5.04: Using Different Initialization Parameters to Achieve a Suitable Outcome
    - Calculating the Distance to the Centroid
        - Exercise 5.05: Finding the Closest Centroids in Our Dataset
    - Standardizing Data
        - Exercise 5.06: Standardizing the Data from Our Dataset
    > Activity 5.01: Perform Customer Segmentation Analysis in a Bank Using k-means
---
6. **How to Assess Performance**
    - Overview
    - Splitting Data
        - Exercise 6.01: Importing and Splitting Data
    - Assessing Model Performance for Regression Models
        - Exercise 6.02: Computing the R2 Score of a Linear Regression Model
    - Mean Absolute Error
        - Exercise 6.03: Computing the MAE of a Model
        - Exercise 6.04: Computing the Mean Absolute Error of a Second Model
    - Other Evaluation Metrics
        - Exercise 6.05: Creating a Classification Model for Computing Evaluation Metrics
        - Exercise 6.06: Generating a Confusion Matrix for the Classification Model
    - More on the Confusion Matrix
        - Exercise 6.07: Computing Precision for the Classification Model
    - Recall
        - Exercise 6.08: Computing Recall for the Classification Model
    - F1 Score
        - Exercise 6.09: Computing the F1 Score for the Classification Model
        - Exercise 6.10: Computing Model Accuracy for the Classification Model
        - Exercise 6.11: Computing the Log Loss for the Classification Model
    - Receiver Operating Characteristic Curve
        - Exercise 6.12: Computing and Plotting ROC Curve for a Binary Classification Problem
        - Exercise 6.13: Computing the ROC AUC for the Caesarian Dataset
    - Saving and Loading Models
        - Exercise 6.14: Saving and Loading a Model
    > Activity 6.01: Train Three Different Models and Use Evaluation Metrics to Pick the Best Performing Model
---
7. **The Generalization of Machine Learning Models**
    - Overview
    - Overfitting
        - Exercise 7.01: Importing and Splitting Data
    - Random State
        - Exercise 7.02: Setting a Random State When Splitting Data
    - Cross-Validation
        - Exercise 7.03: Creating a Five-Fold Cross-Validation Dataset
        - Exercise 7.04: Creating a Five-Fold Cross-Validation Dataset Using a Loop for Calls
    - cross_val_score
        - Exercise 7.05: Getting the Scores from Five-Fold Cross-Validation
    - Understanding Estimators That Implement CV
        - Exercise 7.06: Training a Logistic Regression Model Using Cross-Validation
    - Hyperparameter Tuning with GridSearchCV
        - Exercise 7.07: Using Grid Search with Cross-Validation to Find the Best Parameters for a Model
    - Hyperparameter Tuning with RandomizedSearchCV
        - Exercise 7.08: Using Randomized Search for Hyperparameter Tuning
    - Model Regularization with Lasso Regression
        - Exercise 7.09: Fixing Model Overfitting Using Lasso Regression
    - Ridge Regression
        - Exercise 7.10: Fixing Model Overfitting Using Ridge Regression
    > Activity 7.01: Find an Optimal Model for Predicting the Critical Temperatures of Superconductors
---
8. **Hyperparameter Tuning**
    - Overview
    - What Are Hyperparameters?
        - Exercise 8.01: Manual Hyperparameter Tuning for a k-NN Classifier
    - Advantages and Disadvantages of a Manual Search
    - GridSearchCV
        - Exercise 8.02: Grid Search Hyperparameter Tuning for an SVM
    - Advantages and Disadvantages of Grid Search
    - Random Search
        - Exercise 8.03: Random Search Hyperparameter Tuning for a Random Forest Classifier
    - Advantages and Disadvantages of a Random Search
    > Activity 8.01: Is the Mushroom Poisonous?
---
9. **Interpreting a Machine Learning Model**
    - Overview
    - Linear Model Coefficients
        - Exercise 9.01: Extracting the Linear Regression Coefficient
    - RandomForest Variable Importance
        - Exercise 9.02: Extracting RandomForest Feature Importance
    - Variable Importance via Permutation
        - Exercise 9.03: Extracting Feature Importance via Permutation
    - Partial Dependence Plots
        - Exercise 9.04: Plotting Partial Dependence
    - Local Interpretation with LIME
        - Exercise 9.05: Local Interpretation with LIME
    > Activity 9.01: Train and Analyze a Network Intrusion Detection Model
---
10. **Analyzing a Dataset**
    - Overview
    - Exploring Your Data
        - Exercise 10.01: Exploring the Ames Housing Dataset with Descriptive Statistics
    - Analyzing the Content of a Categorical Variable
        - Exercise 10.02: Analyzing the Categorical Variables from the Ames Housing Dataset
    - Summarizing Numerical Variables
        - Exercise 10.03: Analyzing Numerical Variables from the Ames Housing Dataset
    - Visualizing Your Data
        - Exercise 10.04: Visualizing the Ames Housing Dataset with Altair
    > Activity 10.01: Analyzing Churn Data Using Visual Data Analysis Techniques
---
11. **Data Preparation**
    - Overview
    - Handling Row Duplication
        - Exercise 11.01: Handling Duplicates in a Breast Cancer Dataset
    - Converting Data Types
        - Exercise 11.02: Converting Data Types for the Ames Housing Dataset
    - Handling Incorrect Values
        - Exercise 11.03: Fixing Incorrect Values in the State Column
    - Handling Missing Values
        - Exercise 11.04: Fixing Missing Values for the Horse Colic Dataset
    > Activity 11.01: Preparing the Speed Dating Dataset
---
12. **Feature Engineering**
    - Overview
    - Merging Datasets
        - Exercise 12.01: Merging the ATO Dataset with the Postcode Data
    - Binning Variables
        - Exercise 12.02: Binning the YearBuilt Variable from the AMES Housing Dataset
    - Manipulating Dates
        - Exercise 12.03: Date Manipulation on Financial Services Consumer Complaints
    - Performing Data Aggregation
        - Exercise 12.04: Feature Engineering Using Data Aggregation on the AMES Housing Dataset
    > Activity 12.01: Feature Engineering on a Financial Dataset
---
13. **Imbalanced Datasets**
    - Overview
    - Understanding the Business Context
        - Exercise 13.01: Benchmarking the Logistic Regression Model on the Dataset
    - Analysis of the Result
        - Exercise 13.02: Implementing Random Undersampling and Classification on Our Banking Dataset to Find the Optimal Result
    - Analysis
        - Exercise 13.03: Implementing SMOTE on Our Banking Dataset to Find the Optimal Result
        - Exercise 13.04: Implementing MSMOTE on Our Banking Dataset to Find the Optimal Result
    - Applying Balancing Techniques on a Telecom Dataset
    > Activity 13.01: Finding the Best Balancing Technique by Fitting a Classifier on the Telecom Churn Dataset
---
14. **Dimensionality Reduction**
    - Overview
    - Business Context
        - Exercise 14.01: Loading and Cleaning the Dataset
    - Creating a High-Dimensional Dataset
    > Activity 14.01: Fitting a Logistic Regression Model on a High-Dimensional Dataset
    > Activity 14.01: Fitting a Logistic Regression Model on a High-Dimensional Dataset
    - Strategies for Addressing High-Dimensional Datasets
        - Exercise 14.02: Dimensionality Reduction Using Backward Feature Elimination
    - Forward Feature Selection
        - Exercise 14.03: Dimensionality Reduction Using Forward Feature Selection
    - Principal Component Analysis (PCA)
        - Exercise 14.04: Dimensionality Reduction Using PCA
    - Independent Component Analysis (ICA)
        - Exercise 14.05: Dimensionality Reduction Using Independent Component Analysis
    - Factor Analysis
        - Exercise 14.06: Dimensionality Reduction Using Factor Analysis
    - Comparing Different Dimensionality Reduction Techniques
    > Activity 14.02: Comparison of Dimensionality Reduction Techniques on the Enhanced Ads Dataset
---
15. **Ensemble Learning**
    - Overview
    - Ensemble Learning
        - Exercise 15.01: Loading, Exploring, and Cleaning the Data
    > Activity 15.01: Fitting a Logistic Regression Model on Credit Card Data
    - Simple Methods for Ensemble Learning
        - Exercise 15.02: Ensemble Model Using the Averaging Technique
    - Weighted Averaging
        - Exercise 15.03: Ensemble Model Using the Weighted Averaging Technique
    - Iteration 2 with Different Weights
        - Exercise 15.04: Ensemble Model Using Max Voting
    - Advanced Techniques for Ensemble Learning
        - Exercise 15.05: Ensemble Learning Using Bagging
    - Boosting
        - Exercise 15.06: Ensemble Learning Using Boosting
    - Stacking
        - Exercise 15.07: Ensemble Learning Using Stacking
    > Activity 15.02: Comparison of Advanced Ensemble Techniques
---
16. **Machine Learning Pipelines**
    - Overview
    - Pipelines
        - Exercise 16.01: Preparing the Dataset to Implement Pipelines
    - Automating ML Workflows Using Pipeline
        - Exercise 16.02: Applying Pipelines for Feature Extraction to the Dataset
    - ML Pipeline with Processing and Dimensionality Reduction
        - Exercise 16.03: Adding Dimensionality Reduction to the Feature Extraction Pipeline
    - ML Pipeline for Modeling and Prediction
        - Exercise 16.04: Modeling and Predictions Using ML Pipelines
    - ML Pipeline for Spot-Checking Multiple Models
        - Exercise 16.05: Spot-Checking Models Using ML Pipelines
    - ML Pipelines for Identifying the Best Parameters for a Model
        - Exercise 16.06: Grid Search and Cross-Validation with ML Pipelines
    - Applying Pipelines to a Dataset
    > Activity 16.01: Complete ML Workflow in a Pipeline
---
17. **Automated Feature Engineering**
    - Overview
    - Feature Engineering
        - Exercise 17.01: Defining Entities and Establishing Relationships
    - Feature Engineering ? Basic Operations
        - Exercise 17.02: Creating New Features Using Deep Feature Synthesis
        - Exercise 17.03: Classification Model After Automated Feature Generation
    - Featuretools on a New Dataset
    > Activity 17.01: Building a Classification Model with Features that have been Generated Using Featuretools
---
18. **Model as a Service with Flask**
    - Overview
    - Building a Flask Web API
        - Exercise 18.01: Creating a Flask API with Endpoints
    - Deploying a Machine Learning Model
        - Exercise 18.02: Deploying a Model as a Web API
    - Adding Data Processing Logic
        - Exercise 18.03: Adding Data Processing Steps into a Web API
    > Activity 18.01: Train and Deploy an Income Predictor Model Using Flask
---
