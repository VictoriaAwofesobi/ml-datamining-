# Classification Analysis of the Bank Marketing Dataset

## 📌 Objective
Predict whether a customer will subscribe to a term deposit using classification algorithms. This helps financial institutions optimize marketing efforts.

## 📊 Dataset
- **Source**: UCI Machine Learning Repository
- **Size**: 41,188 instances, 21 attributes
- **Target Variable**: Subscription outcome (`yes` or `no`)

## 🔍 Methods Used
- **Algorithms**: Random Forest, Logistic Regression
- **Library**: scikit-learn
- **Techniques**:
  - One-hot encoding for categorical features
  - Train/Test split (80/20)
  - Confusion matrix for evaluation
  - Feature importance visualization

## 📈 Results
| Metric           | Random Forest | Logistic Regression |
|------------------|---------------|----------------------|
| Accuracy         | 84%           | 88%                  |
| Top Feature      | Duration      | Student Job Feature  |
| Evaluation Tools | Confusion Matrix, Accuracy, F1-Score, Precision, Recall |

## 💼 Business Impact
- Improves campaign targeting
- Enhances resource allocation
- Enables personalized customer offers

## 🔮 Recommendations
- Use Logistic Regression for campaign predictions
- Add engineered features for more accurate outcomes
- Segment users further using clustering for targeted messaging
