# JMML Transcriptomics Analysis (GSE147523)

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/)
[![pyDESeq2](https://img.shields.io/badge/Bioconductor-pyDESeq2-green.svg)](https://github.com/owkin/pyDESeq2)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a complete differential gene expression workflow for Juvenile Myelomonocytic Leukemia (JMML). Utilizing the Python implementation of DESeq2 (**pyDESeq2**), we compare the transcriptomic profiles of **19 JMML patient samples** against **3 normal pediatric controls** from NCBI GEO Dataset [GSE147523](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE147523).

---

## 📂 Project Structure
* `notebooks/`: Contains the step-by-step Jupyter Notebook detailing data cleaning, normalization, model fitting, and results extraction.
* `results/`: Contains the complete, annotated differential expression tables and key visualization plots.
* `environment.yml`: Conda environment configuration file to instantly replicate this analysis.

---

## 🛠️ Installation & Setup
To run this analysis locally, replicate the Conda environment:

```bash
# Clone the repository
git clone [https://github.com/AlexChen-3/JMML-Project.git](https://github.com/AlexChen-3/JMML-Project.git)
cd JMML-Project

# Create environment from yml
conda env create -f environment.yml
conda activate jmml_transcriptomics
