# Biodata Portfolio

Freelance-ready portfolio demonstrating **data science fundamentals**, **ML prototyping**, and **bioinformatics domain expertise** with emphasis on efficiency and practical workflows.

## The Problem: Predicting Drug Response

**Why it matters:** Cancer treatment often involves trial-and-error with expensive therapies that may not work for individual patients. Predicting drug response from molecular data (gene expression) before treatment could:
- Reduce patient exposure to ineffective, toxic therapies
- Lower healthcare costs by avoiding failed treatments
- Accelerate personalized medicine adoption

**The challenge:** Integrating heterogeneous clinical datasets, handling high-dimensional genomics data (14,549 genes), and building interpretable models that generalize across studies.

## What You'll See

### 1. Drug Response Prediction Pipeline (Trastuzumab)

End-to-end workflow predicting response to trastuzumab (breast cancer therapy) from gene expression:

**Data Integration** (`nbs/data acquisition.ipynb`)
- Combining 4 independent GEO datasets (291 samples total)
- Leveraging refine.bio's pre-processed 400K-sample microarray compendium
- Efficient subsetting using zarr data structures
- Matching clinical response labels to expression profiles

**Preprocessing & QC**
- Quality control checks (NaN, inf, zero-variance genes)
- Working with pre-normalized data (SCAN + quantile normalization)
- Gene filtering and feature selection via PCA

**Key Skills Demonstrated:**
- **Efficiency awareness**: Reusing validated preprocessing pipelines rather than reimplementing
- **Large-scale data handling**: Working with 400K-sample databases, subsetting intelligently
- **Bioinformatics literacy**: GEO datasets, microarray normalization, HUGO gene symbols
- **Domain knowledge**: Drug response classification, breast cancer biology
- **Data wrangling**: Multi-source integration, clinical-molecular data alignment

### 2. General Data Science Competencies

- **Data cleaning**: Handling missing values, duplicates, inconsistent formats
- **Exploratory analysis**: Distribution checks, dimensionality assessment
- **Feature engineering**: Domain-aware preprocessing (log-transform, centering, scaling)
- **Workflow documentation**: Clear notebooks tracking decisions and rationale

## Technologies

- **Python**: pandas, numpy for data manipulation
- **Bioinformatics**: GEO datasets, refine.bio, zarr/anndata formats
- **ML** (upcoming): PyTorch for classification models, scikit-learn for feature selection

## License

Apache License 2.0 
