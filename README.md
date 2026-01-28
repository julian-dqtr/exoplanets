# Exoplanets

This project implements a deep learning pipeline to classify and validate exoplanet candidates from the NASA Kepler mission data.

## Project Description
The goal is to distinguish between confirmed exoplanets and false positives using photometric features. This repository contains the comparative study of three neural network architectures, including a final hybrid model using attention mechanisms.

## Results
- Model 1 (MLP): 86% accuracy. Baseline Multi-Layer Perceptron.
- Model 2 (CNN): Performance limited by data scarcity on raw light curves.
- Hybrid Model (Attention + DenseNet): 91.5% accuracy and 0.979 ROC-AUC.

## Repository Structure
- notebooks/ : Contains the MLP, CNN, and the Hybrid Model.
- data/ : Kepler Object of Interest (KOI) dataset.
- report/ : Technical report detailing the methodology and results.
- .gitignore : Configuration to exclude temporary and system files.

## Technical Stack
- Python
- PyTorch
- Scikit-Learn
- Pandas
- Matplotlib / Seaborn

## Authors
- Sneha Basker (CentraleSupelec)
- Julian Dequatre (CentraleSupelec)
