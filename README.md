## Fraud Detection Analysis Project

### Table of Contents
1. [Overview](#overview)
2. [Data Preprocessing](#data-preprocessing)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Model Training and Evaluation](#model-training-and-evaluation)
5. [Results](#results)
6. [Conclusion](#conclusion)
7. [Future Work](#future-work)
8. [Kaggle Dataset Link](#kaggle-dataset-link)

### Overview
This project aims to detect fraudulent online payments using a dataset from Kaggle. It involves data preprocessing, exploratory data analysis (EDA), training multiple machine learning models, and evaluating their performance.

### Data Preprocessing
1. **Import Libraries**: Necessary libraries for data manipulation, visualization, and modeling are imported.
2. **Load Data**: The dataset is loaded into a pandas DataFrame.
3. **Data Cleaning**: Missing values are handled, and unnecessary columns are dropped.
4. **Feature Encoding**: Categorical features are encoded for model compatibility.

### Exploratory Data Analysis (EDA)
1. **Data Inspection**: Initial inspection of the dataset to understand its structure, shape, and data types.
2. **Missing Values Check**: Verification of missing values and appropriate handling if found.
3. **Outlier Detection**: Visualized using box plots to identify any outliers in the dataset.
4. **Feature Distribution**: Count plots to analyze the distribution of different categories within the 'type' feature.
5. **Correlation Analysis**: Heatmap to visualize the correlation between different features.
6. **Scatter Plot**: Relationship between 'oldbalanceOrg' and 'newbalanceOrig'.

### Model Training and Evaluation
Three models are trained and evaluated:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Naive Bayes**

#### Steps:
1. **Data Splitting**: The dataset is split into training and testing sets.
2. **Data Standardization**: Features are scaled using StandardScaler.
3. **Model Training**: Each model is trained on the scaled training data.
4. **Model Evaluation**: Performance metrics (accuracy, precision, recall, F1 score, ROC-AUC) are calculated. Confusion matrices and classification reports are generated for each model.

### Results
- **Logistic Regression**: Detailed performance metrics including accuracy, precision, recall, F1 score, and ROC-AUC score.
- **Decision Tree Classifier**: Performance evaluation and visualization.
- **Naive Bayes**: Evaluation and comparison with other models.
- **Summary**: A comparison table and pie charts of the performance metrics for visual representation.

### Conclusion
The project demonstrates the application of data preprocessing, EDA, and machine learning techniques to detect fraudulent transactions in online payments. The results highlight the effectiveness of different models and their comparative performance.

### Future Work
- Enhance feature engineering for better model performance.
- Explore advanced models like ensemble methods.
- Implement real-time fraud detection systems.

### Kaggle Dataset Link
The dataset used for this project can be found [here](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset/data).
