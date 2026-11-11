# Citrus_CO_detection_and_design_breeding
This repository contains all analytical workflows and scripts for crossover identification and design breeding in a Citrus F1 biparental hybrid population. The code supports comprehensive genomic and breeding analyses across three distinct research dimensions, enabling reproducible reconstruction of recombination landscapes, breeding simulations , and foreground and background selection. By integrating these dimensions, the workflows bridge the gap between genetic mapping and practical breeding, providing a transparent and reproducible framework to precisely dissect.
## Core Analytical Workflows
The repository is organized into three key modules, corresponding to the main research directions of the project:
### 1. Crossover identification in citrus
Analytical workflows for crossover identification using Citrus NGS data, including SNP filtering and screening, parental haplotype reconstruction, and two approaches for scanning and determining crossover events at both SNP and bin levels.
### 2. Breeding simulation, calculation of parental-origin combination similarity(POCS), and determination of optimal population size
Integrated pipelines for breeding simulation and investigating the optimal population size of Citrus hybrid populations based on POCS and simulated progeny. Key steps include: simulated population data generation, POCS calculation, and gradient simulation to determine the non-redundant core progeny set.
### 3. Foreground–Background Joint Genomic Selection (FBJGS)
Integrated pipelines for foreground and background selection utilizing genomic prediction results and crossover (CO) results. Key steps include: datafication and clustering of recombination background information, calculation of composite trait indices and trait weights, and the selection of superior and elimination of inferior progeny.
## Notes
All scripts are modular, well-documented, and designed for reproducible large-scale genomic analysis. They support the core conclusions regarding recombination landscapes, optimal population size selection for Citrus breeding, and the breeding practice of foreground and background selection.
