# amor-TiO2-water
Data and NN models for simulating amorphous TiO2 - water interfaces

This repository contains the training data and input files needed to train a DNN interatomic potential for amorphous TiO2/water interfaces. The DNN model was constructed using the Deep Potential (DP) method, as implemented in the DeepMD-kit code. Energy and forces in the data were computed with the SCAN functional implemented in the CP2K package. For more information of the methodology used to build the DNN training data, please see the reference cited at the end of this document.

Within this repository you will find:

raw: The raw data used to train the DP model; \\
train: The DeepMD-kit input files; \\
DP_models: The frozen DNN graphs that can be used to run DP molecular dynamics. \\

If you use this training data, please read and cite:
Zhutian Ding and Annabella Selloni (2023) To be submitted.
