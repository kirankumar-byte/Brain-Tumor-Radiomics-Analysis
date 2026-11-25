# Brain Tumor Radiomics Analysis

<p align="left">
  <img src="https://img.shields.io/badge/Language-Python-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Medical%20Imaging-PyRadiomics-green" />
  <img src="https://img.shields.io/badge/Image%20Processing-SimpleITK-orange" />
  <img src="https://img.shields.io/badge/Data%20Analysis-Pandas-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/Numerical%20Computing-NumPy-013243?logo=numpy" />
  <img src="https://img.shields.io/badge/Statistics-SciPy-8CAAE6?logo=scipy" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--learn-F7931E?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Visualization-Matplotlib-11557C" />
  <img src="https://img.shields.io/badge/Visualization-Seaborn-4C72B0" />
  <img src="https://img.shields.io/badge/Environment-Jupyter-F37626?logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white" />
</p>

# Comparative Radiomic Analysis of Primary Brain Tumors and Brain Metastases Using MRI

## 📌 Project Overview

This project investigates the radiomic characteristics of primary brain tumors and brain metastases using Magnetic Resonance Imaging (MRI).

The study applies computational image analysis and radiomics techniques to extract quantitative features from MRI images and investigate differences between the two tumor groups.

Using Python and PyRadiomics, the project explores image preprocessing, radiomic feature extraction, statistical analysis, and machine learning approaches to identify potentially discriminative imaging features.

## 🎯 Objectives

- Analyze MRI data from primary brain tumors and brain metastases.
- Extract quantitative radiomic features from MRI images and segmentation masks.
- Investigate differences in radiomic feature distributions between tumor groups.
- Identify statistically significant features using statistical testing.
- Explore patterns in radiomic data through visualization and exploratory analysis.
- Investigate the application of machine learning for tumor classification.

## 🔬 Methodology

The project follows a computational radiomics workflow:

1. **Dataset Preparation** – Organizing MRI images, segmentation masks, and associated labels.
2. **Image Preprocessing** – Preparing images and masks for radiomic analysis.
3. **Radiomic Feature Extraction** – Extracting quantitative imaging features using PyRadiomics.
4. **Feature Matrix Preparation** – Organizing extracted features into a structured dataset.
5. **Statistical Analysis** – Comparing radiomic features between primary and metastatic tumor groups.
6. **Data Visualization** – Exploring feature distributions and identifying patterns.
7. **Machine Learning** – Exploring classification approaches using selected radiomic features.

*The methodology will be updated as the original analysis scripts are recovered and organized.*

## 📊 Statistical Analysis

An independent two-sample Welch's t-test was implemented to compare radiomic feature values between primary and metastatic tumor groups.

The analysis includes:

- Feature-wise statistical testing.
- Identification of features with p-values below 0.05.
- Ranking features based on statistical significance.
- Kernel Density Estimation (KDE) plots to visualize feature distributions.

Multiple-testing correction and other statistical considerations will be documented alongside the final analysis.

## 🛠️ Technologies & Tools

| Category | Tools |
|---|---|
| Programming | Python |
| Medical Image Analysis | PyRadiomics, SimpleITK |
| Data Processing | Pandas, NumPy |
| Statistical Analysis | SciPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook, Google Colab |

## 📁 Repository Structure

```text
Brain-Tumor-Radiomics-Analysis/
│
├── README.md
│
├── notebooks/
│   └── Statistical_Analysis.ipynb
│
├── scripts/
│   └── statistical_analysis.py
│
├── results/
│   └── figures/
│
├── docs/
│   ├── methodology.md
│   └── dataset_description.md
│
└── requirements.txt
```

*The repository structure will evolve as the original project scripts and outputs are recovered.*

## 📈 Research Significance

Radiomics enables the conversion of medical images into quantitative features that can be analyzed computationally.

Comparing radiomic characteristics of primary brain tumors and brain metastases may help investigate imaging patterns associated with different tumor origins and support the development of computational approaches for tumor characterization.

## ⚠️ Data Availability

The MRI images and segmentation masks used in this research are not included in this repository.

Dataset information, references, and relevant usage restrictions will be documented separately.

## 👨‍💻 Author

**P. Kiran Kumar**

M.Sc. Bioinformatics  
Central University of Punjab

- GitHub: https://github.com/kirankumar-byte
- LinkedIn: https://www.linkedin.com/in/kiran17052002/

## 📄 Disclaimer

This repository documents an academic research project in computational radiomics and bioinformatics. The analyses are intended for research and educational purposes and are not intended for clinical diagnosis or treatment decisions.
