# Multiple-Disease-Prediction-System-Using-Machine-Learning
An AI-powered healthcare application that predicts the likelihood of multiple diseases including **Diabetes, Heart Disease, and Kidney Disease** using machine learning models.
This project focuses on **early detection and preventive healthcare**, providing a user-friendly interface for real-time predictions.  

# Team Members
Shivani Deonath (SBU221482)\
Preety Sinha (SBU221981)\
Anand Kumar (SBU221584)    

<img width="1657" height="835" alt="image" src="https://github.com/user-attachments/assets/fcbd3ac3-b739-48e6-bf19-a088321261b4" />


# Project Overview
This system leverages machine learning algorithms to analyze medical parameters and predict disease risks.  

🔍 Predicts:  
  - Diabetes  
  - Heart Disease  
  - Kidney Disease  
- 🧠 Uses specialized ML models for each disease  
- 🌐 Deployed using Streamlit for interactive usage  
- ⚡ Real-time predictions with confidence scores  

# Objectives
- Build a multi-disease prediction system using ML  
- Develop high-accuracy models for critical diseases  
- Create an interactive web-based application  
- Assist doctors and patients with easy predictions  

# Disease Information
| Disease         | Dataset Size | Source |
|----------------|------------|--------|
| Diabetes       | 768        | Pima Indians Diabetes Dataset |
| Heart Disease  | 303        | Cleveland Heart Disease Dataset |
| Kidney Disease | 400        | Chronic Kidney Disease Dataset |

# Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Scikit-learn  
  - XGBoost  
  - Pandas  
  - NumPy  
- **Frontend/UI:** Streamlit  
- **Model Deployment:** Local Streamlit Server  

# Data Preprocessing
- Feature Scaling (StandardScaler, RobustScaler)  
- Missing Value Handling (KNN Imputation)  
- Outlier Detection (Isolation Forest, LOF)  
- Feature Engineering (Normalization, BMI Categorization)  

# Machine Learning Models

## Diabetes Prediction
- Random Forest + XGBoost (Voting Classifier)  

## Heart Disease Prediction
- Gradient Boosting (with early stopping)  

## Kidney Disease Prediction
- Hybrid Model (Machine Learning + Neural Network)  

# Model Performance

| Disease         | Accuracy |
|----------------|---------|
| Diabetes       | 91.2%   |
| Heart Disease  | 92.1%   |
| Kidney Disease | 88.5%   |\
- High cross-validation consistency  
- Balanced precision and recall  
- Reduced overfitting using regularization  

# System Architecture

```
User Input → Data Preprocessing → Model Prediction → Output (Prediction + Confidence Score)
```

- **Frontend:** Streamlit UI  
- **Backend:** ML Models (Python)  
- **Pipeline:** Preprocessing + Feature Engineering

# How to Run the Project

1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/disease-prediction-streamlit-app.git  
   ```  

2. Navigate to the project folder:  
   ```bash  
   cd disease-prediction-streamlit-app  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  

# 📌Features

- User-friendly web interface  
- Real-time prediction  
- Multiple disease detection  
- Confidence score output  
- Scalable architecture for future diseases  

# Sample Output

- Diabetes Prediction with confidence score  
- Heart Disease risk classification  
- Kidney Disease detection results  

# Future Scope

- Add more diseases (e.g., cancer, liver disease)  
- Integrate with hospital databases  
- Deploy on cloud platforms (AWS, Azure)  
- Mobile app integration

# Acknowledgements

- Pima Indians Diabetes Dataset  
- Cleveland Heart Disease Dataset    
- Chronic Kidney Disease Dataset  

# License

This project is for educational and research purposes.



