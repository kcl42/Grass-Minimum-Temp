# Grass-Minimum-Temp
This is a project using RNN and LSTM to forecast the grass temperature.

Trained by using data from HK Observatory dataset, which include 1980-2025 minimum grass temperature.

Reference Link :https://data.gov.hk/en-data/dataset/hk-hko-rss-daily-grass-min-temp

Model:RNN, LSTM, BiLSTM

## Result

RNN  - Test MAE:  0.977 °C, RMSE: 1.310 °C

LSTM - Test MAE:  0.926 °C, RMSE: 1.289 °C

BiLSTM - Test MAE: 0.933 °C, RMSE: 1.271 °C

![image](https://github.com/kcl42/Grass-Minimum-Temp/blob/main/img/Test.png)

## Predict Temperature

![image](https://github.com/kcl42/Grass-Minimum-Temp/blob/main/img/Temp%20pred.png)

## error rate

![image](https://github.com/kcl42/Grass-Minimum-Temp/blob/main/img/95%25%20LSTM.png)

![image](https://github.com/kcl42/Grass-Minimum-Temp/blob/main/img/95%25%20BLSTM.png)

![image](https://github.com/kcl42/Grass-Minimum-Temp/blob/main/img/distrribution.png)
