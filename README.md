# Breast Cancer Detection using Logistic Regression
Approximately 70% of data science problems involve classification and logistic regression is a common solution for binary problems. Logistic regression has many applications in data science, but in the world of healthcare, it can really drive life-changing action. This is one of the [SuperDataScience](https://www.superdatascience.com/) machine learning case study course. It shows how to detect breast cancer by applying a logistic regression model on a real-world dataset and predict whether a tumor is benign (not breast cancer) or malignant (breast cancer) based off its characteristics.

## Code and Resources Used 
**Python Version:** 3.7

**Packages:** pandas and sklearn
## The Dataset
Breast Cancer Wisconsin (Original) Data Set. This dataset obtained from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29). Preview of top rows of dataset.

![Top rows](https://github.com/aimanraz/br-ccr-logireg/blob/main/top_rows.JPG?raw=true)

Attribute Information:

* Sample code number: id number
* Clump Thickness: 1 - 10
* Uniformity of Cell Size: 1 - 10
* Uniformity of Cell Shape: 1 - 10
* Marginal Adhesion: 1 - 10
* Single Epithelial Cell Size: 1 - 10
* Bare Nuclei: 1 - 10
* Bland Chromatin: 1 - 10
* Normal Nucleoli: 1 - 10
* Mitoses: 1 - 10
* Class: (2 for benign, 4 for malignant)

![Histogram](https://github.com/aimanraz/br-ccr-logireg/blob/main/histogram.JPG?raw=true)

## Machine Learnin Model Performance
This shows that how well logistic regression able to make prediction for binary classification cases. The model evaluated using the k-fold cross validation. To start prediction, user have to input 9 attributes (excluding id number and true values). 

![Performance analysis](https://github.com/aimanraz/br-ccr-logireg/blob/main/performance.JPG?raw=true)

let the data drive you...and beyond.
