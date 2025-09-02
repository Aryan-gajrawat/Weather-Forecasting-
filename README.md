# Weather-Forecasting-
This PowerPoint presents a **project for weather forecasting using machine learning**, focusing on decision tree algorithms to predict rainfall and other weather conditions. Here’s a clear and structured explanation for documentation or a GitHub repository.[1]

## Project Overview

The project uses **hourly weather data (2009–2020)** gathered via the worldweatheronline.com API to build models that forecast rain and thunderstorms based on several weather features. The goal is to improve prediction accuracy by using decision tree classifiers trained on historical data.[1]

## Methodology

- **Data Collection**: Weather data was sourced using APIs and packaged tools, resulting in a rich dataset with 24 features (such as temperature, humidity, wind speed, etc.).[1]
- **Feature Selection**: For prediction, only selected features are used: **Temperature**, **Wind Speed**, **Humidity**, **Cloud Cover**, **Pressure**, **Heat Index**, and **Sun Hour**. These are believed to be most influential for rainfall prediction.[1]
- **Data Quality**: The dataset is checked for null/missing values; if any are found, they are replaced with averages (mean/median).[1]
- **Model Training**: A **decision tree classifier** is chosen for its interpretability and suitability for both regression and classification tasks. Histograms and plots are used for initial data visualization and to tune model parameters for best accuracy.[1]
- **Prediction & Evaluation**: The model predicts weather outcomes (rain, thunderstorm) for test data, and accuracy is assessed by comparing predictions to true labels.[1]

## Why Decision Trees?

- Decision trees provide a **visual, easy-to-understand method** for making predictions.[1]
- They help categorize different meteorological parameters and predict precipitation, which is highly reliant on historical data patterns.[1]
- The structure (branches and nodes) makes them transparent and quantifiable, suitable for practical weather forecasting tasks.[1]

## Results & Conclusion

The approach demonstrates that decision trees can predict weather events (up to a week or 10 days ahead) with high accuracy using past data. Their rule-based structure is effective for modeling relationships among features like temperature, humidity, and wind speed—making them valuable for short-term weather forecast models.[1]

