Salary Prediction Using Machine Learning (Regression)
Description
This project aims to predict Salary Estimates based on other features such as Job Title, Rating, Location, Industry, and more. The dataset contains 4,282 records with various attributes related to companies, job positions, and organizational details. The analysis involves cleaning, preprocessing, feature selection, and applying regression models such as Random Forest, MLP, KNN, and Linear Regression to build predictive models.
Dataset
The dataset includes the following features:
•	Job Title (object)
•	Salary Estimate (object, target variable)
•	Rating (float64)
•	Location (object)
•	Size (object)
•	Founded (int64)
•	Type of Ownership (object)
•	Industry (object)
•	Sector (object)
•	Revenue (object)
________________________________________
Data Distribution of salary via Revenue
•	showing the distribution of Salary Estimate feature to Revenue
 
________________________________________
Preprocessing Steps
1.	Data Cleaning:
o	Removed invalid entries, such as -1 values.
o	Converted categorical features to numerical representations using encoding techniques.
o	Cleaned and standardized Salary Estimate and other numerical fields.
2.	Feature Engineering:
o	Transformed Salary Estimate into numerical values for regression analysis.
o	Removed less informative features (e.g., Company).
3.	Normalization:
o	Scaled numerical features to standardize ranges, enabling better model performance.
4.	Feature Selection:
o	Analyzed feature correlation to identify attributes with the highest impact on salary prediction.
o	Features such as Revenue and Location were found to have the strongest correlation with salary.
________________________________________
Feature Correlation
•	to visualize the correlation between features and highlight how Revenue and Location are strongly related to Salary Estimate.
 
________________________________________
Models Used
The following machine learning regression models were implemented:
1.	Random Forest Regressor
2.	Multi-Layer Perceptron (MLP) Regressor
3.	K-Nearest Neighbors (KNN) Regressor
4.	Linear Regression
________________________________________
Results

Model Comparison
The following regression models were compared, and their performances were summarized:
Model	MAE	RMSE	R² Score
Random Forest Regressor	5.21	7.12	0.89
MLP Regressor	5.67	7.55	0.86
KNN Regressor	6.23	8.01	0.84
Linear Regression	6.87	8.45	0.81
Random Forest Regressor provided the best performance in predicting salaries.
________________________________________
Predicted vs. Actual Salary
•	a scatter plot below is comparing predicted vs. actual salaries, with a reference line to show how well the models performed.
 
License
This project is licensed under the dataroadmap (IBM) License. See the LICENSE file for more details.

