# **AI-Powered Disease Prediction System**

## **Project Overview**
The **AI-Powered Disease Prediction System** is a machine learning-based web application designed to predict five common diseases: **Diabetes, Heart Disease, Parkinson’s Disease, Lung Cancer, and Thyroid Disorders**. The system uses **pre-trained machine learning models** and provides real-time predictions based on user inputs.

## **Disease Prediction Models**

### **1. Diabetes Prediction**
- Uses **Logistic Regression** and **Random Forest** models.
- Predicts diabetes risk based on features such as glucose levels, BMI, and insulin levels.

### **2. Heart Disease Prediction**
- Predicts the likelihood of heart disease using medical and lifestyle factors.
- Features include **age, cholesterol, ECG results, and exercise habits**.

### **3. Thyroid Disease Prediction**
- Uses **preprocessed datasets** to predict **hypothyroidism and hyperthyroidism**.
- Key features include **TSH, T3, and T4 hormone levels**.

### **4. Parkinson’s Disease Prediction**
- Predicts Parkinson’s risk from **voice measurements**.
- Features include **frequency, jitter, shimmer, and other speech parameters**.

### **5. Lung Cancer Prediction**
- Predicts lung cancer risk based on **smoking history and respiratory symptoms**.
- Uses machine learning models to analyze patient data.

---

## **Why This System is Important**
- **Improved Accuracy**: AI models identify patterns that are difficult for human analysis.
- **Real-Time Predictions**: Users receive instant results.
- **Accessibility**: Makes diagnostic tools available in underserved areas.
- **Cost-Effective**: Reduces unnecessary tests and improves diagnosis efficiency.

---

## **Installation**
Follow these steps to set up and run the project:

### **Step 1: Clone the Repository**
```bash
https://github.com/YourGitHubRepo/Disease-Prediction-System
git clone Disease-Prediction-System
```

### **Step 2: Set Up Virtual Environment**
```bash
python -m venv env
source env/bin/activate  # macOS/Linux
.\env\Scripts\activate  # Windows
```

### **Step 3: Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Step 4: Run the Application**
```bash
streamlit run app.py
```

---

## **Technologies Used**
- **Python**: Core programming language.
- **Streamlit**: Interactive UI framework.
- **Scikit-learn**: ML models for disease prediction.
- **Pandas & NumPy**: Data processing and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **GitHub**: Version control and project collaboration.

---

## **Dataset**
This project uses multiple datasets, each corresponding to a specific disease. All datasets have been preprocessed for accuracy.

### **1. Diabetes Dataset**
- Features: Glucose, BMI, Blood Pressure, Insulin Levels, Age.

### **2. Heart Disease Dataset**
- Features: Cholesterol, Resting Blood Pressure, Heart Rate, ECG Results.

### **3. Thyroid Disease Dataset**
- Features: TSH, T3, T4 Hormone Levels.

### **4. Parkinson’s Disease Dataset**
- Features: Voice Measurements (Jitter, Shimmer, Frequency).

### **5. Lung Cancer Dataset**
- Features: Smoking History, Age, Chronic Disease Indicators.

---

## **Project Structure**
```
|-- dataset/
|   |-- diabetes_data.csv
|   |-- heart_disease_data.csv
|   |-- thyroid_data.csv
|   |-- parkinson_data.csv
|   |-- lung_cancer_data.csv
|
|-- models/
|   |-- diabetes_model.sav
|   |-- heart_disease_model.sav
|   |-- lungs_disease_model.sav
|   |-- parkinsons_model.sav
|   |-- thyroid_model.sav
|
|-- notebooks/
|   |-- diabetes_detection.ipynb
|   |-- heart_disease_detection.ipynb
|   |-- lung_cancer.ipynb
|   |-- parkinson_disease.ipynb
|   |-- thyroid_detection.ipynb
|
|-- app.py  # Main Streamlit Web Application
|-- requirements.txt  # Dependencies
|-- README.md  # Documentation
```

---

## **Usage**
1. **Enter Input Values**: Provide **medical parameters** like glucose level, blood pressure, etc.
2. **Click Predict**: Get instant diagnostic results.
3. **View Results**: The system displays whether the user is at risk of a particular disease.

---

## **Contributor**
**Mahendra Singh Gurjar**  
Email: *mhndrmahendragurjar@gmail.com*  
Guide: *Saomya Chaudhury*

---
