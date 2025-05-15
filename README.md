# Autonomous Drone Firefighting Simulation 

> 📝 this is my Thesis project for my Bachelor in Cognitive Science and Artificial Intelligence at Tilburg University

## Overview

This repository contains all research materials, code, and documentation for my thesis project on autonomous drone firefighting simulations. The project explores various pathfinding algorithms and their effectiveness in firefighting scenarios using agent-based modeling with the Mesa framework.

## Repository Structure
```text
📁 Project Root 
├── 📁 code # early beginnings, just included for nostalgic purposes (has no function)
├── 📁 simulation │
├── 📁 __pycache__ │
├── 📁 icons # contains icons for the visualisation
│├── 📄 simulation_analysis.ipynb # notebook to analyse simulation metrics
│├── 📄 mesa_first_sim.ipynb # main simulation notebook
│ ├── 📁 comparativeAnalysis
│ │ ├── 📁 ABC 
│ │ ├── 📁 a_star 
│ │ ├── 📁 ACO
│ │ ├── 📁 plane 
│ │ ├── 📁 hybrid 
├── 📄 requirements.txt 
└── 📄 README.md
``` 

## Code Information

- I used the  "Better Comments" VS Code extension for enhanced comment readability with color-coded annotations. I recommend using it to understand the incode comments better.
- Key algorithms implemented:
  - A* pathfinding
  - Artificial Bee Colony (ABC) optimization
  - Ant Colony Optimization (ACO)
  - Risk asseesment of Fire Areas
  - Comparative analysis of different approaches

## System Requirements

To run the simulation:

1. Install all dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

2. Ensure sufficient storage space:
   Comparative analysis with many iterations can generate large datasets
   Recommended: 5GB+ free disk space for extensive simulations (1000 steps for each approach took approximately 5GB: only collecting the Model_data)
   --> for a deeper data analysis storing the Agent_data can be insightful (it takes up much more storage)
         
3. I used python 3.11. For 3.12 some packages ran into issues - might be solved by now

## Research Focus

This project examines:
    Autonomous drone coordination for wildfire suppression
    Comparative performance of different pathfinding algorithms
    Resource optimization in emergency response scenarios
    Environmental impact analysis of firefighting strategies

## Usage Notes

    The mesa_first_sim.ipynb notebook contains the primary simulation implementation
    Comparative analysis folders contain performance metrics for each algorithm
    Progress Tracker documents the development timeline and key milestones i made along the way

## Acknowledgments

Special thanks to:
- [Mesa](https://mesa.readthedocs.io/latest/)
- My academic supervisor: [Dr. Travis J. Wiltshire](https://scholar.google.com/citations?user=JFjMvx0AAAAJ&hl=en&oi=ao)

