## 🧠 Algorithms Implemented

**Regression:**
- Linear Regression

**Linear Regression Summary**

  | Metric                             | Value            | Interpretation                                                                                                                  |
| ---------------------------------- | -------------------| ------------------------------------------------------------------------------------------------------------------------------- |
| **R² Score**                       | **0.90**           | ✅ The model explains **90.2%** of the variance in the target variable. This indicates a **very good fit**. It mean data predicted by this model will only 10% of from actual data.            |
| **Mean Squared Error (MSE)**       | 49,830,096.86    | ❗ This is the average of squared errors. A high value, but depends on the scale of your target variable.                        |
| **Root Mean Squared Error (RMSE)** | 7,059.04        | ⚖️ This tells us the **average prediction error** in the **same units** as the target. Lower is better.                         |
| **Mean Absolute Error (MAE)**      | **6,286.45      | 🧾 On average, the model's predictions are **6,286 units off** from actual values. MAE is less sensitive to outliers than RMSE. |



**Classification:**
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Naive Bayes



 **Comparison of Classification Algorithm:**

 | Model               | Accuracy | Precision (1) | Recall (1) | F1-Score (1) |
| ------------------- | -------- | ------------- | ---------- | ------------ |
| Logistic Regression | 88%      | 93%           | 73%        | 82%          |
| KNN                 | 92%      | 87%           | 92%        | 89%          |
| Naive Bayes         | 92%      | 94%           | 84%        | 89%          |
| Decision Tree       | 88%      | 88%           | 78%        | 83%          |
| SVM                 | 86%      | 93%           | 68%        | 78%          |



| Metric        | Meaning                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------- |
| **Precision** | Of all predicted positives, how many were actually positive? (↓ if many false positives)                    |
| **Recall**    | Of all actual positives, how many did we catch? (↓ if many false negatives)                                 |
| **F1-score**  | Combines both — tells us how **balanced** our model is in predicting positives **correctly and completely** |


 **Detailed Analysis**
✅ 1. Best Overall Balance → KNN and Naive Bayes
- Accuracy: Both KNN and Naive Bayes have the highest (92%)
- F1-Score (1): Tied at 89%, which shows a good balance between precision and recall
- KNN has slightly higher recall → Better at detecting positives
- Naive Bayes has slightly higher precision → Fewer false positives


## 📊 Datasets Used

- **Regression Dataset**: `Salary_Data.csv`  
  Predicting continuous values (e.g., salary, house price, etc.)

- **Classification Dataset**: `Social_Network_Ads.csv`  
  Predicting categories (e.g., pass/fail, spam/not spam)
