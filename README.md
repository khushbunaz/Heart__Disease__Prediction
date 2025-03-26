# ❤️ Heart Disease Prediction

## 📌 Overview
This project utilizes **Machine Learning** to predict whether a person is suffering from **heart disease**. The dataset is sourced from **Kaggle's UCI Heart Disease dataset** ([link](https://www.kaggle.com/ronitf/heart-disease-uci)). By applying **K-Nearest Neighbors (KNN), Decision Tree, and Random Forest classifiers**, the model aims to make accurate predictions.

## 📊 Dataset
- **Source**: UCI Heart Disease Dataset (via Kaggle)
- **Size**: 303 entries
- **Features**:
  - Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol Level (chol), Fasting Blood Sugar (fbs), Resting ECG (restecg), Maximum Heart Rate (thalach), Exercise-Induced Angina (exang), Oldpeak, Slope, CA, Thal, Target (Heart Disease presence)

## 🏗️ Workflow
1. **Data Preprocessing**
   - Handling categorical variables
   - Feature scaling
2. **Exploratory Data Analysis (EDA)**
   - Heatmaps, histograms, and distribution plots
3. **Model Selection & Training**
   - **K-Nearest Neighbors (KNN)**
   - **Decision Tree Classifier**
   - **Random Forest Classifier**
4. **Evaluation**
   - Cross-validation & accuracy comparison

## 🖥️ Installation & Usage
### 📌 Prerequisites
Ensure you have **Python 3.x** installed with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 🚀 Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd heart-disease-prediction
   ```
3. Run the Python script:
   ```bash
   python heart_disease_prediction.py
   ```

## 🏆 Results
- **K-Nearest Neighbors (KNN) Accuracy**: **85.07%**
- **Random Forest Accuracy**: **81.99%**

## 📌 Future Improvements
- Implement **Deep Learning (Neural Networks)**
- Hyperparameter tuning for better accuracy
- Deploy as a web app

## 📜 License
This project is **open-source** under the MIT License.

## 🤝 Contribution
Feel free to fork, improve, and submit pull requests!

---

🚀 **Early Detection. Better Health. Smarter AI.**

