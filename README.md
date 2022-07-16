# Feature Selection using Discriminative Analysis

Feature selection is a dimensionality reduction technique that can choose small set of features, eliminating unnecessary ones, for better learning performance. In this paper, we utilized our proposed discriminative analysis method for feature selection and tested its efficacy in supervised and unsupervised learning environment.

## Authors

1. Md Imrul Kaish (UTRGV)
2. Dr. Rahman (UTRGV)

## Table of Contents

* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Key-Findings">Key Findings</a>
* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Problem-Statement">Problem Statement</a>
* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Dataset">Dataset</a>
* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Summary-of-Results">Summary of Results</a>
* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Publications">Publications</a>
* <a href="https://github.com/Imrul2322/feature-selection-using-discriminative-analysis#Repo-structure">Repo Structure</a>
## Key Findings

Using proposed discriminative analysis algorithm, DNA, we can rank features in a dataset and perform feature selection. Using only 1% features, we obtained similar prediction accuracy with shorter convergence time in supervised and unsupervised learning settings. 

## Problem Statement

Dimensionality reduction methods transform data in lower dimension so that most of the variances in the data are preserved in first few components. Principal Component Analysis (PCA) is a great method to find lower dimensional structure which can be used to find important features in a dataset but it is possible in one dataset only. Discriminative analysis is capable of finding target data (first dataset) variances with respect to background data (2nd dataset), extracting important features in between two datasets. Proposed algorithm, DNA performs better than other discriminative analysis methods (e.g. Contrastive PCA) to perform feature selection in multiple datasets. 

## Dataset

1. Cifar-10 object image dataset.

## Summary of Results

![alt text](https://github.com/Imrul2322/Feature-Selection-using-Discriminative-Analysis/blob/main/assets/cifar%2010%202%20class%2025.png)

Figure 1: Classification of CIFAR10 dataset labels using 25 features (accuracy 83.64%) instead of 3072 features (accuracy 85.10%).

![alt text](https://github.com/Imrul2322/Feature-Selection-using-Discriminative-Analysis/blob/main/assets/MNIST%20data%202%20class%2025.png)

Figure 2: Classification of MNIST dataset labels using 25 features (accuracy 97.72%) instead of 784 features (accuracy 99.91%).

![alt text](https://github.com/Imrul2322/Feature-Selection-using-Discriminative-Analysis/blob/main/assets/classification%20MNIST.png)

Figure 3: Classification Performance curve for MNIST dataset

For detail explanation of results, see <a href="https://github.com/Imrul2322/Feature-Selection-using-Discriminative-Analysis/blob/main/FSDA_results.ipynb">here</a>.


## Publications

1. https://drive.google.com/file/d/1H4f0pV0XagwUZRvgVyg052k7WgB0imcP/view?usp=sharing

## Repo structure

```bash
│   Feature_selection_using_Discriminative_Analysis_results.ipynb
│   FSDA_results.ipynb
│   README.md
│   Visualizing_higher_dimensional_data_on_CIFAR_10.ipynb
│   Visualizing_higher_dimensional_data_on_MNIST.ipynb
│
├───algorithms
│       Contrastive PCA.m
│       DNA.m
│
└───assets
        cifar 10 2 class 25.png
        cifar 10 2 class all.png
        classification MNIST.png
        MNIST data 2 class 25.png
        MNIST data 2 class all.png
        table feature selection in supervised.png
```
