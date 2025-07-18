# 📊 Student Performance Predictor

This project uses a machine learning model to predict students' **math scores** based on demographic and academic data such as gender, race/ethnicity, parental education level, lunch type, test preparation course, and reading/writing scores.

---

## 🧠 Technologies Used

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## 🚀 Project Workflow

| Step | Description |
|------|-------------|
| **1** | Load and explore the dataset |
| **2** | Clean and preprocess the data |
| **3** | Visualize data relationships |
| **4** | Encode categorical features |
| **5** | Feature scaling |
| **6** | Train-Test split |
| **7** | Model training (Linear Regression) |
| **8** | Model evaluation |
| **9** | [Optional] Model deployment |
| **10** | Sample prediction with test input |

---

## 📈 Model Overview

- **Model Used:** Linear Regression
- **Target Variable:** Math Score
- **Input Features:** Gender, Race/Ethnicity, Parental Level of Education, Lunch, Test Prep Course, Reading Score, Writing Score

---

## 🔍 Sample Prediction

<details>
<summary>Click to view</summary>

```python
# Sample input for prediction
sample_input = {
    'gender': 'female',
    'race/ethnicity': 'group B',
    'parental level of education': "bachelor's degree",
    'lunch': 'standard',
    'test preparation course': 'completed',
    'reading score': 72,
    'writing score': 78
}

predicted_math_score = predict_scores(sample_input)
print("Predicted Math Score:", predicted_math_score)
# Output: Predicted Math Score: 77.6
