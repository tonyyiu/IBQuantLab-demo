> **Note:** *This is a demo-only README of a private repository. Full source code or live demo available privately upon request.*

# Backtesting Framework with Streamlit

This repository contains a Streamlit-based application for backtesting trading strategies. The app provides an interactive interface for loading data, selecting strategies, configuring parameters, running backtests, tuning hyperparameters, validating strategies using walk-forward validation, and visualizing results.

## 🎥 Demo Video

[![Watch the demo](https://img.youtube.com/vi/kkF99YnDuYM/0.jpg)](https://www.youtube.com/watch?v=kkF99YnDuYM&t=3s)

## Features

- **Data Loading**: Upload CSV files or fetch historical data from Interactive Brokers (IBKR).
- **Strategy Selection**: Choose from pre-implemented strategies such as SMA Crossover, RSI, Momentum, Mean Reversion, Bollinger Bands, MACD, Buy and Hold, and a Machine Learning-based Random Forest strategy.
- **Parameter Configuration**: Customize strategy parameters directly in the app.
- **Backtesting**: Run backtests with detailed performance metrics and visualizations.
- **Hyperparameter Tuning**: Optimize strategy parameters using grid search.
- **Walk-Forward Validation**: Validate strategies over multiple time windows.
- **Interactive Visualizations**: View price charts, portfolio performance, and strategy-specific overlays.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd backtestingFramework
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Launch the app and upload your data or fetch data from IBKR.
2. Select a strategy and configure its parameters.
3. Run the backtest and view the results.
4. Optionally, tune hyperparameters or perform walk-forward validation.

## Strategies

The following strategies are implemented:

- **SMA Crossover**: Uses short and long simple moving averages to generate buy/sell signals.
- **RSI**: Generates signals based on the Relative Strength Index.
- **Momentum**: Trades based on price momentum.
- **Mean Reversion**: Buys when prices are below a threshold and sells when above.
- **Bollinger Bands**: Uses Bollinger Bands to identify overbought/oversold conditions.
- **MACD**: Trades based on MACD and signal line crossovers.
- **Buy and Hold**: A benchmark strategy that buys and holds the asset.
- **Random Forest Regression**: A machine learning-based strategy using technical indicators as features.

## Walk-Forward Validation

The app supports walk-forward validation to evaluate strategy performance over multiple time windows. This helps ensure robustness and avoids overfitting.

## Deployment

The app can be deployed to Streamlit Cloud for easy sharing and accessibility. Follow these steps:

1. Push the code to GitHub.
2. Link the repository to Streamlit Cloud.
3. Configure the app settings and deploy.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the app.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Streamlit](https://streamlit.io/) for the interactive app framework.
- [Interactive Brokers](https://www.interactivebrokers.com/) for historical data.
- [Matplotlib](https://matplotlib.org/) for visualizations.
- [Scikit-learn](https://scikit-learn.org/) for machine learning components.
