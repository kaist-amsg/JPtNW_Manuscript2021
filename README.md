# JPtNW_Manuscript2021
This repository contains supporting information for the submitted manuscript, "Auto-bifunctional Mechanism of Jagged Pt Nanowire for Hydrogen Evolution Reaction via end-to-end Simulation"

## Machine learning data set
The DFT data set is in JPtNW_Manuscript2021/Training_Set/Data.json. It contains a list of converged structure and calculated H adsorption enregy. The Gibbs free energy temperature correction used is 0.226 eV.

## ACSF parameters
The parameters of the optimized ACSF model is in JPtNW_Manuscript2021/ACSF. It contains training input file ("train.in"), trained neural network parameters ("H.10tw-10tw.ann", and "Pt.13tw-13tw-13tw.ann") and hyperparameters ("H.fingerprint.stp", "Pt.fingerprint.stp"). To use this model, remove hydrogen atoms, and substitute binding site atom to hydrogen.

## DFT structure for building BEP relations
JPtNW_Manuscript2021/BEPCalc contains CONTCAR for initial and transition state used to form the BEP relations in supplementary section 3. V and H indicates Volmer and Heyrovsky reaction respectively. 
