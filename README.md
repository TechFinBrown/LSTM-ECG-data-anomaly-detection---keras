# LSTM-ECG-data-anomaly-detection---keras
---
This repository applied the LSTM network into anomaly/failure detection in the time series. The network can become a predictor in multiple time steps by trained on the non-anomalous data of the ECG signals. The result of prediction error was modeled as a multivariate Gaussian distribution that was able to evaluate the possibility of abnormal behavior.

---
- Result Plot

![](https://github.com/TechFinBrown/LSTM-ECG-data-anomaly-detection---keras/blob/master/LSTM_ECG_Anomaly%20detection.png)

---
Required Libraries
- Keras
- tensorflow
- matplotlib 
- pandas 
- numpy 
- scikit-learn 
- scipy 

References

[1] Renom - LSTM for Anomaly Detection in Time Series Data
https://www.renom.jp/notebooks/tutorial/time_series/lstm-anomalydetection/notebook.html

[2] Malhotra, Pankaj, et al. "Long short term memory networks for anomaly detection in time series." Proceedings. Presses universitaires de Louvain, 2015.

[3] E. Keogh, J. Lin and A. Fu (2005). HOT SAX: Efficiently Finding the Most Unusual Time Series Subsequence. In The Fifth IEEE International Conference on Data Mining.

[4] 井手剛, 杉山将. 『機械学習プロフェッショナルシリーズ　異常検知と変化検知』, 講談社, 2015.
