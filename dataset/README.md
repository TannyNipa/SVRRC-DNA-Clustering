# Datasets
This repository provides genomic benchmark datasets used for evaluating clustering performance in DNA sequence analysis.

---

## Dataset Groups

### 1. CGRcluster Datasets (Included in this Repository)

This repository contains **13 genomic datasets** adapted from the CGRcluster framework.
These datasets are provided for **reproducibility and direct experimentation**.

Each dataset includes:

* Sequence data in `.fas` format
* Ground truth labels in `_GT.tsv` format

#### Dataset List

1. Cypriniformes
2. Cyprinoidei
3. Cyprinidae
4. Cyprininae
5. Astrovirus (unbalanced)
6. Astrovirus (balanced)
7. Dengue Virus
8. HCV
9. HIV
10. Insects
11. Protists
12. Actinopterygii
13. Neopterygii

---

### 2. iDeLUCS / DeLUCS Datasets (External)

In addition to the datasets included here, the study also utilizes **15 real genomic datasets** from the iDeLUCS and DeLUCS frameworks.

Due to size constraints, these datasets are **not included in this repository** and can be accessed from:

* iDeLUCS: https://github.com/Kari-Genomics-Lab/iDeLUCS
* DeLUCS: https://github.com/Kari-Genomics-Lab/DeLUCS

---

## Data Format

* `.fas` — DNA sequences
* `_GT.tsv` — Ground truth cluster labels

---

## Reproducibility

The datasets included in this repository can be directly used to reproduce the clustering experiments described in the paper.

For full-scale evaluation, users are encouraged to combine these datasets with the external iDeLUCS/DeLUCS datasets.

---

## Notes

* All datasets are used for benchmarking unsupervised clustering performance.
* Ground truth labels are provided strictly for evaluation purposes.
* Preprocessing steps follow the methodology described in the paper.
* Synthetic datasets used for pre-training are generated separately and are not included here.

---

## Source
* CGRcluster: https://github.com/millanp95/CGRcluster
* iDeLUCS: https://github.com/Kari-Genomics-Lab/iDeLUCS
* DeLUCS: https://github.com/Kari-Genomics-Lab/DeLUCS
