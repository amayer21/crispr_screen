Pipeline for analysis of genome-wide CRISPR screen

The CRISPR screen pipeline imports reads from crispr screen experiment,
extracts the sgRNA sequences, aligns them to the library, counts the occurences
of each guide in each sample and generates a table with read-count and count-per-million 
for each sgRNA.

This pipeline depends on CGAT script and pipelines.
