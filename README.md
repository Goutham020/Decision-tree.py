# 🫀 Heart Disease Prediction using Decision Tree and Random Forest

This project uses a heart disease dataset to train machine learning models and predict the likelihood of heart disease. It includes data preprocessing, model training, evaluation, and visualization using **Decision Tree** and **Random Forest** classifiers.

---

## 📁 Dataset

- **Source**: UCI Heart Disease Dataset  
- **File Used**: `heart.csv`
- **Target Variable**: `target` (0 = No disease, 1 = Disease)

---

## 📌 Features

Some of the features included in the dataset:
- `age`: Age of the patient
- `sex`: Gender (1 = male; 0 = female)
- `cp`: Chest pain type (4 values)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: 3 = normal; 6 = fixed defect; 7 = reversible defect

---

## 🚀 Steps Performed

1. **Import Libraries**
2. **Load Dataset**
3. **Explore Data** (Check for missing values and shape)
4. **Split Features and Target**
5. **Train-Test Split**
6. **Train Models**
   - Decision Tree
   - Limited Depth Decision Tree
   - Random Forest
7. **Model Evaluation**
   - Accuracy
   - Classification Report
   - Confusion Matrix
   - Cross-Validation Score
8. **Visualizations**
   - Decision Tree Structure
   - Feature Importances
   - Confusion Matrix Heatmap

---

## 📊 Results

| Model                    | Accuracy (%) |
|-------------------------|--------------|
| Decision Tree           | ~X%          |
| Limited Depth Tree      | ~Y%          |
| Random Forest           | ~Z%          |

> *(Replace X, Y, Z with your actual scores)*

- Random Forest generally performs better due to ensemble averaging.
- Feature importance reveals that `cp`, `thalach`, `oldpeak`, and `ca` are key predictors.

---

## 📦 Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
