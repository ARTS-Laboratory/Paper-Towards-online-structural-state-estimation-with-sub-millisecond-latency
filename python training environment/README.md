## Python training environment for Real Time-deployable LSTMs.

DROPBEAR data is saved in `data_6_with_FFT.json`. `train_lstm_v13.py` trains LSTM models across a range of sampling rates, units, and number of cells. All models are saved to /model_saves. Plots of model predictions are saved to /plots, and `.npy` files with model predictions are saved to /prediction_results.

### Dependencies

Tensorflow 2.5.0\
Numpy 1.19.5\
onnxruntime 1.11.0
