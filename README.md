# SVRRC-DNA-Clustering

This repository accompanies our journal submission on predicting the number of clusters in genomic data using synthetic pre-training and SVR-based ordinal regression (SVRRC).

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
