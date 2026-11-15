# Data-Cleaning-and-Basic-Analysis-SWEYNEX-
# Data Cleaning and Basic Analysis

## 1. Introduction

Data cleaning and basic analysis are important steps in bioinformatics. Biological data collected from databases may contain unwanted spaces, formatting errors, or missing information. Cleaning helps improve data quality and makes analysis more accurate.

This project focuses on cleaning and analysing a biological nucleotide sequence using Python.

## 2. Aim

To perform data cleaning and basic statistical analysis of a biological nucleotide sequence using Python.

## 3. Objectives

- To collect a biological sequence from a public database.
- To remove unwanted spaces and formatting.
- To convert sequence data into a consistent format.
- To calculate nucleotide composition.
- To calculate GC percentage.
- To summarize and visualize the results.

## 4. Dataset Information

- **Database:** NCBI
- **Organism:** Homo sapiens
- **Gene:** TP53
- **Accession Number:** NM_000546.6
- **Data Type:** Nucleotide sequence
- **Format:** FASTA

**Dataset URL:** https://www.ncbi.nlm.nih.gov/nuccore/NM_000546.6

## 5. Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- NCBI database

## 6. Methodology

1. Retrieve the TP53 nucleotide sequence from NCBI.
2. Read the FASTA sequence.
3. Remove the FASTA header and unwanted spaces.
4. Convert all sequence characters to uppercase.
5. Validate the nucleotide characters.
6. Count the nucleotides.
7. Calculate GC percentage.
8. Display the results using a table and graph.

## 7. Statistical Analysis

The following values are calculated:

- Total sequence length
- Number of A nucleotides
- Number of C nucleotides
- Number of G nucleotides
- Number of T nucleotides
- GC percentage

**GC Percentage Formula:**

GC% = [(G + C) / (A + T + G + C)] × 100

The sequence is analysed in the nucleotide representation supplied by NCBI.

## 8. Expected Output

The analysis produces:

- Cleaned nucleotide sequence
- Nucleotide count summary
- Total sequence length
- GC percentage
- Nucleotide composition graph

## 9. Conclusion

This project demonstrates the importance of data cleaning and basic statistical analysis in bioinformatics. Python makes it easier to process biological sequences, calculate nucleotide composition, and visualize results. These techniques are useful for understanding biological data and preparing it for further analysis.

## 10. References

1. NCBI Nucleotide Database – https://www.ncbi.nlm.nih.gov/nuccore/NM_000546.6
2. Python Documentation – https://docs.python.org/3/
3. Pandas Documentation – https://pandas.pydata.org/docs/
4. Matplotlib Documentation – https://matplotlib.org/stable/
