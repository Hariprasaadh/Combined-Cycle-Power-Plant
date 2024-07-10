# Combined-Cycle-Power-Plant

This repository contains a machine learning project that predicts the net hourly electrical energy output (PE) of a Combined Cycle Power Plant using Artificial Neural Networks (ANN). The dataset is sourced from the UCI Machine Learning Repository.

Project Overview

Combined Cycle Power Plants (CCPP) are complex systems used for electricity generation, comprising gas turbines, steam turbines, and heat recovery systems. This project aims to predict the net hourly electrical energy output of such plants based on ambient temperature, ambient pressure, relative humidity, and exhaust vacuum.

Dataset

The dataset used in this project is the Combined Cycle Power Plant dataset from the UCI Machine Learning Repository. It includes 9568 data points collected from a Combined Cycle Power Plant over six years (2006-2011). The dataset contains the following features:

1. AT (Ambient Temperature in °C)
2. V (Exhaust Vacuum in cm Hg)
3. AP (Ambient Pressure in mbar)
4. RH (Relative Humidity in %)
5. PE (Net hourly electrical energy output in MW) - Target variable

Model

The model used for this project is an Artificial Neural Network (ANN) implemented using TensorFlow/Keras. The architecture consists of:

1. Input layer with 4 neurons (one for each feature)
2. Two hidden layers with ReLU activation
3. Output layer with a single neuron (predicting PE)
4. The model is compiled with the Adam optimizer and mean squared error (MSE) loss function.

Results

The model's performance is evaluated using Mean Squared Error (MSE). The result demonstrate that the ANN effectively predicts the net hourly electrical energy output with a reasonable accuracy.
