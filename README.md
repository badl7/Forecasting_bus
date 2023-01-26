## Bus Demand Forecasting in Banana Republic Municipalities


The central urban planning committee of Banana Republic has asked for help in forecasting bus demands of municipalities. They have provided a dataset that includes two measurements for an hour for the number of used buses in each municipality, each measurement is timestamped. The dataset is in CSV format, with the following columns:

    MUNICIPALITY_ID: An anonymized identifier for the municipality
    TIMESTAMP: The exact time of the measurement
    USAGE: The number of buses in use at the time of measurement
    TOTAL_CAPACITY: The total number of buses in the municipality

# Method

*    Simple Baseline: Linear Regression
*    Complex Method: XGBoost, LSTM, Sarimax
