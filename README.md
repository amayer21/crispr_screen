Pipeline for the analysis of genome-wide CRISPR screen

The CRISPR screen pipeline imports reads from a crispr screen experiment,
extracts the sgRNA sequences, aligns them to the library, counts the occurences
of each guide in each sample and generates a table with read-count and count-per-million 
for each sgRNA.

This pipeline depends on CGAT scripts and pipelines (https://github.com/CGATOxford/cgat and https://github.com/CGATOxford/CGATPipelines)
