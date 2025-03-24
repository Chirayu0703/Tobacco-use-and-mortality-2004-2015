# Tobacco Use and Mortality (2004-2015) - Machine Learning Project

## Project Overview
This project explores the relationship between tobacco use and mortality rates using machine learning techniques. The dataset consists of health-related data from 2004 to 2015, analyzing smoking habits, mortality statistics, and other influencing factors.

## 🔬 Learning Method  
This project follows a **Supervised Learning** approach, where labeled data (mortality outcomes) is used to train various classification models. The key steps in the learning process include:  
1. **Feature Selection & Engineering** – Extracting relevant features from the dataset.  
2. **Data Preprocessing** – Handling missing values, scaling, and encoding categorical variables.  
3. **Model Training** – Training multiple classifiers (Logistic Regression, Random Forest, XGBoost).  
4. **Hyperparameter Tuning** – Optimizing model performance using Grid Search/Random Search.  
5. **Model Evaluation** – Comparing different models using accuracy, precision, recall, F1-score, and ROC-AUC.  
6. **Model Explainability** – Using **SHAP and LIME** to interpret predictions.  

## 🔧 Technologies Used  
- **Programming Language:** Python  
- **Machine Learning Frameworks:** Scikit-learn, XGBoost, TensorFlow/Keras  
- **Data Processing & Visualization:** Pandas, NumPy, Seaborn, Matplotlib  
- **Model Explainability:** SHAP, LIME  
- **Deployment:** Flask, FastAPI  

## Project Workflow
### 1. Data Collection
- Health surveys (NHANES, BRFSS)
- Mortality data (WHO, CDC)
- Tobacco use data

### 2. Data Preprocessing
- Handling missing values
- Feature engineering (e.g., duration of tobacco use, demographics)

### 3. Exploratory Data Analysis (EDA)
- Data visualization using heatmaps, histograms, correlation matrices

### 4. Model Selection & Training
- **Algorithms**: Logistic Regression, Random Forest, Gradient Boosting
- **Evaluation metrics**: Accuracy, Precision, Recall, ROC-AUC

### 5. Model Deployment
- **Flask API** for predictions
- **Web dashboard** using Streamlit

## 🏆 Challenges and Considerations  
- **Data Quality:** Cleaning and handling missing data properly.  
- **Bias in Data:** Addressing potential biases in demographic representation.  
- **Model Explainability:** Ensuring interpretability using SHAP/LIME.  
- **Privacy & Ethics:** Ensuring compliance with health data protection standards.  

---

## 📌 Future Improvements  
- Improve accuracy using deep learning models like CNNs/LSTMs.  
- Implement a real-time data pipeline for live predictions.  
- Deploy the model on cloud services (AWS, Google Cloud).


