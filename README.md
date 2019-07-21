# Heart-Disease-Classification
Creating a Classification Model in Apache Spark with Scala

Model uses the `datasets/Heart.csv` dataset (credit: ISLR) to build a binary classification model to predict whether or not the patient has heart disease (`AHD`) given the following features:

- `Age`
- `Sex`
- `ChestPain`
- `RestBP`
- `Chol`
- `Fbs`
- `RestECG`
- `MaxHR`
- `ExAng`
- `Oldpeak`
- `Slope`
- `Ca`
- `Thal`

## Train/Test split
As part of the coursework, everyone in the class did an 80/20 split of the data and input **42** as the random seed. This allowed us to compare accuracy scores of different models on an apples to apples basis. 

# Published Notebook
My databricks notebook can be found [here](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8269972537251933/4391435069137660/7272513819797709/latest.html).

# Accuracy Score
Using a Random Forrest Classifier with 40 trees, a max depth of 5 and a minimum instance per node of 1, my models accuracy was: 
### 91.1%
