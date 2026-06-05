# Optimising public waste bin locations considering cost and service coverage: A case study in Bucaramanga, Colombia

This repository contains the complete replication package, computational datasets, and source code for the paper titled: *"Optimising public waste bin locations considering cost and service coverage: A case study in Bucaramanga, Colombia"*.

## Repository Structure

The project repository is structured systematically to facilitate full computational reproducibility across all 17 analysed communes.

├── 01_Coordinates/          # Spatial coordinates of the currently installed waste receptacles

├── 02_Distance_Generation/  # Python scripts used to generate the network nodes and distance matrices for each commune

├── 03_Distance_Matrices/    # Generated distance outputs, serving as the primary input parameters for the optimisation model

├── 04_Mathematical_Model/   # Mixed-Integer Linear Programming (MILP) optimization source code

└── 05_Scenario_Outputs/     # Model execution outputs, granularly segmented by commune and evaluation scenario
