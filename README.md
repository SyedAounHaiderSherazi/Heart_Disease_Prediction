# 🫀 Heart Disease Prediction using Machine Learning

This is a beginner-friendly machine learning project that predicts the likelihood of heart disease in a patient based on key health indicators. It uses logistic regression and is ideal for showcasing basic ML skills in a resume or portfolio.

---

## 🔍 Problem Statement

Heart disease is a major cause of death globally. Early prediction through machine learning can help in timely treatment and reduce mortality. This project aims to build a simple predictive model using a small dataset.

---

## 📁 Features Used

| Feature    | Description |
|------------|-------------|
| age        | Age of the patient |
| sex        | Gender (0 = Female, 1 = Male) |
| cp         | Chest pain type |
| trestbps   | Resting blood pressure |
| chol       | Serum cholesterol in mg/dl |
| fbs        | Fasting blood sugar > 120 mg/dl |
| restecg    | Resting electrocardiographic results |
| thalach    | Maximum heart rate achieved |
| exang      | Exercise-induced angina |
| oldpeak    | ST depression induced by exercise |
| slope      | Slope of the peak exercise ST segment |
| ca         | Number of major vessels colored by fluoroscopy |
| thal       | Thalassemia indicator |
| target     | Presence (1) or absence (0) of heart disease |

---

## 🤖 Model Used

- **Logistic Regression**: A simple yet effective classification model suitable for binary classification tasks like disease prediction.

---

## 📊 Evaluation Metrics

- Confusion Matrix  
- Classification Report  
- Accuracy Score

> ⚠️ Note: The model shows 100% accuracy on the test set due to the simplified and small dataset used for demonstration purposes only.

---

## 🚀 How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Heart_Disease_Prediction.ipynb
    ```

---

## 🛠 Libraries Used

- Python
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

---

## 🧠 Future Improvements

- Use a full dataset (e.g. UCI Heart Disease Dataset)
- Apply cross-validation
- Add other classification models (Random Forest, XGBoost)
- Build a Streamlit or Flask web app

---

## 📎 License

This project is licensed under the MIT License - feel free to use and modify it.

---

## ✍️ Author

Syed Aoun Haider Sherazi  
[LinkedIn](https://www.linkedin.com/in/syed-aoun-haider-sherazi)  
[GitHub](https://github.com/SyedAounHaiderSherazi)
