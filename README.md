# Energy Consumption Predictor

A classic repository name for this project: **energy-consumption-predictor**

## Overview

This project is a web application that predicts household energy consumption using machine learning models. Users can input household and environmental parameters, select a prediction model (Random Forest or Linear Regression), and visualize the results with interactive charts.

## Features
- Predicts household energy usage (kWh) based on user inputs
- Supports two models: Random Forest and Linear Regression
- Interactive web interface built with Streamlit
- Visualizes input data with bar and pie charts (Plotly)
- Customizable background and modern UI
- Handles categorical and numerical features

## Requirements
- Python 3.7+
- Streamlit
- pandas
- joblib
- plotly

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/energy-consumption-predictor.git
   cd energy-consumption-predictor
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   If `requirements.txt` is not present, install manually:
   ```bash
   pip install streamlit pandas joblib plotly
   ```

## Usage
1. Ensure the model files (`Random_forest_model(2).pkl` and `Linear_model.pkl`) are present in the project directory.
2. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
3. Open the provided local URL in your browser.
4. Enter household and environmental data, select a model, and click **Predict** to see the estimated energy usage and visualizations.

## File Structure
- `app.py` - Main Streamlit application
- `Random_forest_model(2).pkl` - Random Forest model file
- `Linear_model.pkl` - Linear Regression model file

## License
This project is for educational and demonstration purposes.
