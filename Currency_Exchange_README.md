# USD-INR Exchange Rate Prediction with Google Colab

This project leverages the power of Google Colab to analyze the historical USD-INR exchange rate and build a time series model for predicting future exchange rates using the SARIMA model.

## Project Overview

This project aims to:

1. Perform exploratory data analysis on historical USD-INR exchange rate data within the Google Colab environment.
2. Identify trends, patterns, seasonality, and growth trends in the exchange rate data.
3. Develop a robust time series model, specifically SARIMA, for predicting future exchange rates.
4. Evaluate the performance of the model using appropriate metrics and visualize the results.

## Data

The project utilizes a CSV file named "INR-USD.csv," containing daily USD-INR exchange rate data from 2000 to 2023. This data is readily loaded and processed using Pandas within Google Colab.

## Methodology

The project follows these key steps:

1. **Data Loading and Preprocessing:** Load the exchange rate data from the CSV file within Google Colab. Utilize Pandas to handle missing or erroneous data, ensuring data integrity.
2. **Exploratory Data Analysis (EDA):** Employ visualization libraries like Plotly and Matplotlib to conduct EDA within Google Colab. This involves identifying trends, patterns, seasonality, and growth trends in the exchange rate data.
3. **Time Series Modeling with SARIMA:** Leverage the `statsmodels` library within Google Colab to implement the SARIMA model. This involves determining optimal model parameters and training the model using historical data.
4. **Model Evaluation and Prediction:** Evaluate the SARIMA model's performance using metrics like Mean Squared Error (MSE) or Root Mean Squared Error (RMSE). Visualize predictions alongside historical data for insightful analysis.

## Google Colab Integration

This project is designed to be executed seamlessly within Google Colab. The provided Jupyter notebook leverages Colab's features, including:

- **Pre-installed Libraries:** Colab provides pre-installed libraries like Pandas, NumPy, Matplotlib, and Seaborn, simplifying the setup process.
- **GPU Acceleration:** Leverage Colab's GPU acceleration for faster model training and computation.
- **Interactive Environment:** Utilize Colab's interactive environment for data exploration, visualization, and model development.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Statsmodels
- pmdarima

## Getting Started with Google Colab

1. Open the Jupyter notebook (`usd-inr-prediction.ipynb`) in Google Colab.
2. Execute the code cells sequentially to load the data, perform EDA, build the SARIMA model, and generate predictions.
3. Explore the interactive visualizations and analyze the model's performance.

## Results

The project demonstrates the successful implementation of a SARIMA model for USD-INR exchange rate prediction using Google Colab. The accuracy of the predictions is influenced by factors such as the historical data's length and the model's parameters.

## Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests with enhancements or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgments

We acknowledge the developers and maintainers of the open-source libraries used in this project. We also express gratitude to Google Colab for providing a powerful platform for data science and machine learning.