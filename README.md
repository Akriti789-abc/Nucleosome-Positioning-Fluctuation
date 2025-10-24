# Content for README.md

# Nucleosome-Positioning-Fluctuation

## Project Overview
This project investigates how nucleosome positioning fluctuates around circadian clock genes in *Arabidopsis thaliana*. Using MNase-seq data, we analyze the occupancy patterns of nucleosomes around key circadian genes such as LHY, providing insights into chromatin dynamics and temporal gene regulation.

## Data
- Gene coordinates: LHY, and other circadian clock genes in Arabidopsis thaliana.
- Nucleosome positioning data: MNase-seq processed datasets (read frequency, fragment coordinates).

## Analysis
- Filter nucleosome fragments ±1kb around target genes.
- Compute nucleosome occupancy vectors.
- Visualize nucleosome positioning fluctuations around circadian clock genes.

## Purpose
Understanding nucleosome positioning dynamics helps explain temporal regulation of gene expression and provides insights into circadian chromatin remodeling mechanisms.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- pybedtools
- cython

## Usage
1. Clone the repository.
2. Upload your gene coordinates and MNase-seq nucleosome files into the `data/` folder.
3. Run the Jupyter/Colab notebook to generate nucleosome occupancy plots and analyze fluctuations.
"""
