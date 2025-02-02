# Beijing PM2.5 Forecasting Challenge  
**Predicting hourly PM2.5 concentrations using LSTM networks**  

[![Python 3.8](https://img.shields.io/badge/Python-3.8-blue.svg)](https://www.python.org/)
[![TensorFlow 2.12](https://img.shields.io/badge/TensorFlow-2.12-orange.svg)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Project Overview  
This repository contains code for forecasting PM2.5 levels in Beijing using meteorological and air quality data. The model employs LSTM networks to capture temporal dependencies in hourly measurements.  

## Repository Structure  
├── data/ # train and test datasets
├── submissionf/ # Saved models
├── notebooks/ # Jupyter notebooks for EDA, preprocessing, and training


## Reproducing Results  
### Installation  
1. Download both train and test datasets into your local machine
2. Open the notebook {Final_Kaggle_subm.ipynb} either on your colab or Jupyter notebook
3. Configure the dataset locations according to where you stored you datasets.
4. Run each cell to build and train model
