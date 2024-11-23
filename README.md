# Anomaly Detection with Autoencoders

This lab is part of a series, and I'm focusing on learning about unsupervised learning and anomaly detection using resources and code provided by the Facilitator.

## The Problem:

How do we detect anomalies when labeled data is unavailable or incomplete?

## The Solution: Autoencoders (AEs)
In this lab, we shift to unsupervised learning by using autoencoders, a type of neural network. Autoencoders can:

- Learn patterns in data without requiring labels.
- Capture non-linear relationships for better anomaly detection.

Although the KDD99 dataset has labels, we will not use them for training the model. Instead, we’ll use the labels to:

- Evaluate how well our model detects anomalies.
- Analyze if anomalies are grouped meaningfully in the latent space based on their type.

## Learning Objectives
By completing this lab, I aim to:

- Understand how autoencoders work for unsupervised learning.
- Learn to use Keras for building and training autoencoder models.
- Analyze model performance using evaluation metrics and latent space visualizations.