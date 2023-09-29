# Credit Card Churn Prediction Project

## Overview

This repository contains the code and documentation for a data science project focused on predicting credit card churn while addressing the challenge of imbalanced data. In the credit card industry, accurate customer retention prediction is crucial, and imbalanced datasets can hinder predictive accuracy. The project aims to develop a method that skillfully balances datasets using a combination of undersampling, oversampling, and hybrid sampling techniques.

## Project Details

### Exploratory Data Analysis

- Conducted comprehensive exploratory data analysis (EDA) to understand the significance and relevance of customer attributes in relation to churn.
- Utilized chi-square test statistics to identify key variables affecting churn, including gender, education level, marital status, income category, and card category.

### Machine Learning Preparation

- Standardized the dataset for uniform scaling to prepare it for machine learning algorithms.
- Focused on numerical variables, essential for algorithms utilizing mean and distance calculations, while excluding categorical variables.

### Sampling Algorithms

#### Oversampling

- Amplified minority class instances through triple instance sampling, mean value computation, and an iterative approach.

#### Undersampling

- Enhanced dataset balance and decision boundaries through mean vector calculation, distance sorting, and targeted removal.

#### Hybrid Sampling

- Balanced class representation while reducing majority class instances through augmentation and reduction techniques.

### Results

- **Undersampling:** Logistic regression's minority class recall increased from 0.52 to 0.83, with the decision tree achieving an impressive recall score of 0.94.
- **Oversampling:** Logistic regression's minority class recall rose from 0.52 to 0.78, while the decision tree improved by 3%.
- **Hybrid Sampling:** The decision tree's recall increased from 0.76 to 0.87, maintaining a strong majority class recall.

## Conclusion

- Undersampling improved minority class recall but raised concerns about majority class information loss.
- Oversampling exhibited trade-offs, introducing noise and redundancy.
- Hybrid sampling emerged as a promising approach, effectively balancing class representation and accuracy.
- The decision tree consistently performed well, making it an ideal choice for practical applications in credit card churn prediction.

## Repository Contents

- `/code`: Contains the project code and Jupyter notebooks.
- `/data`: Includes the dataset used for analysis.
- `/results`: Stores the project's results and visualizations.
- `/docs`: Contains documentation related to the project.

## Contact

For any inquiries or collaborations, please contact [Harishankr Nagar](mailto:harishankar2@gmail.com).

