# ids-datasets-analysis
Preprocessing and Classification of 2 popular IDS datasets, KDD1999 and CSE-CIC-IDS2018

This repository contains 3 main jupyter notebooks used for dataset analysis and binary classification.
## Notebooks

- [preprocessing-cse-cic-ids2018.ipynb](preprocessing-cse-cic-ids2018.ipynb): Notebook responsible for preparing and pre-processing data from the CSE-CIC-IDS2018 dataset used in model training.

- [kdd1999-preprocessing.ipynb](kdd1999-preprocessing.ipynb): Notebook responsible for preparing and pre-processing data from the KDD-1999 dataset used in training the models.

- [automated-binary-fits-with-hyper-parameter-tuning.ipynb](automated-binary-fits-with-hyper-parameter-tuning.ipynb): Notebook that performs automated training of all Machine Learning models for classifying cyberattacks and generates metrics for analysis.

## Dataset

The datasets used for training and testing the models were [KDD-1999](https://kdd.org/kdd-cup/view/kdd-cup-1999) and [CSE-CIC-IDS2018](https://registry.opendata.aws/cse-cic-ids2018).

## Metrics

The following metrics were used to evaluate the trained classification models:

- Accuracy: proportion of correctly classified instances in relation to the total number of instances.

- Precision: proportion of correctly classified positive instances in relation to the total number of instances classified as positive.

- Recall: proportion of correctly classified positive instances in relation to the total of positive real instances.

- F1-Score: harmonic mean between precision and recall, providing a balanced measure between the two previous metrics.

- ROC-AUC: performance measure used to assess the quality of a binary classification model. The ROC curve is obtained by plotting the true positive rate (TPR or recall) against the false positive rate (FPR or 1 - Specificity) for various values ​​of the classification threshold.

### The notebooks were tested and executed on Kaggle Platform.
