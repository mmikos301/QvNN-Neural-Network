# QvNN-Neural-Network

Research project focused on the implementation and testing of advanced neural network architectures (LSTM, CNN, Attention) utilizing hypercomplex algebra (HypercomplexKeras). The analysis is conducted on financial time-series data from AAPL (Apple Inc.).

Project Structure
Environment Setup: Configuration of libraries (TensorFlow, Keras, HypercomplexKeras) and ensuring computational determinism.

Data Preparation: Loading time-series data, missing values analysis, stationarity tests (ADF), and autocorrelation tests (Ljung-Box).

Function Definitions: Utility tools for model construction and evaluation.

Core Experiments (Exp1-Exp6): Performance comparison of various network configurations with hypercomplex heads.

Stability Tests: Verification of model result reproducibility.

Reporting: Visualization of results and metrics (MAE, RMSE, R2).

Data Methodology
The project utilizes log-returns of stock prices and a set of technical indicators:

RSI (Relative Strength Index)

MACD (Moving Average Convergence Divergence)

ATR (Average True Range)

ROC (Rate of Change)

The analysis covers two variants of feature sets: FEATS_4 (basic prices) and FEATS_8 (extended with technical indicators).

Tech Stack
Language: Python 3.x

Deep Learning: TensorFlow, Keras

Hypercomplex Algebra: HypercomplexKeras

Data Analysis: Pandas, NumPy, Scikit-learn, Statsmodels

Visualization: Matplotlib, Seaborn

Usage
Clone the repository:

Bash
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
Open Kod_do_pracy_inz_FINAL.ipynb in Google Colab or a local Jupyter Notebook environment.

Ensure the dataset aapl_us_2025.csv is available (update the path in section 2.1).
