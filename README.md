# Stock Market Prediction Notebook

This project provides a Jupyter Notebook for analyzing and predicting stock prices, with a focus on American Airlines (AAL). It demonstrates data collection, preprocessing, visualization, and basic prediction techniques using Python and popular data science libraries.

## Project Structure

- `notebooks/stock_predictions.ipynb`: Main notebook for data loading, analysis, and prediction.
- `data/stock_market_data-AAL.csv`: Historical stock data for American Airlines.
- `results/`: Intended for saving model outputs and results (currently empty).
- `src/`: Placeholder for additional source code (currently empty).
- `requirements.txt`: List of required Python packages.

## Features

- Fetches stock data from Alpha Vantage and Kaggle.
- Preprocesses and visualizes stock price data.
- Implements data normalization and smoothing.
- Demonstrates a simple moving average prediction.
- Uses libraries such as Pandas, NumPy, Matplotlib, Scikit-learn, and TensorFlow.

## Getting Started

1. **Install dependencies**  
   Create a conda environment and install dependencies:
   ```sh
   conda create --name stock-prediction --file requirements.txt
   conda activate stock-prediction
   ```

2. **Set up API keys**  
   - For Alpha Vantage, set your API key in a `.env` file:
     ```
     API_KEY=your_alpha_vantage_api_key
     ```

3. **Run the notebook**  
   Open `notebooks/stock_predictions.ipynb` in JupyterLab or VS Code and run the cells.

## Data Sources

- [Alpha Vantage](https://www.alphavantage.co/)
- [Kaggle: Price Volume Data for All US Stocks & ETFs](https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)

## License

This project is for educational and research purposes.
