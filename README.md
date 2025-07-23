# SignalLake
SignalLake is a real‑time equity‑forecasting lake‑house pipeline built in Python. It streams 1‑minute market bars from Alpaca, upserts them into PostgreSQL, enriches each tick with technical indicators, and powers an ensemble of LSTM, ARIMA, and XGBoost models to deliver rolling next‑bar predictions.
