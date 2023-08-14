# Ride-Hailing Supply-Demand Forecasting Project 🚗📊

## Background and Problem Statement 🌆📋

In the ride-hailing industry, companies like Uber deal with the challenge of matching passenger demand with driver availability. This project aims to predict the supply-demand gap for ride-hailing services, helping optimize driver allocation and provide a smooth experience for passengers.

## Problem Definition and Evaluation Criteria 📝🔍

The objective is to forecast the supply-demand gap in specific regions and time slots. This gap represents the difference between passenger requests and driver responses. The Mean Absolute Error (MAE) is used as the evaluation metric to measure the accuracy of predictions.

## Data and Fields 📊🗃️

Three main data tables are used:

1. **Order Information Table**: Contains order details such as IDs, regions, price, and time.

2. **Region Information Table**: Provides region information and mapping.

3. **POI Information Table**: Includes points of interest and facilities data.

4. **Weather Information Table**: Presents weather conditions every 10 minutes.

## Predictive Modeling 📈🤖

Two machine learning techniques are employed for predictive modeling:

1. **Linear Regression**: Predicts the gap using region IDs and time slots. Data preprocessing includes one-hot encoding and standard scaling.

2. **Decision Trees**: Used for classifying the supply-demand gap. Accuracy and MAE are evaluation metrics.

## Running the Code ▶️🛠️

1. Ensure Python 3.x and required libraries are installed.
2. Modify file paths in the code to match your data locations.
3. Run the code within a Python environment.

## Results and Impact 🎉📈

Project success is determined by predictive model accuracy. Lower MAE values indicate better performance. Accurate supply-demand forecasts help optimize driver allocation and enhance user experience.

## Contact Information 📬

For questions or suggestions, please contact Areeba Sattar at areebasattar23@gmail.com.

🚀 Happy coding and exploring ride-hailing supply-demand dynamics!
