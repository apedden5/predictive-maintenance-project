# predictive-maintenance-project

## Predictive Maintenance of Machinery

This project contains a machine learning system that predicts when machines are likely to fail/ break down in a factory setting.  The goal is to help prevent unexpected breakdowns and support smarter maintenance scheduling.  

I trained two models using PyTorch:

Binary classification: Pass/Fail (1 = yes, 0 = No)

Multiclass classification: If it fails, what type of failure is it (1. Heat Dissipation Failure, 2. Power Failure, 3. Overstrain Failure, 4. Tool Wear Failure, 5. Random Failures?)


The data was cleaned and prepared in Google BigQuery (SQL), then exported to Google Colab for training. I tested different approaches and built custom neural networks in PyTorch, which gave the best results.

98% accuracy for binary model

85% accuracy for multiclass model

Performance was evaluated with confusion matrices and metrics like precision, recall, and F1-score.
These results show that machine failures can be detected early, helping reduce downtime and save costs.
