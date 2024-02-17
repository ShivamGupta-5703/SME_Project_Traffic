# Traffic Prediction with Neural Networks
This repository contains code for predicting traffic volume using various neural network architectures including Multi-Layer Perceptron (MLP), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU). The models are trained and evaluated on historical traffic data obtained from multiple junctions.

## Dataset

The dataset used in this project is sourced from [provide data source or describe how it was collected]. It consists of historical traffic data recorded at various junctions over a specific period. Each record includes attributes such as DateTime, Number of Vehicles, and Junction ID. Prior to model training, the dataset undergoes preprocessing steps including:

- Feature engineering: Extracting relevant features such as year, month, day, hour, and day of the week from the DateTime attribute.
- Normalization: Scaling numerical features to a standard range to ensure consistent model training.
- Data splitting: Segmenting the dataset into training and testing sets to facilitate model evaluation.
