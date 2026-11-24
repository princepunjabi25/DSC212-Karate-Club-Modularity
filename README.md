# DSC212-Karate-Club-Modularity

# DSC212 Assignment: Modularity on the Karate Club Graph

Name: Prince Punjabi  
Roll No: IMS25153  
Course: DSC212 (Graph Theory Module), IISER Thiruvananthapuram

## Overview
This repository contains my Jupyter notebook for the DSC212 assignment on community detection in Zachary's Karate Club graph using recursive spectral modularity partitioning (Newman, 2006).

## Contents
- `DSC212_Karate_Club_Modularity_IMS25153_v2.ipynb`: Full code, outputs, graph visualizations after each split, metric evolution plots, and discussion.

## Summary of Results
- Iteration 1 splits the club into 2 groups (16 and 18 nodes, Q = 0.3715), matching Zachary's actual split for 33 out of 34 members (only node 8 differs).
- Using Newman's generalized modularity matrix for subgroups, recursive bisection stops after 3 splits with 4 communities (sizes 7, 9, 12, and 6) and final modularity Q = 0.3934.
- Degree, betweenness, closeness, and clustering are tracked across iterations after removing inter-community edges at each split.

## How to Run
Install `numpy`, `pandas`, `networkx`, and `matplotlib`, then open the notebook and click **Restart & Run All**.

## References
1. M. E. J. Newman (2006). Modularity and community structure in networks. PNAS, 103(23), 8577-8582.
2. W. W. Zachary (1977). An information flow model for conflict and fission in small groups. Journal of Anthropological Research, 33(4), 452-473.
