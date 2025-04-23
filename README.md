# Logistic Regression Scaling Accuracy Comparison (Wine Quality Dataset)

This project explores the impact of different feature scaling methods on the performance of **Logistic Regression** using the Wine Quality dataset.

## 📁 Dataset
- Dataset: Wine Quality
- Target Variable: `quality`

## ⚙️ Models and Scaling Techniques
We trained Logistic Regression using different preprocessing scaling methods to observe their effect on model accuracy.

### 📊 Accuracy Comparison:
| Scaling Method       | Accuracy       |
|----------------------|----------------|
| ❌ No Scaling         | 0.755          |
| ⚖️ StandardScaler     | **0.769** ✅ Best |
| 📉 MinMaxScaler       | 0.751          |
| 💪 RobustScaler       | 0.764          |

## 🧠 Insights
- **StandardScaler** gave the best performance, improving accuracy.
- **RobustScaler** was nearly as effective, especially for handling outliers.
- **MinMaxScaler** underperformed slightly.
- **No scaling** still gave a decent baseline, but may raise convergence warnings.

## 📝 How to Run
```bash
# Install requirements
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

## 📷 Visualizations
- KDE plots comparing feature distributions before and after scaling.
- Accuracy comparison charts.

## 🧪 Notebook Includes
- Exploratory Data Analysis
- Feature Scaling
- Train-Test Splitting
- Logistic Regression Model Training
- Accuracy Evaluation
- Plotting Feature Distributions

## 📎 Conclusion
Scaling is an essential preprocessing step that can significantly impact model performance. In this experiment, **StandardScaler** performed best with **Logistic Regression**.

---

Feel free to fork this repo and try out other models or datasets!

## 🔗 Connect With Me
- LinkedIn: [Your LinkedIn URL Here]
- GitHub: [Your GitHub Profile URL Here]

