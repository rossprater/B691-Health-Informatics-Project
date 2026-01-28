# B691-Health-Informatics-Project

# Machine Learning for Fraud, Waste, and Abuse Detection in Healthcare Claims

Author: Ross Prater  
Program: INFO-B 691 – Thesis/Project in Health Informatics  
Term: Spring 2026  

## Project Overview

This repository contains the code, documentation, and artifacts for a master’s-level health informatics project focused on the design and evaluation of machine learning methods for detecting potential fraud, waste, and abuse (FWA) in healthcare claims data.

The goal of this project is not to identify confirmed fraud, but to develop analytically rigorous and interpretable models that surface anomalous or high-risk utilization and billing patterns that may warrant further review. The emphasis is on methodological design, feature engineering grounded in healthcare domain knowledge, and formal evaluation under real-world constraints such as class imbalance and limited ground truth.

## Project Objectives

- Design and implement one or more ML approaches suitable for healthcare claims data  
- Engineer features reflecting utilization intensity, billing patterns, temporal behavior, and peer deviation  
- Evaluate model performance using appropriate quantitative and qualitative methods  
- Assess practical considerations including interpretability, scalability, and limitations  
- Produce a reproducible pipeline and an IMRAD-formatted academic report  

## Scope and Academic Distinction

While the topic of FWA detection overlaps with the author’s professional experience, this project is academically distinct in that it:

- Places the author in the role of model designer and evaluator, not downstream consumer  
- Emphasizes independent methodological decision-making  
- Requires formal evaluation and scholarly documentation  
- Goes beyond rule-based or deterministic approaches commonly used operationally

No proprietary or confidential data is used in this repository.  

## Data Sources

This project uses synthetic or de-identified healthcare claims datasets, such as:

- CMS public synthetic datasets  
- Other publicly available or simulated claims data suitable for research

Specific dataset details, schemas, and preprocessing steps are documented in the /data and /notebooks directories.

⚠️ Note: All datasets used comply with academic and ethical standards for privacy and data use.

## Methods

Depending on dataset characteristics and labeling constraints, methods may include:

- Unsupervised anomaly detection
- Semi-supervised learning
- Ensemble-based approaches

Models are evaluated using metrics appropriate to the problem context, such as:

- Precision / recall and related variants
- Ranking-based metrics (e.g., precision@K)
- Stability and robustness analyses
- Interpretability techniques (e.g., feature importance)

Repository Structure  
.  
├── data/               # Raw and processed datasets (or data documentation)  
├── notebooks/          # Exploratory analysis and modeling notebooks  
├── src/                # Reusable Python modules and pipelines  
├── results/            # Model outputs, metrics, and visualizations  
├── docs/               # Project documentation and figures  
├── report/             # IMRAD-formatted project report drafts  
└── README.md  

## Tools and Technologies

- Python  
- Pandas / NumPy  
- scikit-learn (and related ML libraries)  
- Jupyter Notebooks  
- Visualization libraries (e.g., matplotlib, seaborn)  
- Exact dependencies are listed in requirements.txt.

## Evaluation and Reproducibility

This project prioritizes:

- Transparent feature engineering  
- Reproducible experiments  
- Clear documentation of assumptions and limitations  
- All major modeling decisions are justified and documented to support academic review.

## Expected Outcomes

- A functional ML pipeline for FWA risk detection  
- Quantitative evaluation results with supporting visualizations  
- A comprehensive academic report suitable for graduate-level assessment  
- Critical discussion of limitations and real-world applicability  

## Disclaimer

This project is for academic and research purposes only. Outputs do not constitute fraud determinations, compliance decisions, or investigative findings.
