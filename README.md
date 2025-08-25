# Crop-Recommendation-System

🌱 Smart Crop Recommendation System
📖 Project Overview
Smart Crop Recommendation System is an intelligent web application that leverages machine learning to help farmers and agricultural professionals determine the optimal crop to plant based on specific environmental and soil conditions. By analyzing key parameters like nutrient levels, weather conditions, and soil properties, our system provides data-driven recommendations to maximize yield and promote sustainable farming practices.

This application combines a powerful machine learning backend with an intuitive Streamlit-based frontend, making agricultural intelligence accessible to everyone from small-scale farmers to large agricultural enterprises.

🎯 Key Features
🤖 Intelligent Prediction: Utilizes ensemble machine learning models (Random Forest and XGBoost) trained on comprehensive agricultural data

📊 Multi-Parameter Analysis: Considers 7 critical factors for accurate recommendations:

Nitrogen (N), Phosphorus (P), Potassium (K) levels

Temperature, Humidity, Rainfall measurements

Soil pH balance

🖼️ Visual Feedback: Displays images of recommended crops for easy identification

📈 Performance Metrics: Models achieve over 96% accuracy in crop recommendation

🌍 Accessibility: Web-based interface works on any device with internet access

🏗️ Technical Architecture
Backend
Machine Learning Models:

Random Forest Classifier (Primary)

XGBoost Classifier (Alternative/Ensemble)

Training Accuracy: 98.12% on validation set

Validation Accuracy: 96.56% on test data

Framework: Scikit-learn, XGBoost

Frontend
Web Framework: Streamlit

Visualization: Matplotlib, Seaborn

Data Handling: Pandas, NumPy

Data
Dataset: Crop_recommendation.csv

Features: 7 agricultural parameters

Target: 22 different crop types

📈 Model Performance
Our trained models demonstrate excellent performance:

Final Training Accuracy: 98.12%

Final Validation Accuracy: 96.56%

Low Loss Values: 0.0578 (training), 0.1210 (validation)

Consistent Improvement: Steady accuracy increase across 10 training epochs

🚀 Installation & Usage
Prerequisites
bash
pip install streamlit numpy pandas scikit-learn xgboost matplotlib seaborn pillow
Running the Application
bash
streamlit run webapp.py
How to Use
Enter soil nutrient levels (N, P, K)

Input environmental conditions (temperature, humidity, rainfall)

Specify soil pH level

Click "Predict" to get recommended crop

View crop image and cultivation information

🌟 Key Benefits
Increased Yield Potential: Data-driven recommendations optimize crop selection

Resource Efficiency: Reduces waste by matching crops to ideal conditions

User-Friendly Interface: Accessible to users with varying technical expertise

Scalable Solution: Can be adapted for different regions and crop types

📁 Project Structure

crop-recommendation-system/
│
├── webapp.py                 # Main Streamlit application
├── RF.pkl                    # Trained Random Forest model
├── XGBoost.pkl              # Trained XGBoost model
├── Crop_recommendation.csv  # Dataset for training
├── crop_images/             # Directory containing crop images
│   ├── rice.jpg
│   ├── wheat.jpg
│   └── ... (other crop images)
├── training_hist.json       # Training history and metrics
└── README.md               # Project documentation


