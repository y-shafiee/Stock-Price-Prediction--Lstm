# M Meta Stock Price Prediction with LSTM

> Time-series forecasting of **Meta (META)** daily stock prices using an LSTM network in TensorFlow/Keras.  


## Highlights
- Uses 40-day sliding window to predict next-day closing price.
- Model architecture: 2 × LSTM (64 units) + Dropout layers + Dense regression head.
- Data preprocessing: Min–Max scaling, sequence generation.
- Visualization of predictions vs. actual prices.
- Notebook based on original Colab workflow.

⚠️ **Important:** The original notebook uses:
- `drive.mount` (Google Colab paths) → should be replaced with relative paths (e.g., `data/META.csv`).