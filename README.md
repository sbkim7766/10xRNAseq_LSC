# 10xRNAseq_LSC
Single-Cell Transcriptomics Identifies Limbal Stem Cells and Uncovers Their Differentiation Trajectory in Limbal Basal Epithelium of Human Cornea

# Summary
The concept that the rapid-turnover human corneal epithelium is maintained by limbal stem cells (LSCs) residing in corneal limbus has been recognized for three decades. However, the molecular identity of LSCs remains elusive. Single-cell transcriptomics of 16,360 limbal basal cells identifies LSCs, estimated ~320 cells/cornea in quiescent state. 
We analyzed 10xscRNA-seq data of Limbal Basal Epithelium cells of Human Cornea, and characterized their sub-cell populations using R packages from Bioconductor.

# Data and R script
- scRNAseq_analysis_LSC.R : R script for processing the read count data from GSE153515
- regev_lab_cell_cycle_genes.txt: Gene list for cell cyle status analysis using Seurat
- 10x scRNA-seq data: GSE153515 (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE153515)

# R packages mainly used in this analysis
- Seurat: https://satijalab.org/seurat/
- Monocle: http://cole-trapnell-lab.github.io/monocle-release/
- SCENIC: https://github.com/aertslab/SCENIC


