# Protein-secondary-structure-prediction

**This repository contains a PyTorch implementation of an FCN for predicting protein secondary structures.**

* **Data:** Utilizes protein sequences, PSSM profiles, and labels from the provided datasets.
* **Model:** A 1-d convolutional network with multiple layers, batch normalization, and dropout.
* **Training:** Trained with Adam optimizer and CrossEntropyLoss, with hyperparameter tuning using the Ax library.
* **Results:** Achieved  on 83% acuracy validation set and second position on the competition.

