# Credit Card Fraud Detection

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Given a highly imbalanced dataset, we apply various preprocessing, feature selection, and modeling approaches to improve fraud detection accuracy.

## Dataset
The dataset contains anonymized credit card transaction records, where:
- **0** represents a legitimate transaction
- **1** represents a fraudulent transaction (only **0.17%** of the dataset)

## Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing & Analysis)
- **Scikit-Learn** (Machine Learning Models)
- **Matplotlib, Seaborn** (Data Visualization)
- **Imbalanced-learn** (Handling Imbalanced Data)

## Approach
1. **Exploratory Data Analysis (EDA)**  
   - Identified key patterns in fraudulent vs. non-fraudulent transactions.
   - Used correlation analysis and visualization techniques to detect influential features.

2. **Data Preprocessing & Feature Engineering**  
   - Scaled numerical features using StandardScaler.
   - Applied **undersampling** to balance class distribution.
   - Selected key features based on feature importance.

3. **Model Training & Evaluation**  
   - Trained models: **Logistic Regression, SVM, K-Nearest Neighbors (KNN)**
   - Optimized hyperparameters using **GridSearchCV**.
   - Evaluated using **Precision-Recall Curve, Confusion Matrix, and ROC-AUC Score**.

## Results
- Achieved **93% recall**, minimizing false negatives for fraud detection.
- Achieved **F1-score of 0.89** and **AUC-ROC of 0.96**.
- Reduced false positives by **18%** through optimized sampling techniques.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Mausham-Sharma/credit-card-fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Credit-Card-Rraud-Detection
   ```
3. Run the Jupyter Notebook or script:
   ```bash
   jupyter notebook
   ```

## Future Improvements
- Implement deep learning models (e.g., LSTMs) for better anomaly detection.
- Deploy the model as an API for real-time fraud detection.

## Contributors
- **Mausham Sharma**  
  [LinkedIn](https://www.linkedin.com/in/mausham-sharma/) | [GitHub](https://github.com/Mausham-Sharma)
