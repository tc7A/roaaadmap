# Scikit-learn Learning Topics

## 1. Introduction to Scikit-learn
- [Overview of Scikit-learn](#)
- [Installation and setup](#)
- [Key features and API structure](#)

## 2. Data Preparation
- [Loading datasets (e.g., `load_iris`, `load_digits`)](#)
- [Working with custom datasets](#)
- Handling missing values (`SimpleImputer`)
- Scaling and normalization (`StandardScaler`, `MinMaxScaler`)
- Encoding categorical variables (`OneHotEncoder`, `LabelEncoder`)

## 3. Exploratory Data Analysis (EDA)
- Data visualization with Scikit-learn tools
- Feature selection
- Feature engineering
- Correlation analysis

## 4. Supervised Learning
### Regression Models
- Linear regression
- Ridge and Lasso regression
- Polynomial regression
- Decision tree regression
- Random forest regression
- Gradient boosting regression (e.g., XGBoost, AdaBoost)

### Classification Models
- Logistic regression
- k-Nearest Neighbors (kNN)
- Support Vector Machines (SVM)
- Decision trees and random forests
- Gradient boosting classifiers (e.g., XGBoost, AdaBoost)
- Naive Bayes

## 5. Unsupervised Learning
- Clustering algorithms (k-means, DBSCAN, hierarchical clustering)
- Dimensionality reduction (PCA, t-SNE)
- Gaussian mixture models

## 6. Model Selection and Evaluation
- Train-test split
- Cross-validation
- Performance metrics:
  - Regression: `mean_squared_error`, `r2_score`
  - Classification: `accuracy_score`, `f1_score`, `roc_auc_score`
- Hyperparameter tuning (`GridSearchCV`, `RandomizedSearchCV`)

## 7. Pipeline and Workflow Automation
- Creating and using pipelines (`Pipeline` class)
- Feature preprocessing and model training pipelines
- Grid search within pipelines

## 8. Working with Sparse Data
- Sparse matrices
- Handling text data
- Using `CountVectorizer` and `TfidfVectorizer`

## 9. Advanced Topics
- Ensemble methods (bagging, boosting, stacking)
- Feature importance and interpretation
- Semi-supervised learning
- Outlier detection (`IsolationForest`, `EllipticEnvelope`)

## 10. Integration with Other Libraries
- Using Scikit-learn with Pandas for data manipulation
- Visualizing models and data with Matplotlib and Seaborn
- Exporting models (`joblib`, `pickle`)

## 11. Customization and Extensibility
- Writing custom transformers
- Building custom scoring metrics
- Implementing custom models using Scikit-learn API

## 12. Hands-On Projects
- Classification tasks (e.g., spam detection, sentiment analysis)
- Regression tasks (e.g., house price prediction)
- Clustering tasks (e.g., customer segmentation)
- Dimensionality reduction for visualization