# Insulin-Gene-Mutation-Analysis
A bioinformatics pipeline using Biopython to fetch, analyze, and visualize the Human Insulin Gene (INS). Includes genomic stats, protein translation, and motif search.

# Overview
This project is a bioinformatics pipeline designed to analyze the Human Insulin Gene (INS). It fetches real-time data from the NCBI Nucleotide Database, performs genomic statistical analysis, translates DNA to Protein, and includes a Mutation Simulation Tool to predict the biological impact of genetic variations (Silent, Missense, or Nonsense mutations).

# Key Features
NCBI Integration: Automatically fetches gene data using `Biopython` (Entrez).
Genomic Stats: Calculates Nucleotide length and GC Content percentage.
Central Dogma Simulation: Translates DNA coding sequences into Amino Acid sequences.
Data Visualization: Plots the distribution of amino acids in the insulin protein.

# Tech Stack
Python 
Biopython (Sequence manipulation & Entrez)
Matplotlib (Visualization)
Collections (Data handling)

# How to Run
1.  Install dependencies:
    ```bash
    pip install biopython matplotlib
    ```
2.  Open the Jupyter Notebook (`insulin_gene_analysis.ipynb`).
3.  Run all cells to see the analysis.

