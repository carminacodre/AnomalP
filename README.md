# AnomalP experiments

This repository containts jupyter notebooks with code for experiments having the goal of predicting anomalies in protein sequences.

The protein amino acids represented in either SA (25 letters) or angles construct protein sequences each belonging to different proteins which in turn belong to different superfamilies. 
By training different flavours of neural networks, with focus on Autoencoders, these experiments try to determine if a protein belongs to a superfamily or not, respectively if it is not an anomaous structure with respect to a superfamily or if it is. 

### Main experiments

`AE_all` contains the experiments ran at sequence level in SA representation and angle based represetnation.

`AE_all_protein_level` contains the experiments ran at protein level in SA representation and angle based represetnation.

`Preprocessing` contains the code for preprocessing the protein sequences in various forms
 
 
 ### Additional notebooks
 
 
`AE_subset` contains an initial experiment on a subset of data used for trying different models and their capabilities

`Data_Exploration` was used for dataset statistics and initial exploration

`Results`, `Utils_Time`, `Visualization` are utilities used for computing results and metrics

`VAE` is an initial experiment with Variational Autoencoders
 