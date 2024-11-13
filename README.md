# Customer Segmentatiom for an Automobile Company

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Approach](#approach)

### Project Overview

The primary goal is to predict the customer (A, B, C, D) for the new potential customers based on their demographic and behavioral characteristics. This segmentation will allow the automobile company to tailor their marketing strategies effectively, ensuring that they reach the right customers with the right messages. Data Source: Kaggle.

### Data Sources

Customer Segmentatiom for an Automobile Company Dataset: The primary dataset used for this project is the " Train.CSV" and "Test.CSV" files, containing datails about the customers of the Company.

### Tools

- Python Programming Langauge: Using Libraries like; Pandas, Numpy, Sklearn, Xgboost.
 
### Approach
-	Data Preprocessing: Handles missing values and encoded categorical variable, scaled numerical features to standardize data distribution and split the data into training and validation sets.
-	Modeling: Implemented and compared three machine learning models: Tuned RandomForest, GradientBoosting, and XGBoost. Performed hyperparameter tuning using GridDearchCV to optimize model performance and evaluated models based on validation accuracy and detailed classification reports.
-	Results:
- Tuned RandomForestClassifier: 
  - Validation Accuracy: 53.2%
  - Key Metrics:
       - Precision: 45% for Segment A, 43% for Segment B, 52% for Segment C, and 65% for Segmented D.
       - Recall: 44% for Segmented A, 33% for Segment B, 57% for Segment C, and 74% for Segment D.
       - F1-Score: 45% for Segment A, 37% for Segment B, 54% for Segment C, and 69% for Segment D.
- GradientBoostingClassifier:
  - Valiadtion Accuracy: 52.9%
  - Similar performance across segments with slightly lower recall and precision that RandomForest.
- XGBoostClassifier:
  - Validation Accuracy: 51.3%
  - Lower Overall performance compared to RandomForest and GradientBoosting.
