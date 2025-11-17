# Histomonas Turkeys Microbiome Analysis - R Bookdown Project

This repository contains the complete R analysis code for the Histomonas trial microbiome study in turkeys, compiled as an R Bookdown document for easy sharing and reproducibility.

**📖 View the compiled bookdown**: [https://3d-omics.github.io/ANMI024_Histomonas_Turkeys_Macro_and_Micro/](https://3d-omics.github.io/ANMI024_Histomonas_Turkeys_Macro_and_Micro/) 

## Project Overview

This project analyzes Histomonas presence and its effects on the turkey microbiome using metagenomic sequencing data. The analysis includes both macro-samples (bulk digesta) and micro-samples (laser microdissected tissue sections) to understand spatial and temporal patterns of microbial communities in response to Histomonas infection and vaccination.

## Repository Structure

This repository contains the complete R analysis code for the Histomonas trial microbiome study. The analysis is organized into chapters covering:

- **Data Preparation** (Chapters 01A, 01Ba-01Cc, 02): 
  - **01A**: MAG catalogue preparation
  - **01Ba-01Cc**: Micro-sample metadata, counts, and sequencing statistics
  - **01Ca-01Cc**: Macro-sample metadata, counts, and sequencing statistics
  - **02**: Metabolomics data preparation
- **MAG Catalogue** (Chapter 03): Overview and visualization of the metagenome-assembled genome catalogue
- **Analysis Chapters** (Chapters 04A-04H): Comprehensive analyses including:
  - **04A**: Histomonas presence analysis
  - **04B**: Sequencing statistics
  - **04C**: Bacterial load analysis
  - **04D**: Alpha diversity analysis
  - **04E**: Beta diversity - macro samples
  - **04F**: Beta diversity - micro samples
  - **04G**: Beta diversity - macro vs micro comparison
  - **04H**: Spatial analysis - micro samples
- **Data Export** (Chapter 05A): Export data for Microbetag 
- **Package Versions** (Chapter 06A): R package versions used in the analysis

The compiled HTML bookdown document provides a complete view of all analyses with code, plots, and interpretations.

## Data Files

The repository includes processed data files (`.Rdata`) used in the analyses:

- **`data/micro/sample_metadata.Rdata`**: Micro-sample metadata
- **`data/micro/counts.Rdata`**: Micro-sample read counts, genome counts, and alpha diversity
- **`data/micro/seq_stats.Rdata`**: Micro-sample sequencing statistics
- **`data/macro/sample_metadata.Rdata`**: Macro-sample metadata
- **`data/macro/counts.Rdata`**: Macro-sample read counts, genome counts, and alpha diversity
- **`data/macro/seq_stats.Rdata`**: Macro-sample sequencing statistics
- **`data/MAG_catalogue/data.Rdata`**: MAG catalogue information including phylogenetic trees, taxonomic data, and functional annotations
- **`data/data_colors.Rdata`**: Color schemes and plotting themes used throughout the analyses
- **`data/Afekta_Histomonas_Metabolites/metabolites_data.Rdata`**: Metabolomics data for different sample types (HN, HM, MN, MM)


## Contact

For questions about the analysis or data access, please contact:
- Amalia Bogri: amalia.bogri@sund.ku.dk
- Antton Alberdi: antton.alberdi@sund.ku.dk
- Jorge Langa: jorge.langa@sund.ku.dk

## Citation

If you use this code in your research, please cite the repository:

Bogri, A., Langa, J., & Alberdi, A. (2024). Histomonas Turkeys Microbiome Analysis. GitHub repository. https://github.com/3d-omics/ANMI024_Histomonas_Turkeys_Macro_and_Micro

