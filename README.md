# Weather-Forecasting-
 **machine learning-based approach to weather forecasting**, focusing on using decision tree algorithms to predict rainfall and other meteorological events over short time frames based on historical weather data.[1]

## Project Overview

The project proposes using hourly weather data from 2009 to 2020, sourced via worldweatheronline.com API, to train machine learning models—specifically decision trees—for weather prediction tasks (rainfall, thunderstorm). Only a subset of the 24 available weather features is selected for modeling: **Temperature**, **Wind**, **Humidity**, **Cloud Cover**, **Pressure**, **Heat Index**, and **Sun Hour**.[1]

## Methodology

- **Data Preparation**: Datasets are checked for null values. If found, nulls are filled with mean/median values. Feature selection involves taking temperature as the dependent variable and others as independent features using `iloc` indexing.[1]
- **Model Building**: Decision tree classifiers are chosen for their interpretability and effectiveness. The process involves plotting histograms for training, feature extraction, and parameter tuning to optimize accuracy.[1]
- **Experimentation**: The process includes splitting data into training and testing sets, extracting features, and comparing predicted outputs to actual labels, with accuracy as a key metric.[1]
- **Results & Conclusion**: Decision trees are highlighted for their high accuracy and ease of use in weather prediction. The results indicate they can reliably predict short-term weather events and are heavily dependent on past data patterns.[1]

## Key Points

- **Traditional vs. Machine Learning**: The presentation distinguishes between conventional forecasting (synoptic, statistical, numerical methods) and data-driven machine learning techniques.[1]
- **Feature Importance**: Physical weather parameters (temperature, humidity, cloud cover, etc.) are used for prediction, representing typical inputs for meteorological modeling.[1]
- **Decision Tree Advantages**: Decision trees are praised for being simple, quantifiable, and interpretable, making them suitable for weather applications.[1]


trees.[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/100760542/123d1024-e3ad-48f2-aeae-9569e3336e88/Financial-design.pptx)
