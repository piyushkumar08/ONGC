# ONGC
Stock Price Prediction using LSTM
<img width="599" alt="image" src="https://user-images.githubusercontent.com/70332585/174426168-b367ef39-374f-42a2-a239-dce5fb936a95.png">

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

The objective of this project is to somewhat predict the stock prices based on the opening prices for the last 60 days or so. 

## 2. Installation <a name="installation"></a>

- Python - [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - numpy
  - matplotlib
  - Scikit-learn
     - preprocessing (for MinMaxScaler) 
     - model_selection (for train_test_split)
  - keras
     - models (for Sequential)
     - layers (for Dense, LSTM, Dropout and Bidirectional)

  
## 3. Data<a name="data"></a> 

The dataset is collected from the website [investing.com](https://www.investing.com/equities/oil---natural-gas-corporation) for the last year.
Also uploaded above by the name : ["ONGC Historical Data.csv"](https://github.com/piyushkumar08/ONGC/blob/main/ONGC%20Historical%20Data.csv)


## 4. Implementation <a name="model"></a> 
  - EDA
  - Data scaling using MinMaxScaler
  - Train-test division of the dataset
  - Fitting the data and checking the accuracy
  - Plotting the Final Prediction Curve along with actual values for Comparison.

## 5. Result<a name="results"></a>

The details of the results are shown in the jupyter notebook itself along the source code. Click here to see the result -> [Result](https://github.com/piyushkumar08/NIDDK/blob/main/NIDDK.ipynb](https://github.com/piyushkumar08/ONGC/blob/main/ONGC.ipynb) 

