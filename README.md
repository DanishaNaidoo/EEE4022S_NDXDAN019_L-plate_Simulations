# EEE4022S L-Plate EMC Project 

## Project Overview
This repository contains the Altair FEKO simulation files used for the EEE4022S final year project entitled "Simulation and Characterisation of an EMC Earthing L-plate at a SANSA Science Installation." The project aimed to investigate the effectiveness of an L-plate in mitigating radiated emissions and common mode (CM) currents in a system with sensitive scientific equipment.

Two key experiments were conducted using FEKO simulations:

Experiment 1: This experiment investigated the effect of the L-plate on common mode (CM) current produced within the L-plate by a source of electromagnetic interference. Four different simulation scenarios were created to evaluate the L-plate's impact on CM current:

- No L-plate or earthing,
- No L-plate but with earthing,
- L-plate without earthing,
- L-plate with earthing.
  
Experiment 2: This experiment focused on the L-plate's physical structure and its influence on radiated emissions. Four distinct simulation scenarios were used to assess the effectiveness of the L-plate in reducing radiated emissions:

- No L-plate,
- Standard L-plate,
- Partially enclosed L-plate,
- Fully enclosed L-plate.

## Repository Contents 
1. **Main_Simulation** folder: Contains the basic FEKO simulation designed for the L-plate system
2. **CM_Current_Evaluation** folder: Contains the FEKO simulation files for the first experiment
3. **Effect_of_Geometry** folder: Contains the FEKO simulation files for the second experiment

## How to use
All FEKO simulation files are provided as .cfx files. These can be downloaded from this repository and run using Altair FEKO. 
