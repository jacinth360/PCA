
# PCA and DE

## Repository Overview
This repository contains an end-to-end analysis pipeline for microarray intensity data, applying Principal Component Analysis (PCA) and differential expression (DE) analysis.

The analysis covers:
- Preprocessing and scaling of normalized intensity data
- Principal Component Analysis (PCA) to explore variance structure
- Variance explained and cumulative variance visualizations
- Biplot construction of PC1 vs PC2 with sample metadata
- Differential expression filtering (padj < 0.01) on microarray probes
- Extraction of DE intensity values
- Heatmap visualization of differentially expressed probes using a color-blind-friendly palette
