# DataMining-Individual-Project
Practices on decision tree, KNN, NB, Perceptron and SVM with and without importing packages

## Classification models based on Dataset

In this project, several classification models included Decision Tree, KNN, Naive Bayes, Perceptron and SVM will be shown. You can use these models to predict the test data based on trained dataset. You can use Jupyter notebook, Pycharm or Spyder to run. In order to use these models easily, here the brief guideline is shown.

### Prerequisites
***Dataset.xlsx*** is under **the same directory** as the models
<br>
***numpy, pandas libraries*** are needed
<br>
***sklearn library*** should be prepared
<br>
- <font size=4>Install scikit-learn using ``conda install -c anaconda scikit-learn ``</font>

### Imported libraries
To run each model, make sure the following libraries are imported.
-<font size=5> ``import pandas as pd``</font>
<br>
-<font size=5> ``import numpy as np``</font>
<br>
-<font size=5> ``from sklearn.svm import SVC`` </font>
<br>
-<font size=5> ``from sklearn.model_selection import train_test_split`` </font>
<br>
-<font size=5> ``from sklearn import metrics``</font>
<br>
-<font size=5> ``from sklearn.metrics import confusion_matrix``</font>
<br>
-<font size=5> ``from matplotlib import pyplot as plt``</font>

### Imported dataset
-<font size=5> ``excel = "Dataset.xlsx"``</font>

### Run the model
Run the model in section <font size=5>``Test model here!!``</font>, then you can create model in <font size=5>``Train model here!``</font> and get the predicted data in <font size=5>``Use model here!``</font>

It is **not necessray** to run <font size=5>``interpretation``</font> section.
<br>
This section is for illustration!

### Import the predicted value
Since Decision Tree has the best performance among these classification model, we store its predicted value as final result, which save in an copy file <font size=5>``Dataset_finalresult.xlsx``</font>
<br><br>
<font size=5>``Dataset.xlsx``</font> is to test and find the model
