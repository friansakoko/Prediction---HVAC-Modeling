This code is a full pipeline for loading a trained neural network model (a GRU-LSTM hybrid with quantization noise) and applying it to a new dataset for prediction. It begins by importing necessary libraries like TensorFlow, scikit-learn, Pandas, and others, including custom functions like quantization_noise. It then loads the pretrained model quantization_gru_lstm_model, loads the new input dataset, selects 12 predictor features, and standardizes them using StandardScaler.

![image](https://github.com/user-attachments/assets/8fbb3251-2508-40be-a93c-627f22cb0e58)
