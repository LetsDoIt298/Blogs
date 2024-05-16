# Blogs


1) Different measures of Performance metrics and when to use which?
   ![image](https://github.com/LetsDoIt298/Blogs/assets/90137904/042042ea-68c0-446d-b8ff-44dc8f608f60)



# Supervised Learning:
## Regression Metrics:
•	Mean Squared Error (MSE) <br>
•	Root Mean Squared Error (RMSE) <br>
•	Mean Absolute Error (MAE) <br>
•	R-squared (Coefficient of Determination) <br>
•	Mean Absolute Percentage Error (MAPE) <br>
•	Median Absolute Error <br>
•	Explained Variance Score <br>
•	Relative Squared Error <br>
•	Root Mean Squared Logarithmic Error (RMSLE)

## Classification Metrics:
•	Accuracy <br>
•	Precision <br>
•	Recall (Sensitivity) <br>
•	F1-score <br>
•	ROC-AUC (Receiver Operating Characteristic - Area Under the Curve) <br>
•	Precision-Recall AUC <br>
•	Confusion Matrix <br>
•	Cohen's Kappa <br>
•	Matthews Correlation Coefficient (MCC) <br>
•	Log Loss (Cross-entropy loss) <br>
# Unsupervised Learning:
## Clustering Metrics:
•	Silhouette Score <br>
•	Davies–Bouldin Index <br>
•	Calinski-Harabasz Index <br>
•	Dunn Index <br>
•	Adjusted Rand Index <br>
•	Normalized Mutual Information (NMI) <br>
•	Homogeneity, Completeness, and V-measure <br>
•	Jaccard Coefficient

## Mean Squared Error (MSE)
•	Use When: You want to penalize larger errors more significantly.
•	Characteristics: MSE calculates the average of the squares of the errors (the difference between the actual and predicted values). It's sensitive to outliers because the errors are squared.

Root Mean Squared Error (RMSE)
Use When: Similar to MSE, but you want the error metric to have the same units as the original data.
Characteristics: RMSE is the square root of MSE. It is also sensitive to large errors/outliers and is useful when you want to compare errors in the same unit as the target variable.

Mean Absolute Error (MAE)
Use When: You want a straightforward interpretation of the average error without penalizing larger errors disproportionately.
Characteristics: MAE calculates the average of the absolute errors. It is less sensitive to outliers compared to MSE and RMSE.

R-squared (Coefficient of Determination)
Use When: You want to understand the proportion of variance in the dependent variable that is predictable from the independent variables.
Characteristics: R-squared ranges from 0 to 1 and indicates how well data fit a statistical model – the higher the R-squared, the better the model explains the variability of the response data.

Mean Absolute Percentage Error (MAPE)
Use When: You need a measure of prediction accuracy in percentage terms.
Characteristics: MAPE calculates the average absolute percentage error between actual and predicted values. It is scale-independent and useful for comparing forecasting errors across different scales but can be problematic when actual values are close to zero.

Median Absolute Error
Use When: You want a robust measure of central tendency that is less affected by outliers.
Characteristics: This metric calculates the median of the absolute errors. It provides a more robust measure of the central tendency of the errors compared to MAE.

Explained Variance Score
Use When: You need to understand how much of the variance of the target variable is explained by the model.
Characteristics: Similar to R-squared but can be negative in some cases when the model performs worse than a constant mean predictor.

Relative Squared Error
Use When: You want to compare the squared error of the model to the squared error of a simple model (e.g., mean predictor).
Characteristics: It is a relative measure that indicates how well the model performs compared to a baseline.

Root Mean Squared Logarithmic Error (RMSLE)
Use When: You want to measure the ratio between actual and predicted values and are particularly concerned with relative errors and when dealing with exponential growth.
Characteristics: RMSLE calculates the square root of the mean squared logarithmic errors. It is less sensitive to outliers and more appropriate when the data has exponential growth patterns.

Summary of Usage Contexts:
MSE/RMSE: When larger errors should be penalized more heavily.
MAE: When you need a simple, interpretable measure that treats all errors equally.
R-squared: When you need a proportion measure of explained variance.
MAPE: When percentage errors are more meaningful.
Median Absolute Error: When robustness to outliers is important.
Explained Variance Score: When comparing the variance explained by the model to total variance.
Relative Squared Error: When you need a baseline comparison.
RMSLE: When the model errors and data are on an exponential scale.


For More info regarding all the metrices follow :-
[link](https://neptune.ai/blog/performance-metrics-in-machine-learning-complete-guide)
