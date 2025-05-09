# Capstone
Multi-Omics-Driven Diagnostic and Predictive Modeling for Lung Cancer Management
# Multi-Omics-Driven Diagnostic and Predictive Modeling for Lung Cancer Management

This capstone project applies deep learning and machine learning methods to Lung Adenocarcinoma (LUAD) multi-omics data, focusing on unsupervised clustering, subtype discovery, and survival prediction.

## Overview

Despite medical advances, lung cancer remains the leading cause of cancer-related deaths worldwide. This project explores how multi-omics integration and advanced models like SubtypeGAN and DeepSurv can uncover meaningful biological patterns and improve risk prediction in LUAD.

## Goals

- Identify LUAD patient subtypes using unsupervised learning  
- Predict survival outcomes using deep learning models  
- Evaluate model performance with silhouette score and concordance index  
- Visualize expression patterns and survival curves  
- Provide insights into feature importance for clinical interpretation  

## Dataset

Data was sourced from the MLOmics Benchmark and includes:

- mRNA Expression  
- miRNA Expression  
- DNA Methylation  
- Copy Number Variation (CNV)  
- Survival Labels  

## Key Methods

- Clustering: KMeans, Spectral, Hierarchical, SubtypeGAN  
- Survival Analysis: Cox Proportional Hazards, DeepSurv  
- Visualization: PCA, t-SNE, Kaplan-Meier, Heatmaps  
- Feature Importance: Neural weights and survival relevance  

## Results Summary

| Method                  | Score Type         | Result     |
|-------------------------|--------------------|------------|
| SubtypeGAN              | Silhouette Score   | 0.5025     |
| DeepSurv                | Concordance Index  | 0.6083     |
| Classical Cox           | Concordance Index  | 0.527      |
| Spectral Clustering     | Silhouette Score   | 0.3584     |
| Hierarchical Clustering | Silhouette Score   | 0.3615     |

## Repository Structure

A_Aghaloyan_Capstone.ipynb – main notebook  
figures/ – visualizations  
README.md – project documentation  

## License

This project is part of an academic capstone submission. All data and code are for educational and research purposes only.