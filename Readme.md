# AutoAI Model Building in IBM Watson Studio

This project demonstrates how to build a machine learning model using IBM Watson Studio's AutoAI tool. The goal of the model is to **predict PM2.5 levels** (a key air pollution indicator) based on various environmental features such as PM10, NO2, SO2, CO, O3, temperature, humidity, and wind speed.

## 🚀 Project Objective

To predict PM2.5 (fine particulate matter) levels in air using machine learning with AutoAI in Watsonx.ai.

## 📁 Dataset Features

- city  
- country  
- date  
- pm10  
- no2  
- so2  
- co  
- o3  
- temperature  
- humidity  
- wind speed  

> `pm2.5` is the **target column** used for prediction.

## 🛠️ Implementation Steps

1. Uploaded and cleaned air quality dataset.
2. Used IBM Watsonx's **AutoAI** to automatically build machine learning pipelines.
3. Selected the best performing model pipeline.
4. Deployed the model as an API endpoint.
5. Used a test dataset to validate the deployed model via a REST API call.

## 🧪 Tools & Technologies

- IBM Watson Studio (AutoAI)
- Python
- REST API
- pandas
- requests

## 📊 Sample Prediction Output

The model takes inputs like:
```json
{
  "pm10": 80,
  "no2": 30,
  "so2": 10,
  "co": 0.5,
  "o3": 25,
  "temperature": 32,
  "humidity": 45,
  "wind speed": 3
}
