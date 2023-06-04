# Weighted-Network-Embedding

This repository contains a collection of Python notebooks reproducing the synthetic and real data examples from the JASA paper *Spectral embedding of weighted graphs*. If you use this code in your own experiments, please cite the following publication:

Gallagher, I., Jones, A., Bertiger, A. Priebe, C. & Rubin-Delanchy, P. (2021). Spectral embedding of weighted graphs. *Journal of the American Statistical Association*.

The algorithms described in these notebooks use the <a href="https://github.com/iggallagher/Spectral-Embedding">Spectral-Embedding</a> package, which includes many other spectral embedding techniques.

###

### Flight Network Analysis.ipynb

Code used in Section 3 (Applications). The Python notebook provides the weighted adjacency spectral embedding for the airport flight network data using the matrix of flight counts, the matrix of square root flight counts, and the matrix of flight presence data. This reproduces the plot in Figure 3.

The notebook uses data from <a href="https://zenodo.org/record/5815448#.Y1KVlS8w1pS">Zenodo</a>. The airport metadata is included in this repository but details for the flights in each month of 2019 need to be downloaded separately.

###
