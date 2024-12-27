# Predicting-Remaining-Useful-Life-RUL-of-Jet-Engines-Using-LSTM-Regression-on-NASA-Turbofan-Dataset

This project leverages the NASA Turbofan Jet Engine Data Set to predict the Remaining Useful Life (RUL) of jet engines. RUL is a key metric representing the time or cycles remaining before a machine requires maintenance or failure occurs. Accurate RUL predictions enable effective predictive maintenance, reducing downtime, improving safety, and optimizing operational efficiency.

## Dataset
The dataset, available on Kaggle, consists of simulated engine data under varying operational conditions. It includes time-series sensor readings and operational settings for multiple engines, each running until failure. This sequential data provides a rich foundation for training time-series models.

## Methodology
The project employs a Long Short-Term Memory (LSTM) regressor, a type of recurrent neural network (RNN) designed to handle sequential data and capture long-term dependencies. The LSTM model is trained to map sequences of sensor readings to their corresponding RUL values. Key steps include:

- Data preprocessing: Organizing and normalizing sensor data into fixed-length sequences for model training.
- Model training: Training the LSTM regressor on the processed data to minimize prediction error.
- Evaluation: Testing the model on unseen engines and analyzing performance using metrics like loss and R².

## Key Features
- Sequential data analysis: Uses LSTM to handle the temporal nature of engine sensor data.
- Predictive maintenance application: Focuses on estimating RUL to support proactive decision-making.
- Visualization: Includes plots for loss and R² metrics to track model performance during training and evaluation.

