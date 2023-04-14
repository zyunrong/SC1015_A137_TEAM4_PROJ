# SC1015_A137_TEAM5_PROJ

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the breast cancer dataset from [Kaggle](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)
  
## Contributors

- Zhang Yun Rong 
- Tan Guan Ying Xavier
- Karl Maersk Mc-Kinney Soerensen 
  All been equally involved in each aspect of the project.

## Problem Definition

- Are we able to predict if breast cancer tumors are malignant (cancerous) or benign (non cancerous) based on its attributes?
- Which model would be the best to predict it?

## Models Used

1. Logistic Regression
2. Decision Tree
3. Random Forest Classifier

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score
