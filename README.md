
# Predictive Maintenance of Machinery

This project contains a machine learning system that predicts when machines are likely to fail/ break down in a factory setting.  The goal is to help prevent unexpected breakdowns and support smarter maintenance scheduling.  

## Models:

two different models were trained with PyTorch:

- Binary classification: Predicts failure (1 = yes, 0 = No)
- Multiclass classification: If it fails, what type of failure is it?


The data was cleaned and prepared in Google BigQuery (SQL), then exported to Google Colab for training. I tested different approaches and built custom neural networks in PyTorch, which gave the best results.

## Results:

- 98% accuracy for binary model
- 85% accuracy for multiclass model

Performance was evaluated with confusion matrices and metrics like accuracy, precision, recall, and F1-score as well.  You can find more detail on these metrics in the report or models provided in the repository.  These results show that machine failures can be detected early, helping reduce downtime and save costs.  

## Tools used:

- Python
- PyTorch
- Google Colab
- BigQuery
- GCS

- ## Project Files:
  
- `Final_Project_Machine_Maintenance_Report.pdf` = Full project report
- `Final_Project_Binary_Classification.ipynb` = Binary model notebook
- `Final_Project_Multi_Classification.ipynb` = Multiclass model notebook
- `BinaryTrain` = Clean binary training set
- `BinaryTest` = Clean binary test set
- `MultiClassTrain` = Clean multiclass training set
- `MultiClassTest` = Clean multiclass test set
  
## How to Run:

1. Open notebooks in Google Colab or Jupyter
2. Install dependencies
3. Run each cell to train/test models

> Note: the clean binary and multiclass test and train datasets are located in the repository.  The original uncleaned dataset is located on kaggle.

> Original Dataset: https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

