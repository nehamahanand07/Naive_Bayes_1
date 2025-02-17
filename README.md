# Naive_Bayes_1
Breast Cancer Classification Using Gaussian Naïve Bayes (GaussianNB)

Dataset details:

Dataset taken from kaggle. Link    https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset
*Utilized the Breast Cancer Dataset from Kaggle, containing features like radius, texture, perimeter, and more.
*Target Diagnosis:
  M - Malignant 
  B - Benign

🔍 Dataset Exploration:
Conducted thorough data exploration, including checking dataset shape, size, data types, and missing values.
Dropped the non-informative id column to streamline the dataset for analysis.

📊 Data Preprocessing:
*Separated features (X) and target variable (y) for model training.
*Split the dataset into training (70%) and testing (30%) sets using train_test_split with a random state for reproducibility.
*No feature scaling required for GaussianNB, as it inherently assumes a normal distribution for probability calculations.

🤖 Model Implementation:
*Implemented the Gaussian Naïve Bayes (GaussianNB) algorithm for binary classification (Benign vs. Malignant).
*Trained the model on the training dataset and generated predictions for the test set.

📈 Performance Evaluation:
Calculated an accuracy score .
Analyzed the confusion matrix to evaluate true/false positives and negatives.
Visualized the confusion matrix using Matplotlib for better interpretability.
Generated a classification report to assess precision, recall, and F1-score, ensuring a comprehensive evaluation of model performance.

💡 Key Insights:
*GaussianNB proved to be a lightweight yet effective algorithm for this classification task.
*The model performs well overall with high accuracy (94%).
*Class B is slightly better classified than Class M (higher recall).
*Some M instances are misclassified as B, as indicated by the recall gap.
*The weighted and macro averages suggest balanced performance across both classes.
*The model demonstrated strong performance in distinguishing between benign and malignant cases, highlighting its potential for medical diagnostics.
