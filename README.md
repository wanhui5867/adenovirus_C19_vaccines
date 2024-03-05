# Description
This reportoire includes the analysis scripts for analysing the scRNA-seq with matched scBCR-seq data which was used in paper: "Comparative single-cell transcriptomic profile of hybrid immunity induced by adenovirus vector-based COVID-19 vaccines"

# Sequecing data:
The fastq raw files of scRNA-seq data and scBCR-seq data can be accessed in Zenodo (10.5281/zenodo.7904759)

# Analysis steps and scripts:
0.hastage.Rmd: the R script is used to preprocess the data from Cellranger, including, merge data, demultiplex of hashtag, QC, dimensionality reduction, evulation of batch effector, clustering, cell type annotation, ect.
1.Bcell.Rmd: the R script is used to analyze the B cells.
2.Tcell.Rmd: the R script is used to analyze the T cells.
3.statistic.Rmd: the R script is used for statistical analysis in the paper.
4.plot.Rmd: the R script plots some figures in the paper.
