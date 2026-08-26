# ZUDIO STORE EXPANSION AND MARKET PREDICTOR

An end-to-end Machine Learning project that predicts the performance and viability score of untapped markets for retail expansion using Python, Scikit-Learn, and Streamlit.

# What is this?

Ever wondered how retail brands decide where to open their next store?
This project uses real-time data analysis and machine learning to evaluate untapped cities and determine whether they make high-potential locations for a new Zudio store rollout.

By analyzing local market features—such as population estimates, per-capita income, existing mall density, and customer counts—a trained Random Forest Regressor model calculates a performance and priority score for each city. Coupled with an interactive Streamlit web application, users can dynamically select states and cities to instantly review projected metrics and expansion recommendations.

# Key Features

Machine Learning Pipeline: Built with a Random Forest Regressor model to predict continuous store performance metrics based on regional demographics.

Interactive Web App: A clean, user-friendly interface built with Streamlit for seamless exploration of untapped markets.

Dynamic Decision Support: Automatically classifies target markets into high or low-potential categories to assist retail strategy teams.

Zero-Editing Software: Powered purely by Python, Pandas, Scikit-Learn, Joblib, and Streamlit.

# How It Works

The project follows a streamlined data-to-deployment pipeline:

Raw Training Data (new zudio1.csv)
Train Random Forest Regressor
Export Model via Joblib (zudio_rf_model.pkl)
Load Untapped Cities Data (no zudio store.csv)
User Selects State and City in Streamlit App
Extract Market Features (Population, Income, Malls, etc.)
Model Predicts Performance Score
Display Interactive Business Recommendations

# Tech Stack

Language: Python

Data Manipulation: Pandas, NumPy

Machine Learning: Scikit-Learn (Random Forest Regressor)

Model Serialization: Joblib

Web App Framework: Streamlit

Getting Started Locally

Follow these steps to run the web application on your local machine:

# Clone the repository:
git clone https://github.com/darlingloya13-cmd/Zudio-prediction-ML-model-.git
cd Zudio-prediction-ML-model-

Install the required dependencies:
pip install streamlit pandas scikit-learn joblib

Run the Streamlit app:
streamlit run app.py

# Project Structure

app.py - Main Streamlit web application
zudio_rf_model.pkl - Trained Random Forest Regressor model
no zudio store.csv - Test dataset containing untapped cities
README.md - Project documentation
