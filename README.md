# Aircraft Engine Maintenance Prediction

## Overview
The **Aircraft Engine Maintenance Prediction App** is a machine learning project designed to predict whether an aircraft engine requires maintenance based on input parameters such as temperature, pressure, rotational speed, engine health, and more. This tool helps in proactive maintenance, which can significantly improve the safety, reliability, and efficiency of aircraft operations.

The model was developed using a Random Forest algorithm and deployed using **Streamlit** for a user-friendly interface. This project simulates real-world scenarios where aircraft engines operate under varying conditions, and the app helps management make informed decisions on when to service engines.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Features](#features)
- [Usage](#usage)
- [Model](#model)
- [Deployment](#deployment)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Structure

## Features
- Predicts whether an aircraft engine needs maintenance based on user input parameters.
- Interactive web interface built with **Streamlit**.
- Sidebar input widgets for real-time predictions.
- Supports input for critical features such as temperature, pressure, rotational speed, engine health, and more.


## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/ighobaby/aircraft-engine-maintenance.git
cd aircraft-engine-maintenance
 
### 2. Set up a virtual environment:

bash

python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate

### 3. Install the dependencies:

bash

pip install -r requirements.txt

4. Run the Streamlit app:

bash

streamlit run app.py

The app should now be running locally at http://localhost:8501/.
Usage

    Input engine parameters like temperature, pressure, rotational speed, engine health, etc., into the sidebar.
    The app will predict whether the engine needs maintenance based on these inputs.
    Check the result displayed on the main screen.

Input Parameters:

    Temperature (°C): The temperature of the engine.
    Pressure (kPa): Pressure in the engine.
    Rotational Speed (RPM): Rotational speed of the engine's components.
    Engine Health: A categorical value representing engine health (0 for bad, 1 for average, 2 for good).
    Fuel Consumption (L): Fuel consumption rate.
    Vibration Level (mm/s): Vibration level of the engine.
    Oil Temperature (°C): The temperature of the engine's oil.
    Altitude (m): Aircraft altitude.
    Humidity (%): Humidity level in the air.

Model

The model used for this prediction is a Random Forest Classifier. The dataset contains various engine health and operational parameters, simulating different conditions for multiple aircraft engines.
Model Evaluation Metrics:

    Accuracy
    Precision
    Recall
    F1-Score
    ROC-AUC

The trained model is stored in the random_forrest_aircraft_model.pkl file and is loaded in the app for real-time predictions.
Deployment

The app is deployed on Streamlit

Results

The project provided accurate predictions on whether an aircraft engine needs maintenance. The Random Forest model was able to classify engines' maintenance needs with high accuracy based on the provided input parameters.

You can view the live app here:

    Streamlit Cloud: Streamlit App
    

License

This project is licensed under the MIT License - see the LICENSE file for details.
Contact

Created by Augustine Osagie

    GitHub: https://github.com/ighobaby
    LinkedIn: https://www.linkedin.com/in/augustine-osagie-
