This project applies five supervised machine learning algorithms to the Breast Cancer Wisconsin dataset from sklearn. The objective is to build, evaluate, and compare classification models.

## 1.Load the dataset from Sklearn.

## 2.Preprocessing

- Loaded dataset into a pandas DataFrame.

- Checked for missing values (dataset contains none).

- Performed feature scaling using StandardScaler for algorithms sensitive to magnitude (Logistic Regression, SVM, k-NN).

- Identified and  handled outliers using the IQR method for selected perimeter-related features.

- Data splitting.
  
## 3.Implement Classification Models

 -Logistic Regression
 
 -Decision Tree Classifier

 -Random Forest Classifier

 -Support Vector Machine (SVM)

 -k-Nearest Neighbors (k-NN)

 ## 4.Model Performance evaluation by Accuracy Score.

 -Compare the performance of the five classification algorithms. Find the best and worst model.

 ## Tools & Technologies Used

1. Python 3.10+

2.Jupyter Notebook – for experiment tracking and interactive development

3.Pandas – data loading, exploration, and preprocessing

4.NumPy – numerical computations

5.Matplotlib & Seaborn – data visualization

6.Scikit-learn (sklearn)
