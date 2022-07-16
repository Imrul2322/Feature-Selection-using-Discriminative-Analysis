# Feature Selection using Discriminative Analysis

Feature selection is a dimensionality reduction technique that can choose small set of features, eliminating unnecessary ones, for better learning performance. In this paper, we utilized our proposed discriminative analysis method for feature selection and tested its efficacy in supervised and unsupervised learning environment.

## Key Findings

Using proposed discriminative analysis algorithm, DNA, we can rank features in a dataset and perform feature selection. Using only 1% features, we obtained similar prediction accuracy with shorter convergence time in supervised and unsupervised learning settings. 

## Problem Statement

Dimensionality reduction methods transform data in lower dimension so that most of the variances in the data are preserved in first few components. Principal Component Analysis (PCA) is a great method to find lower dimensional structure which can be used to find important features in a dataset but it is possible in one dataset only. Discriminative analysis is capable of finding target data (first dataset) variances with respect to background data (2nd dataset), extracting important features in between two datasets. Proposed algorithm, DNA performs better than other discriminative analysis methods (e.g. Contrastive PCA) to perform feature selection in multiple datasets. 

## Dataset

1. Cifar-10 object image dataset.

## Summary of Results

![alt text](https://github.com/Imrul2322/NonNegative-Discriminative-Data-Analytics/blob/main/assets/symptoms.png)



## Publications

1. https://drive.google.com/file/d/1H4f0pV0XagwUZRvgVyg052k7WgB0imcP/view?usp=sharing
