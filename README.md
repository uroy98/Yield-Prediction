# Yield-Prediction
This repository contains the an autoencoder model which has been used to derive latent representations of the input data (chemical reactions) to predict the reaction yield of amide coupling under micellar catalysis reactions. It has the following folders:

1. **Dataset**: This folder has the **ARID** training dataset, the testing dataset and the drug molecules testing dataset. The drug molecules were tested at first using our **REACT** model and then they were experimentally validated in the laboratory.
2. The file **ModelsComparison.ipynb** has all the models tried and compared against our REACT model.
3. The file **ReactionYieldPredictionModel.ipynb** has -
   1. the autoencoder model which can be used to derive the latent representations of the input data.
   2. the skeleton code that can be used to test our REACT model on any test data related to micellar catalysis.
   3. the models tried and compared against our REACT model.

The paper published using this dataset can be found at ACS Catalysis 2025 in this link - https://pubs.acs.org/doi/abs/10.1021/acscatal.5c03190  
