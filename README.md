# ofi-trial-task
Order Flow Imbalance Feature Construction Task
# OFI Feature Construction – Trial Task

## Author
Sushmitha Katherine Jayaraj

## Overview
This project implements the following Order Flow Imbalance (OFI) features:
- ✅ Best-Level OFI
- ✅ Multi-Level OFI (normalized)
- ✅ Integrated OFI (via PCA)

> Note: Cross-Asset OFI was not included as the dataset only contains a single symbol (AAPL).

## Files
- `ofi_feature_construction.ipynb`: Code to compute all OFI features
- `ofi_features.csv`: Final OFI values for each 1-minute timestamp
- `conceptual_answers.pdf`: LaTeX answers to the theory questions

## How to Run
1. Open the Colab notebook
2. Upload `first_25000_rows.csv` when prompted
3. Run all cells to generate and export OFI features

