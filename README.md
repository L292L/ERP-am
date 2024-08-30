# Time Series Forecasting of Air Quality – Evaluating the Impact of Adding Relevant Pollutant Features on PM2.5 Prediction Accuracy in Urban Background

## Project Overview

Air pollution poses a significant threat to human health, with fine particulate matter (PM2.5) being one of the most harmful pollutants. PM2.5, composed of various toxic substances, has been linked to serious health issues, including cardiovascular and respiratory diseases. The accurate prediction of PM2.5 concentrations is crucial for mitigating these health risks. Futhermore, we found most of previous studies of PM2.5 prediction only utilise PM2.5 combining with meterological data. However, the composition of PM2.5 is very complex and closely related to many other pollutants.

Therefore, this project investigates the impact of incorporating additional pollutant data on the accuracy of PM2.5 predictions. The study utilises data from the UK's Automatic Urban and Rural Network (AURN), which monitors pollutants such as NO, NO2, NOX, SO2, O3, CO, PM10, and PM2.5, along with meteorological data. 

## Objectives

The primary goal of this research is to assess how including multiple pollutants, alongside PM2.5 concentrations and meteorological data, affects the accuracy of short-term and long-term PM2.5 predictions. The project is divided into two key sections:
- **Multi-Pollutant Prediction**: Predicting PM2.5 concentrations using multiple relevant pollutants (NO, NO2, NOX, SO2, O3, CO, PM10) and meteorological data.
- **Single-Pollutant Prediction**: Predicting PM2.5 concentrations using only PM2.5 data and meteorological data.

The study leverages Long Short-Term Memory (LSTM) networks to model time series data, a method chosen for its effectiveness in capturing long-term dependencies and mitigating issues like gradient vanishing or exploding.

## Methodology

The research follows a structured approach:
1. **Data Preparation**: Utilising data from the AURN network, focusing on pollutants and meteorological factors relevant to PM2.5 formation. Preprocessing the data, such as missing values imputation.
2. **Exploratory Data Analysis**: Analysing the relationships between pollutants, meteorological factors, and PM2.5 concentrations.
3. **Model Development**: Implementing LSTM networks to predict PM2.5 concentrations over short-term and long-term periods.
4. **Comparative Analysis**: Evaluating the impact of including multiple pollutants on prediction accuracy compared to using only PM2.5 data.

## Conclusion

This study provides valuable insights into the factors influencing PM2.5 prediction accuracy and offers a robust methodology for enhancing environmental policy-making and public health initiatives.

## Repository Contents

- **Data Files**: Contains R code for extracting data, and the CSV files (extracted monitoring data and monitoring station metadata).
- **Code Files**: Includes Jupyter notebooks for data processing, model development, and prediction.
- **Results Comparison**: Documentation comparing the performance of two experiments.
- **Requirements**: A 'requirements.txt' file listing all necessary Python packages.

