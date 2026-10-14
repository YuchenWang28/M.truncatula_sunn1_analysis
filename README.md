# M.truncatula_sunn1_analysis

Codes used for the transcriptomics analysis of the sunn-1 mutant in the A17 background grown under different nitrogen (N) and CO2 conditions.

This repository contains the analysis workflow and supporting data used to investigate transcriptomic responses, differential expression, co-expression networks, and gene regulatory mechanisms associated with the sunn-1 mutant in Medicago truncatula.

## Overview

The project is organized as a series of R Markdown analysis documents, each covering a major step in the workflow:

- Physiological measurements and experimental metadata
- Differential expression analysis
- Weighted gene co-expression network analysis (WGCNA)
- Gene regulatory network (GRN) inference
- Consensus network and subnetwork analysis
- Network visualization
- Gene expression plotting
- DAP-seq validation
- NAC47 overexpression analysis

## Repository structure

- `Section01_Physiology.Rmd` — physiological data and experimental context
- `Section02_DEGAnalysis.Rmd` — differential expression analysis
- `Section03_WGCNAnalysis.Rmd` — weighted gene co-expression network analysis
- `Section04_GRNanalysis_ConsensusNetwork.Rmd` — consensus GRN analysis
- `Section04_GRNanalysis_Subnetworks.Rmd` — subnetwork-based GRN analysis
- `Section05_GRNvisualization.Rmd` — visualization of regulatory relationships
- `Section06_PlotGeneExpression.rmd` — plotting and figure generation for gene expression
- `Section07_DAPseqValidation.Rmd` — validation of candidate regulators using DAP-seq data
- `Section08_NAC47Overexpression.rmd` — analysis of NAC47 overexpression experiments
- `MT_genome/` — genome and annotation resources used in the project
- `data_for_publication/` — processed and publication-related datasets
- `LICENSE` — project license

## Data resources

This repository contains both analysis scripts and data files used for publication and downstream interpretation, including:

- raw and processed counts
- metadata tables
- phenotype summaries
- network edge tables
- annotation files for transcription factors and other regulatory genes

The files under `data_for_publication/` are especially relevant for reproducing or extending the publication analyses.

## Reproducibility

This project is mainly implemented in R using `.Rmd` analysis notebooks. To reproduce the analyses:

1. Clone the repository.
2. Open the relevant R Markdown file in RStudio or another R environment.
3. Install the required R packages.
4. Run the code in order to reproduce figures, networks, and statistical outputs.

## Requirements

Typical dependencies include:

- R
- RStudio (recommended)
- Bioconductor and CRAN packages used for transcriptomics and network analysis
- Genome annotation files and dataset inputs stored in the repository or referenced by the scripts

## License

This project is licensed under the terms described in the `LICENSE` file.

## Notes

This repository is intended for transcriptomics and regulatory network analysis of the sunn-1 mutant in Medicago truncatula under varying nitrogen and CO2 conditions. It is designed to support reproducible analysis and figure generation for the corresponding study.
