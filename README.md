[![DOI](https://zenodo.org/badge/579992957.svg)](https://zenodo.org/badge/latestdoi/579992957)

# Computational Approaches to Opera Libretti

## Purpose of this repository
Here you can find data & code for the paper on structural properties of libretti in DraCor

## Structure of this repository
* [Data](/data)
* [Code](/code) (relies entirely on the data in the [Data](/data) folder, no external data is needed)
* [Results](/results) in the form of visualizations and tables (these files are linked in the final version of the paper)
* [Paper](giovannini_skorinkin_libretti_2023pp.pdf) draft in the PDF format

## Reproduction of the research: instruction

Run the [notebook](/code/DraCor_Opera_Analyser.ipynb) to reproduce the research. The notebook is optimised for use in Google Colab, but also works as a standalone Jupyter notebook if all the external libraries & their dependencies are installed. 

## Mapping of the figures and tables:

1. [Figure "Evolution of French drama, 1626-1889, visualised through PCA"](/results/figures/pca-french.png)
2. [Figure "Evolution of German drama, 1770-1920, visualised through PCA"](/results/figures/pca-german.png)
3. [Figure "Correlation matrix for the German corpus"](/results/figures/correlation_matrix_ger.png)
4. [Figure "Correlation matrix for the French corpus"](/results/figures/correlation_matrix_fre.png)
6. [Figure "Relative features importance according to the random forest classifier"](/results/figures/rfo_with_treshold.png)
7. [Figure "Evolution of selected features in German data: word\_count\_sp (below) and num\_of\_groups (above)"](/results/figures/sc-ger-wcsp-groups.png)
8. [Figure "Evolution of selected features in French data (I): density (above) and num\_speaker (below)."](/results/figures/sc-fre-density-speakers.png.png)
9. [Figure "Confusion matrix for a four-class classifier trained and tested on the German sample"](/results/figures/confusion_matrix_ger.png)
10. [Figure "Confusion matrix for a four-class classifier trained and tested on the French sample."](/results/figures/confusion_matrix_fre.png)
11. [Figure "Evolution of selected features in French data (II): word_count_sp and word_count_stage."](/results/figures/sc-fre-wordcounts.png)
12. [Figure "Principal Components Analysis for German and French libretti, with centroids (X)"](/results/figures/pca-libretti.png)
13. [Table 1.](/results/table1.csv)
14. [Table 2.](/results/table2.csv)
15. [Table 3.](/results/table3.csv)

## DOI

https://doi.org/10.5281/zenodo.8356601
