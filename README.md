## predictive-maintenance-project
Built predictive maintenance ML models using SQL + PyTorch, reaching strong binary and multiclass accuracy to help detect failures early.

#Predictive Maintenance — Machine Failure Classification

This project builds a machine learning system that predicts when industrial equipment is likely to fail. The goal is to help prevent unexpected breakdowns and support smarter maintenance scheduling.

I trained two models using PyTorch:

Binary classification — Will the machine fail?

Multiclass classification — If it fails, what type of failure is it?

The data was cleaned and prepared in Google BigQuery (SQL), then exported to Google Colab for training. I tested different approaches and built custom neural networks in PyTorch, which gave the best results.

98% accuracy for binary model

85% accuracy for multiclass model

Performance was evaluated with confusion matrices and metrics like precision, recall, and F1-score.
These results show that machine failures can be detected early, helping reduce downtime and save costs.
