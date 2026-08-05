# Flight-Delay-Intelligence-system
Flight Delay Prediction System is a machine learning project that predicts whether a flight will be delayed or on time using flight schedule and operational data. Built with Python, Scikit-learn, Pipelines, One-Hot Encoding, StandardScaler, Decision Tree, Random Forest, Joblib, and Streamlit for deployment.
# ✈ Flight Delay Prediction System

A Machine Learning project that predicts whether a scheduled flight is likely to be **Delayed** or **On Time** based on flight schedule and operational information. The project demonstrates a complete end-to-end machine learning workflow, from data preprocessing to model deployment using Streamlit.

---

## 📌 Project Overview

Flight delays can impact passengers, airlines, and airport operations. This project uses machine learning algorithms to analyze flight-related information and predict flight delays before departure.

The project covers the complete ML pipeline including:

- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Pipeline Creation
- Model Training
- Model Evaluation
- Model Deployment

---

## 🚀 Features

- Predicts flight delay status.
- End-to-end Machine Learning Pipeline.
- Automatic preprocessing using Scikit-learn Pipeline.
- One-Hot Encoding for categorical features.
- Standard Scaling for numerical features.
- Decision Tree Classifier.
- Random Forest Classifier.
- Model evaluation using multiple metrics.
- Streamlit web interface for predictions.
- Model saved using Joblib.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit
- Jupyter Notebook

---

## 📂 Dataset Features

The model uses the following input features:

- Year
- Month
- Day of Month
- Day of Week
- Airline
- Flight Number
- Origin Airport
- Origin City
- Origin State
- Destination Airport
- Destination City
- Destination State
- Scheduled Departure Time
- Scheduled Arrival Time
- Scheduled Flight Duration
- Flight Distance

---

## ⚙ Machine Learning Workflow

### 1. Data Collection

Load the flight dataset.

### 2. Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Selected useful features

### 3. Data Preprocessing

- One-Hot Encoding
- Standard Scaling

### 4. Train-Test Split

Split the dataset into training and testing sets.

### 5. Pipeline

Created a Scikit-learn Pipeline combining:

- ColumnTransformer
- OneHotEncoder
- StandardScaler
- Machine Learning Model

### 6. Model Training

Models used:

- Decision Tree Classifier
- Random Forest Classifier

### 7. Model Evaluation

Evaluation metrics:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

### 8. Save Model

Saved the trained model using Joblib.

### 9. Deployment

Created a Streamlit application that allows users to enter flight information and receive delay predictions.

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Decision Tree | 78% |
| Random Forest | 79% |

> **Note:** Although Random Forest achieved slightly higher overall accuracy, the dataset is imbalanced, making delayed flights more challenging to predict. This project focuses on demonstrating a complete machine learning workflow rather than maximizing accuracy.

---

## 📁 Project Structure

```
Flight_Delay_Prediction/
│
├── app.py
├── Flight_Delay.ipynb
├── flight_delay_model.pkl
├── dataset.csv
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Flight-Delay-Prediction.git
```

Move into the project folder:

```bash
cd Flight-Delay-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📸 Application

The Streamlit application allows users to:

- Enter flight details
- Predict whether a flight will be delayed
- Display the prediction result instantly

---

## 📈 Future Improvements

- Hyperparameter tuning
- Feature importance visualization
- Weather data integration
- Airport congestion analysis
- Flight delay probability prediction
- Cloud deployment
- Interactive dashboard
- Real-time flight API integration

---

## 🎯 Learning Outcomes

This project helped demonstrate practical experience with:

- Data preprocessing
- Feature engineering
- Scikit-learn Pipelines
- One-Hot Encoding
- Standardization
- Decision Tree
- Random Forest
- Model evaluation
- Model deployment using Streamlit

---

## 👨‍💻 Author

**Khezar Hayat**

BS Artificial Intelligence Student

Passionate about Machine Learning, Artificial Intelligence, and Data Science.

---

## ⭐ If you found this project useful

Please consider giving the repository a **Star ⭐**.
