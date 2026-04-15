# Systematic Benchmarking of AlphaFold2 and OpenFold3 on Protein–Peptide Complexes

This repository contains the dataset, evaluation scripts, and benchmarking results for AF2 and OpenFold3 predictions of a protein–peptide complexes.

## Overview

Protein–peptide interactions are critical mediators of biological processes, yet structural prediction for these complexes remains challenging. This study provides a comprehensive comparative evaluation of AF2 and OpenFold3 using a curated, non-redundant dataset of 976 protein–peptide complexes. The study specifically evaluates performance under CAPRI peptide criteria, partitioning results into disordered (IDR) and structured (Non-IDR) peptide subsets to understand how conformational flexibility impacts prediction accuracy.

Predictions can be accessed: https://zenodo.org/records/19598102

## Repository Structure

```text
├── data/               # Curated dataset of protein-peptide complexes including sequences
├── scripts/            # Python notebooks for DockQ evaluation and score calculation
├── results/            # Prediction outputs and confidence scores
