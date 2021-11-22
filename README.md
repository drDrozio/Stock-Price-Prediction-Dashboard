# Stock-Prices-Prediction-ML-Flask-Dashboard

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Zeeshanahmad4/BOT--Hydrafacial">
    <img src="https://github.com/Zeeshanahmad4/ML--RMSE-with-graphs/blob/master/digital-brain-ai-machine-learning-artificial-intelligence-512.png" alt="Logo" width="110" height="130">
  </a>
  <h3 align="center">Stock Prices Prediction Dashboard</h3>
</p>


<!-- ABOUT THE PROJECT -->
## About The Project
### Interactive Dashboard to display stock price prediction over time.
Input parameters : -
1. Stock Name (Choose from Drop Down)
2. Model for Prediction (Choose from Drop Down)

Data was collected fro stocks individually for a window of 5 years and kept in the storage. Logic was developed to chose from the stock data.

User can select a particular stock for anlysis. The evaluation can be made for multiple machine learning models at the same time using the results obtained on the dashboard. With refernces to actual data points, user can choose the most optimal model for prediction.

Moreover evaluation metrics are also provided for all the models alongside.

## Deploy ![Link](https://stock-price-predictordashboard.herokuapp.com/)

## Methodology 
The following models were used to train on the dataset

```
├── Support Vector Regressor (Linear & RBF Kernel)
├── Linear Regression
├── Random Forests
├── K-Nearest Neighbors
├── Decision Trees

```
### Flowchart
![plot](./flowchart.PNG)

## Screenshots
### Demo Screenshot
![Demo](https://github.com/drDrozio/Stock-Price-Prediction-Dashboard/blob/master/pics/ezgif.com-video-to-gif.gif)

### Dashboard
![Output-Data](https://github.com/drDrozio/Stock-Price-Prediction-Dashboard/blob/master/pics/Capture3.PNG)

### Prediction result
![predic](https://github.com/drDrozio/Stock-Price-Prediction-Dashboard/blob/master/pics/Capture1.PNG)

### Models evaluation
![evaluation](https://github.com/drDrozio/Stock-Price-Prediction-Dashboard/blob/master/pics/Capture2.PNG)
![evaluation](https://github.com/drDrozio/Stock-Price-Prediction-Dashboard/blob/master/pics/Plot.png)



## Installation
1. Clone the repo
```sh
git clone https://github.com/drDrozio/Stock-Price-Prediction-Dashboard.git
```

2. Install python packages
```sh
pip install -r requirements.txt
```
