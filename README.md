# AI-Driven Capital Market Analysis

## Project Overview
This project applies advanced stochastic models and machine learning techniques to analyze and predict capital market risks and returns. It demonstrates the power of combining traditional financial modeling with cutting-edge AI techniques to provide more accurate and timely insights into market dynamics.

## Key Features
- Historical stock data retrieval using yfinance
- Stochastic modeling with Geometric Brownian Motion (GBM)
- Machine learning models:
  - Random Forest for return prediction
  - LSTM neural network for price prediction
- Comprehensive visualization of actual prices, model predictions, and GBM simulations
- Model performance evaluation and comparison

## Technologies Used
- Python 3.8+
- Libraries: numpy, pandas, yfinance, matplotlib, scikit-learn, tensorflow, scipy

## Installation
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/capital-market-analysis.git
   ```
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Open `capital_market_analysis.ipynb` in Jupyter Notebook or Google Colab.
2. Run all cells to perform the analysis on Apple Inc. (AAPL) stock.
3. To analyze a different stock, modify the `analyze_stock()` function call at the end of the notebook:
   ```python
   analyze_stock('TICKER', 'START_DATE', 'END_DATE')
   ```

## Key Findings
- LSTM outperforms Random Forest in stock price prediction
- Both models show significant predictive power (R2 > 0.80)
- GBM simulation provides insights into potential price ranges and limitations of constant volatility assumptions
- Analysis challenges strong-form market efficiency, highlighting potential for algorithmic trading strategies
- Recent historical prices and short-term changes are most important for predicting returns

## Future Improvements
- Implement more sophisticated stochastic volatility models
- Incorporate sentiment analysis from news and social media
- Develop a real-time prediction system with automated trading signals
- Expand analysis to multiple assets for portfolio optimization

## Contributing
Contributions to improve the project are welcome. Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Acknowledgements
- [yfinance](https://github.com/ranaroussi/yfinance)
- [scikit-learn](https://scikit-learn.org/)
- [TensorFlow](https://www.tensorflow.org/)
