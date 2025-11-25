# A Comparative Study of Node Ranking Metrics in Directed Networks

This repository contains the source code and the report of my Master Project (done at the Department of Physics, University of Fribourg).

📄 **[Read the full report (PDF)](Mproject.pdf)**

## Project Overview

This project analyzes and compares three node ranking metrics applied to competitive directed networks:
1.  **In-degree**
2.  **PageRank**
3.  **Zermelo’s Strength** (based on the Bradley-Terry model)

The study evaluates the accuracy of these metrics against the "intrinsic strength" of nodes through numerical simulations on various synthetic network models (Random, Bradley-Terry, and Biased networks).
This work serves as a preliminary study for future analysis of real-world professional tennis (ATP) rankings.

## Repository Contents

* **`Mproject.ipynb`**: The complete Jupyter Notebook (containing the network generation, metric implementation, and correlation analysis)
* **`.pkl files`** : These files contain pre-calculated simulation results.
* **`Mproject.pdf`**: The final report containing the theory, methodology, results and discussions.

## Usage & Installation

The project is written in **Python**. Libraries needed to run the notebook: `NetworkX` (Graph generation and analysis), `SciPy` & `NumPy` (Statistical calculations), `Matplotlib` (Data visualization)

Note: The notebook is configured to automatically reload the .pkl files, to reduce computation time by avoiding the need to re-run all the simulations from scratch.



## Author & Supervision

* **Author:** Thomas REY
* **Supervisor:** Matúš MEDO
* **Date:** September/November 2025
* University of Fribourg (Switzerland), Department of Physics
