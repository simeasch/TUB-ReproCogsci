# TUB-ReproCogsci

# Created by
- Creator: Simeas Scheurer cloned and modifed from the scripts from Sein Jeung
- Institution: TU Berlin, Digital Tools for Reproducible Research Seminar

# Contributed by
- Contributor: Sein Jeung

# Description
This repository contains scripts for analyzing and processing data from the publicly shared dataset from the Digital Tools for Reproducible Research seminar at TU Berlin. It contains scripts restructuring and processing a publicly shared data set for training purpose. The focus of these scripts is to demonstrate how to effectively use shared platforms, work collaboratively, and create reproducible research. 

  # Script 1: gaits_01_import.py
   What it does: Loads force data for left and right feet from     text files, filters and saves it and visualizes the vertical    ground reaction force for both feet.
  Output: Saves the processed data and a plot of the total        force data.

  # Script 2: gaits_02_extract_features.py
  What it does: Detects rising and falling edges in the force     data, identifies local minima as final contact points, and      calculates stride times for both feet.
  Output: Saves stride times and visualizes edges and final       contact points.

  # Script 3: gait_03_summary.py
  What it does: Loads stride time data, calculates the average    stride times for control and patient groups, and visualizes     the results in a scatter plot.
  Output: Displays and saves a plot comparing average stride      times between the groups.

# Dataset belonging to the Scripts
The dataset used for the analysis is shared as part of the seminar and contains data on gait analysis, sensor readings, and experimental results.

# Data source:
- (https://physionet.org/content/gaitpdb/1.0.0/)
The dataset contains data from gait analysis experiments, including time-series measurements of forces from different body parts during walking. It includes data for multiple participants, both healthy controls and patients with various conditions, and is used for analyzing gait patterns.

For this project, I used the Ga (Gait) group from the dataset.

# How to Run the Scripts

1. Clone the repository:
    clone (https://github.com/simeasch/TUB-ReproCogsci)
2. Install required dependencies:
   Ensure you have the necessary Python packages installed:
4. Modify file paths:
Update file paths in the scripts to reflect your local setup for data files and output directories.
5. Run the scripts:
   Execute the main analysis script using Python
6. Check Results:
Results, including figures and output files, will be saved in the folders "Results" and "Figures" 
