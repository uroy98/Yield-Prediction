# Yield-Prediction
This repository contains the following:

1. Dataset: This folder has the **ARID** training dataset, the testing dataset and the drug molecules testing dataset. The drug molecules were tested at first using our **REACT** model and then they were experimentally validated in the laboratory.
2. The file **ModelsComparison.ipynb** has all the models tried and compared against our REACT model.
3. The file **ReactionYieldPredictionModel.ipynb** has the skeleton code that can be used to test our REACT model on any test data related to micellar catalysis.
4. The file **encoder_model.h5** is the autoencoder model which can be used to derive the latent representations of the input data.
5. The file **best_model.pkl** is the model which predicts the reaction yield of the micellar catalysis reactions.
