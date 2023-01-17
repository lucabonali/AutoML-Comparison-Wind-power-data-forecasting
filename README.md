# AutoML-Comparison-Wind-power-data-forecasting
An automl comparison of open source software libraries on kaggle dataset https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset

This repository contains data and notebooks behind this Medium article: https://medium.com/@lucabonali12/open-source-automl-libraries-comparison-on-wind-turbine-power-generation-forecasting-task-gcp-1dddc0dfa80

## Data

In the Data folder there are 4 files:

* gcp_prediction.csv -> the prediction derived from GCP Automl model.
* scaled_wind_data.csv -> Output of the preprocessing notebook, and input of the comparison notebook.
* scaling_df.csv -> mean and standard deviation of the features and label variables (derived from standard scaling).
* wind_turbine_data.csv -> original input dataset, founded here: https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset?resource=download
