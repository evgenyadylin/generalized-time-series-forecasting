# Data

This folder is intended for datasets used with the forecasting notebook.

The dataset used in the article is only an experimental example. It is included to demonstrate the full pipeline and to make the notebook easier to understand. The method is not limited to this specific dataset.

You can try the code with any univariate time series dataset that has:

* one date or time column
* one numerical value column

For example, you can use data such as electricity prices, stock prices, temperature, sales, demand, traffic, or sensor measurements.

A simple CSV file should look like this:

```csv
date,value
2020-01-01,10.5
2020-01-02,11.2
2020-01-03,10.9
```

If you use your own dataset, update the notebook so that it reads your file name and column names correctly.

Example:

```python
df = pd.read_csv("data/your_dataset.csv")
date_col = "date"
target_col = "value"
```

The goal of the provided dataset is only to show how the event-stream forecasting pipeline works.
