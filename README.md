# 🧬 Skin Microbiome Analysis

[![Last Commit](https://img.shields.io/github/last-commit/barah123/Skin_microbiome.svg)](https://github.com/barah123/Skin_microbiome)
[![Repo Size](https://img.shields.io/github/repo-size/barah123/Skin_microbiome.svg)](https://github.com/barah123/Skin_microbiome)
[![License](https://img.shields.io/github/license/barah123/Skin_microbiome.svg)](LICENSE)
[![Language](https://img.shields.io/github/languages/top/barah123/Skin_microbiome.svg)](https://github.com/barah123/Skin_microbiome)
[![Stars](https://img.shields.io/github/stars/barah123/Skin_microbiome.svg?style=social)](https://github.com/barah123/Skin_microbiome/stargazers)

---

This project analyzes skin microbiome composition and diversity using amplicon sequencing data. The analysis was performed in R using Google Colab, with datasets accessed from a cloud bucket ( AWS S3). The goal is to explore microbial community structure, diversity metrics, and taxonomic abundance.

## 📂 Project Overview

- **Notebook**: `Skin_microbiome.ipynb`
- **Author**: Philip Yamoah Appiah
- **Institution**: George Washington University – MS Health Data Science
- **Tools**: Python, Pandas, Seaborn, QIIME2-style preprocessing, AWS S3 (data source)

## 🧪 Key Analyses

- ✅ Taxonomic profiling at phylum/genus levels  
- ✅ Alpha diversity (Shannon, Simpson indices)  
- ✅ Beta diversity (Bray-Curtis distance, PCoA plots)  
- ✅ Visualization of taxa abundance (bar plots, heatmaps)  
- ✅ Sample clustering and dendrograms  

## 💻 Technologies Used

- `Python 3.x`
- `Google Colab`
- `Pandas`, `Seaborn`, `Matplotlib`, `Scikit-bio`
- AWS S3 (data access)
- Optional tools: `QIIME2`, `phyloseq` (if data originated from other pipelines)

## 📈 Sample Visualizations

Plots included:
- Diversity boxplots
- PCoA ordination
- Heatmaps of dominant genera

## 📁 How to Use

1. Open `Skin_microbiome.ipynb` in Google Colab.
2. If accessing external data, make sure the correct S3 bucket or URL is specified.
3. Run cells in sequence.
4. Modify parameters (e.g., taxonomic level, distance method) as needed.

## 🔒 License

This project is for academic demonstration and analysis purposes.

## ✉️ Contact

For questions or collaboration, please contact:  
**Philip Yamoah Appiah**  
📧 [pyappiah561@gmail.com  

