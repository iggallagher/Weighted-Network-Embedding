# Weighted-Network-Embedding

This repository contains a collection of Python notebooks reproducing the synthetic and real data examples from the JASA paper *Spectral embedding of weighted graphs*. If you use this code in your own experiments, please cite the following publication:

Gallagher, I., Jones, A., Bertiger, A. Priebe, C. & Rubin-Delanchy, P. (2023). Spectral embedding of weighted graphs. *Journal of the American Statistical Association*.

The algorithms described in these notebooks use the <a href="https://github.com/iggallagher/Spectral-Embedding">Spectral-Embedding</a> package, which includes many other spectral embedding techniques.

### Anomalous p-values SBM.ipynb

Code used in Section 3.1 (Pairwise p-value data). The Python notebook provides the weighted adjacency spectral embedding for three different represenations of a network of p-values data; 1-p-values, log p-values and threshold p-values. This reproduces the plots in Figure 1.

### Anomalous p-values SBM Chernoff Information.ipynb

Code used in Section 3.1 (Pairwise p-value data). The Python notebook provides an analysis of the Chernoff information for the different p-values representaions described in the previous notebook. This reproduces the phase diagrams in Figure 2.

### Flight Network Analysis.ipynb

Code used in Section 3.2 (Air traffic data). The Python notebook provides the weighted adjacency spectral embedding for the airport flight network data using the matrix of flight counts, the matrix of square root flight counts, and the matrix of flight presence data. This reproduces the plots in Figure 3.

The notebook uses data from <a href="https://zenodo.org/record/5815448#.Y1KVlS8w1pS">Zenodo</a>. The airport metadata is included in this repository but details for the flights in each month of 2019 need to be downloaded separately.

### Two Community Gaussian SBM.ipynb

Code used in Section 4.3 (Gaussian distributions with equal means). The Python notebook produces the weighted adjacency spectral embedding for a rank deficient two-community Gaussian stochastic block model reproducing the plot in Figure 4.
