# credit-risk-classification

Overview of the Analysis:

To determine whether the historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Olso & Harris Financial conducted a creditworthiness analysis using a data that was trained and evaluated for our credit model. evaluated for our credit model. 

Within our credit model, there were two types of loans: low-risk and high-risk loans. Low-risk loans (0) and High-risk loans are given to consumers. The creditworthiness analysis allowed Olso & Harris Financial to measure creditworthiness based on accuracy, precision, and recall scores.

 

•	Precision measures each label for how many predicted occurrences is correct. For example, how many loans are low-risk (1) or high-risk(0) are actually low or high risk.

•	Recall measures each label for how many actual occurrences are correctly predicted. For example, which loans are actually low risk/high-risk are predicted correctly.

•	F1-Score measures the mean of precision and recall.
•	Confusion Matrix demonstrates the number of the following: true positives, true negatives, false positives, and false negatives for labels.

The Results:

Low-Risk Loans (Healthy Loans): Precision: 1.00 (100% of predicted low-risk loans were correct.) Recall: 1.00 (100% of actual low risk loans were correctly identified). F1-Score: 1.00 (100% balance of precision and recall).

High-Risk Loans (Unhealthy Loans): Precision: 0.87 (87% of predicted low-risk loans were correct.) Recall: 0.95 (95% of actual low-risk loans were correctly identified). F1-Score: 0.91 (100% balance of precision and recall).

Conclusion: This indicates that the logistic regression model predicts that low-risk loans are better than high-risk loans. Higher precision, recall, and F1-Scores mean that in favor of the 0 label.

Recommendation: The creditworthiness model used by Olso & Harris Financial use is closely matched when it comes to low-risk versus high-risk loans. The model slightly favors low-risk loans, which indicates that the model is slightly imbalanced. 
