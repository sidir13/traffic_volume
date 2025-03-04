
Traffic Data Prediction with Deep Learning

Traffic data fluctuates constantly or is affected by time. Predicting it can be challenging, but this task will help sharpen your time-series skills. With deep learning, you can use abstract patterns in data that can help boost predictability.

Your task is to build a system that can be applied to help you predict traffic volume or the number of vehicles passing at a specific point and time. Determining this can help reduce road congestion, support new designs for roads or intersections, improve safety, and more! Or, you can use it to help plan your commute to avoid traffic!

### The Data:

The dataset is collected and maintained by the UCI Machine Learning Repository. The target variable is traffic_volume. The dataset contains the following and has already been normalized and saved into training and test sets:

- train_scaled.csv
- test_scaled.csv

| Column                 | Type        | Description                                         |
|------------------------|-------------|-----------------------------------------------------|
| temp                   | Numeric     | Average temp in kelvin                             |
| rain_1h                | Numeric     | Amount in mm of rain that occurred in the hour     |
| snow_1h                | Numeric     | Amount in mm of snow that occurred in the hour     |
| clouds_all             | Numeric     | Percentage of cloud cover                         |
| date_time              | DateTime    | Hour of the data collected in local CST time       |
| holiday_ (11 columns)  | Categorical | US National holidays plus regional holiday, Minnesota State Fair |
| weather_main_ (11 columns) | Categorical | Short textual description of the current weather  |
| weather_description_ (35 columns) | Categorical | Longer textual description of the current weather|
| traffic_volume         | Numeric     | Hourly I-94 ATR 301 reported westbound traffic volume |
| hour_of_day            | Numeric     | The hour of the day                                |
| day_of_week            | Numeric     | The day of the week (0=Monday, Sunday=6)           |
| day_of_month           | Numeric     | The day of the month                               |
| month                  | Numeric     | The number of the month                            |
| traffic_volume         | Numeric     | Hourly I-94 ATR 301 reported westbound traffic volume|

### Model Comparison:

For this task, I utilized PyTorch to build deep learning models for traffic volume prediction. However, to evaluate the performance and accuracy of the models, I compared them to other machine learning models, such as:

- Random Forest (RF)
- Support Vector Regression (SVR)

This comparison provides a comprehensive understanding of the strengths and weaknesses of various models and their effectiveness for traffic volume prediction.

By combining the power of deep learning and traditional machine learning models, we can make more accurate predictions to help with traffic management, planning, and optimization.

