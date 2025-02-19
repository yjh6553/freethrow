# Free Throw Success Rate Prediction

## Overview
This project analyzes and predicts the success rate of free throws using various machine learning models. Our team explored different features that impact free throw accuracy, collecting and processing data to build predictive models using statistical and deep learning approaches.  

## Features Explored
We examined multiple factors that could influence free throw success rates, including:
- **Player stance and posture**
- **Shot trajectory and release time**
- **Environmental factors (crowd noise, fatigue, game pressure)**
- **Player statistics (height, weight, past performance)**  

## Tech Stack
We used the following libraries and frameworks for data processing, analysis, and modeling:
- **Python** for data handling and model implementation
- **Pandas & NumPy** for data collection, cleaning, and transformation
- **SciPy** for statistical analysis and hypothesis testing
- **PyTorch** for deep learning models
- **Matplotlib & Seaborn** for data visualization

## Models Implemented
We experimented with multiple machine learning models to compare their effectiveness in predicting free throw success:
- **Generalized Linear Model (GLM)** – Interpretable statistical model for understanding feature impact
- **Bayesian Hierarchical Model (BHM)** – Captures uncertainty and variance across different conditions
- **Random Forest** – Handles non-linearity and interactions between multiple variables
- **Neural Networks (PyTorch)** – Deep learning model to capture complex patterns in player performance

## Results & Findings
- **Feature Importance:** Certain biomechanical and game-related factors showed a strong correlation with free throw accuracy.
- **Model Performance:** The **Neural Network** achieved the highest accuracy, but **Random Forest** provided better interpretability.
- **Statistical Insights:** Bayesian modeling helped quantify the probability of success under different conditions.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yjh6553/freethrow.git
   cd freethrow
