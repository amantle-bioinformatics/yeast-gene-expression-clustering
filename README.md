# yeast-gene-expression-clustering
A bioinformatics project analyzing gene expression in Saccharomyces cerevisiae using machine learning clustering. Using the Spellman dataset, it identifies co-expressed genes across the yeast cell cycle through K-means, hierarchical, and DBSCAN methods, revealing patterns in temporal gene regulation.
# Yeast Gene Expression Clustering Analysis

A bioinformatics data science project analyzing gene expression patterns in *Saccharomyces cerevisiae* using machine learning clustering techniques.

## Overview

This project performs clustering analysis on gene expression data from the Spellman dataset to identify co-expressed genes in yeast cell cultures. By analyzing expression patterns across different time points during the cell cycle, we aim to discover functional relationships between genes and group them into meaningful clusters based on their expression profiles.

## Dataset

**Spellman Dataset (Spellman.csv)**
- **Organism**: *Saccharomyces cerevisiae* (baker's yeast)
- **Data Type**: Gene expression measurements (log ratios)
- **Structure**: 4,381 transcripts × 23 time points
- **Context**: Cell cultures synchronized at different cell cycle points using temperature-sensitive cdc15-2 mutation
- **Size**: 609.18 kB

The dataset captures gene expression levels measured at various time points during the yeast cell cycle, providing insights into temporal gene regulation patterns.

## Objectives

1. **Data Exploration**: Analyze the structure and characteristics of the Spellman gene expression dataset
2. **Data Preprocessing**: Clean and prepare the data for clustering analysis
3. **Clustering Analysis**: Apply machine learning algorithms to identify groups of co-expressed genes
4. **Pattern Discovery**: Identify genes with similar expression profiles and potential functional relationships
5. **Visualization**: Create informative plots and visualizations to present findings
6. **Biological Interpretation**: Analyze clusters for biological significance and gene function relationships

## Methodology

- **Programming Language**: Python
- **Key Libraries**: 
  - Pandas (data manipulation)
  - NumPy (numerical computing)
  - Scikit-learn (machine learning)
  - Matplotlib/Seaborn (visualization)
  - Scipy (statistical analysis)
- **Clustering Algorithms**: K-means, Hierarchical Clustering, DBSCAN
- **Analysis Techniques**: Principal Component Analysis (PCA), correlation analysis

## Project Structure

