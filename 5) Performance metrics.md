# List of Performance Metrics:-
1) Accuracy
2) Precision
3) Recall (Sensitivity)
4) F1 Score
5) Area Under the Receiver Operating Characteristic Curve (AUC-ROC)

# Brief discription:-
## Accuracy:
The proportion of correctly predicted instances out of the total instances. It's useful for balanced datasets but may be misleading for imbalanced classes.

## Precision:
The proportion of true positive predictions out of all positive predictions made by the model. It indicates how many of the predicted positive instances are actually positive.

## Recall (Sensitivity):
The proportion of true positive predictions out of all actual positive instances. It measures the model's ability to find all relevant instances in the dataset.

## F1 Score:
The harmonic mean of precision and recall. It's useful for balancing the trade-off between precision and recall, especially in imbalanced datasets.

## Area Under the Receiver Operating Characteristic Curve (AUC-ROC):
The area under the ROC curve, which plots the true positive rate against the false positive rate at various threshold settings. It provides an aggregate measure of performance across all classification thresholds.


# When do we use which metrics?
Accuracy:
When to Use: Accuracy is ideal for problems where the classes are balanced, meaning each class has a similar number of instances. For example, if you’re evaluating a model that predicts customer churn and you have a roughly equal number of churned and non-churned customers, accuracy provides a straightforward measure of performance.
Example: You’re running a model to categorize products as high or low risk for a quality control process, and you have an equal number of high and low-risk products.
Precision:

When to Use: Use precision when the cost of false positives is high. Precision helps you understand how many of the predicted positive outcomes are actually true positives, which is important when you want to minimize incorrect positive predictions.
Example: In a fraud detection system, where falsely identifying a legitimate transaction as fraudulent could cause customer dissatisfaction or operational disruption, high precision ensures that only genuine fraud cases are flagged.
Recall:

When to Use: Recall is important when the cost of missing positive instances is high. It tells you how many of the actual positives were correctly identified by the model, which is crucial when it’s important not to overlook any relevant cases.
Example: For a model predicting potential customer leads, high recall is essential if missing a lead means losing out on potential sales. You want to capture as many potential leads as possible, even if it means some may be false positives.
F1 Score:

When to Use: Use the F1 Score when you need a balance between precision and recall and when you have an imbalanced dataset. It provides a single metric that combines both precision and recall, which helps in situations where neither metric alone is sufficient.
Example: In a customer support ticket classification system, where you need a balance between correctly identifying high-priority tickets (recall) and ensuring those identified are indeed high-priority (precision), the F1 Score gives you a balanced view.

