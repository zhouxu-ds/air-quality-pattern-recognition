# Time Series Pattern Recognition with Air Quality Sensor Data

This is a real-world client-facing project that consists of data analysis, visualization, machine learning, and automated pattern recognition using time series data from measurements of air quality sensors.

## Links to Resources

- [My post on Medium and Towards Data Science](https://towardsdatascience.com/time-series-pattern-recognition-with-air-quality-sensor-data-4b94710bb290)
- [My project report](https://github.com/zhouxu-ds/ds-projects/blob/master/air_quality_pattern_recognition/report_TSPR.pdf)
- [Data used in this project](https://github.com/zhouxu-ds/ds-projects/tree/master/air_quality_pattern_recognition/data)

## Notebooks

- [EDA](https://github.com/zhouxu-ds/ds-projects/blob/master/air_quality_pattern_recognition/notebook/EDA.ipynb): This notebook consist of my EDA work, together with some data visualization. It also includes data preprocessing and saves the processed data as a `pkl` file, to be used in the later notebooks.
- [Point Anomaly Detection](https://github.com/zhouxu-ds/ds-projects/blob/master/air_quality_pattern_recognition/notebook/point_anomaly_detection.ipynb): This notebook show how to detect the point anomalies (outliers) and automatically flags them.
- [Collective Anomaly Detection](https://github.com/zhouxu-ds/ds-projects/blob/master/air_quality_pattern_recognition/notebook/collective_anomaly_detection.ipynb): This notebook shows how to detect the collective anomalies (patterns) by training Regression models using sliding window and forward chaining on the time series data.
- [Clustering](https://github.com/zhouxu-ds/ds-projects/blob/master/air_quality_pattern_recognition/notebook/clustering.ipynb): This notebook shows how to use the clustering methods (K-Means and DBSCAN) to group the data into different events. It shows strength and weakness of each method.

