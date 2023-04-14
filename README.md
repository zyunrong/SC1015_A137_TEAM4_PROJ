# SC1015_A137_TEAM5_PROJ

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the breast cancer dataset from [Kaggle](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction](https://github.com/zyunrong/SC1015_A137_TEAM5_PROJ/blob/main/Data%20Extraction.ipynb)
2. [Data Visualization](https://github.com/zyunrong/SC1015_A137_TEAM5_PROJ/blob/main/Data%20Visualization.ipynb)
3. [Machine Learning Models](https://github.com/zyunrong/SC1015_A137_TEAM5_PROJ/blob/main/Machine%20Learning%20Models.ipynb)

## Contributors

- Karl Maersk Mc-Kinney Soerensen 
- Tan Guan Ying Xavier
- Zhang Yun Rong

  All been equally involved in each aspect of the project.

## Problem Definition

- Are we able to predict if breast cancer tumors are malignant (cancerous) or benign (non cancerous) based on its attributes?
- Which model would be the best to predict it?

## Models Used

1. Logistic Regression
2. Decision Tree
3. Random Forest Classifier

## Conclusion

- We identified 6 variables with the highest correlation to diagnosis, being Radius_Mean, Perimeter_Mean, Area_Mean, Compactness_Mean, Concavity_Mean and Concave Points_Mean
- Logistic Regression Model has high accuracy(93%) but a low TPR(85%)
- Decision Tree has a high accuracy as well(92%)
- Random Forest Classifier has the highest accuracy(96%) and a high TPR(92%)
- Random Forest Classifier is the best model to predict if breast cancer tumors are malignant or benign
- Yes, it is possible to predict if a tumor if malignant or benign with acceptable amount of accuracy and low wrong diagnosis rate(1-TPR and FPR)

## What did we learn from this project?
- The use of random state in data splitting
- Use of pairplot to identify and extract variables with high correlation
- Logistic Regression from sklearn
- Random Forest Classification from sklearn
- Learning how to use github
- Classification report using precision, recall, f1-score and support

## References

- <https://www.kaggle.com/code/fareselmenshawii/breast-cancer-various-models>
- <https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset>
- <https://www.kaggle.com/code/kanuriviveknag/breast-cancer-prediction#Thus-Breast-cancer-prediction-using-RandomforestClassifier-,obtained-the-accuracy-of-96%>
- <https://towardsdatascience.com/breast-cancer-cell-type-classifier-ace4e82f9a79>
