# Customer-Segmentation-for-an-Automobile-Company
Helping the Automobile Company to tailor the right message to the right customers.
-	Data Preprocessing: Handles missing values and encoded categorical variable, scaled numerical features to standardize data distribution and split the data into training and validation sets.
-	Modeling: Implemented and compared three machine learning models: Tuned RandomForest, GradientBoosting, and XGBoost. Performed hyperparameter tuning using GridDearchCV to optimize model performance and evaluated models based on validation accuracy and detailed classification reports.
-	Results:
	Tuned RandomForestClassifier: 
	Validation Accuracy: 53.2%
o	Key Metrics:
Precision: 45% for Segment A, 43% for Segment B, 52% for Segment C, and 65% for Segmented D.
Recall: 44% for Segmented A, 33% for Segment B, 57% for Segment C, and 74% for Segment D.
F1-Score: 45% for Segment A, 37% for Segment B, 54% for Segment C, and 69% for Segment D.
	GradientBoostingClassifier:
	Valiadtion Accuracy: 52.9%
	Similar performance across segments with slightly lower recall and precision that RandomForest.
	XGBoostClassifier:
	Validation Accuracy: 51.3%
	Lower Overall performance compared to RandomForest and GradientBoosting.

