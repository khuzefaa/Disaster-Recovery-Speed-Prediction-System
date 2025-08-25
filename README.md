# Disaster-Recovery-Speed-Prediction-System
A comprehensive machine learning system that predicts recovery speeds for communities affected by natural disasters (floods and earthquakes). This project supports SDG 11 - Sustainable Cities and Communities by helping identify which areas will recover fastest or slowest after disasters, enabling better resource allocation and preparedness planning

Natural disasters affect millions of people annually, with recovery times varying dramatically between communities. This system uses advanced analytics to predict recovery patterns, helping governments, NGOs, and disaster response organizations make data-driven decisions about resource allocation and preparedness investments.
The system combines survival analysis techniques with machine learning to analyze multiple factors including infrastructure quality, population density, economic conditions, and disaster preparedness levels to predict community recovery times.
Key Features
🔍 Comprehensive Analysis Methods

Survival Analysis: Kaplan-Meier estimators and Cox Proportional Hazards modeling
Machine Learning: Random Forest regression for recovery time prediction
Trend Modeling: Time-series analysis of recovery patterns
Scenario Planning: Predictions for different community types

📊 Data Sources Simulated

Historical disaster recovery data
Satellite imagery time series (infrastructure damage assessment)
Infrastructure quality maps
Socioeconomic indicators
Emergency response capabilities
Population demographics

🎯 Prediction Capabilities

Recovery time estimation (days to full recovery)
Risk factor identification
Community resilience scoring
Resource allocation recommendations



Model Architecture

Data Generation: Synthetic disaster scenarios with realistic parameters
Feature Engineering: Log transformations, interaction terms, categorical encoding
Survival Analysis: Handles censored recovery data
ML Pipeline: Random Forest with hyperparameter optimization
Scenario Modeling: Predictions for different community types


