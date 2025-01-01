# Power Sage - Solar Data Forecasting

**Power Sage** is an advanced forecasting tool designed to predict solar radiation values using NASA's POWER (Prediction Of Worldwide Energy Resources) dataset. This project utilizes time series forecasting models like **ARIMA** and **SARIMA** to predict solar radiation data from 2019 to 2025 for any given location on the globe. The results are presented with metrics such as **RMSE (Root Mean Square Error)** to evaluate the accuracy of the predictions.

The project is built using Python and deployed with an interactive interface built using **Gradio**. It can be accessed and used to predict solar energy values for any latitude and longitude based on NASA's public dataset.

## Features

- **Dynamic Region Selection**: The user can input latitude and longitude to select a region and get solar data predictions for that region.
- **Time Series Forecasting**: Uses ARIMA and SARIMA models for solar radiation prediction.
- **Metrics Display**: Outputs key performance metrics like RMSE to evaluate forecast accuracy.
- **Interactive Interface**: A Gradio interface is provided for easy user interaction.

## Installation

### Clone the Repository

To get started, clone this repository:

```bash
git clone https://github.com/yashwantpatilyup/power-sage.git
cd power-sage
