# SVRRC-DNA-Clustering

This repository accompanies the peer-reviewed article:

**Predicting the Number of Clusters in Genomic Data via Synthetic Pre-Training and Support Vector Regression-Based Ordinal Regression**

Published online in *IEEE Access* on **23 July 2026**.

**DOI:** [https://doi.org/10.1109/ACCESS.2026.3713686](https://doi.org/10.1109/ACCESS.2026.3713686)

## Overview

Estimating the correct number of clusters in genomic datasets is a challenging problem, especially when data distributions are complex (e.g., overlapping or nested clusters).
This work addresses the problem by learning patterns of data distribution and mapping them to the corresponding number of clusters.

## Contents

* **Datasets**

  * 13 CGRcluster datasets (included) with sequence data and ground truth labels
  * Selected datasets for ablation study

* **Source Code**

  * Feature extraction (k-mer representation)
  * Dimensionality reduction (PCA)
  * Cluster number prediction using SVRRC

## External Data

Additional datasets used in the study (iDeLUCS / DeLUCS) are not included due to size limitations and can be accessed from:

* https://github.com/Kari-Genomics-Lab/iDeLUCS
* https://github.com/Kari-Genomics-Lab/DeLUCS

## Purpose

This repository is intended to support reproducibility and provide reference implementations for the proposed method.
