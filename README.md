# Dried Blood Droplet Biometrics XAI

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![IEEE](https://img.shields.io/badge/Publication-IEEE-blue)
![XAI](https://img.shields.io/badge/XAI-ExplainableAI-green)

## Subject-Specific Dried Blood Droplet Morphology Analysis Using a Hybrid DenseNet201 and Random Forest Approach with XAI Interpretation

This repository presents an AI-driven framework for subject-specific dried blood droplet morphology analysis using a hybrid DenseNet201 and Random Forest architecture combined with Explainable AI (XAI) techniques.

The framework analyzes subtle blood droplet drying patterns such as:
- Outer rings
- Crack formations
- Texture distributions
- Internal drying structures

to identify subject-specific morphological signatures.

---

# Overview

A single dried blood droplet forms unique spatial patterns due to complex internal fluid dynamics during evaporation. The movement of proteins, cells, and biomolecules toward the droplet boundary creates ring-like structures and crack formations that vary between individuals.

These patterns act as biological signatures and may enable:
- subject-specific analysis
- longitudinal health monitoring
- automated blood sample interpretation
- AI-assisted biomarker discovery

Since blood droplets from different individuals often appear visually similar to the human eye, manual analysis becomes challenging.

This work proposes a hybrid deep learning framework combining:
- DenseNet201 feature extraction
- Random Forest classification
- Explainable AI interpretation

for automated subject-level blood droplet morphology analysis.

---

# Abstract

A single dried blood droplet forms a specific pattern of rings, cracks, and textures where internal fluid movement creates formations that push protein and cells toward the outer edges. Every person holds a unique biological makeup such that the resulting dried pattern acts as a personal signature.

Identifying these patterns at individual level leads to new ways of tracking patient-specific health over time. Droplets from different people look similar to the human eye, making manual sorting difficult.

We developed a hybrid model that uses a DenseNet201 backbone to extract fine details and a Random Forest model for classification, addressing subtle visual differences.

The proposed model achieved:
- Mean Accuracy: 82.5%
- Five-fold stratified cross-validation
- Dataset size: 1,710 images
- Subjects: 30 individuals

The model’s ability to distinguish between individuals was validated using:
- Intra-subject distance analysis
- Inter-subject distance analysis
- Statistical separability testing
- Gallery-query protocols
- Cumulative Match Characteristic (CMC) curves

Explainable AI techniques including SHAP and Grad-CAM demonstrated that the model focuses on:
- outer rings
- inner crack regions
- drying texture distributions

where blood chemistry strongly influences droplet formation.

The results demonstrate that dried blood droplets contain sufficient discriminative information for subject-level identification and automated blood morphology analysis.

---

# Publication

Published in IEEE WiSPNET 2026.

## Citation

R. Vijayakumar, K. S. Vuppalapati, N. N. S and R. M,

**"Subject-Specific Dried Blood Droplet Morphology Analysis Using a Hybrid DenseNet201 and Random Forest Approach with XAI Interpretation"**

2026 International Conference on Wireless Communications Signal Processing and Networking (WiSPNET)

Chennai, India, 2026.

DOI:
https://doi.org/10.1109/WiSPNET69615.2026.11489414

Publisher:
IEEE

Conference Date:
17–19 March 2026

---

# Keywords

- Dried Blood Droplets
- Biometrics
- DenseNet201
- Random Forest
- Explainable AI
- SHAP
- Grad-CAM
- Morphology Analysis
- Subject Identification
- Blood Pattern Recognition

---

# Technical Contributions

## Hybrid AI Framework
- DenseNet201-based deep feature extraction
- Random Forest classification pipeline
- Hybrid CNN + ML architecture

## Biometrics Analysis
- Subject-specific morphology recognition
- Intra-subject compactness analysis
- Inter-subject separability analysis
- Gallery-query evaluation

## Explainable AI
- SHAP interpretability
- Grad-CAM visualization
- Feature attribution analysis

---

# Dataset Information

| Property | Value |
|---|---|
| Total Images | 1710 |
| Number of Subjects | 30 |
| Validation Strategy | 5-Fold Stratified Cross Validation |

---

# Model Performance

| Metric | Value |
|---|---|
| Mean Accuracy | 82.5% |
| Subjects | 30 |
| Validation | 5-Fold Cross Validation |

---

# Biometrics Validation

The learned embeddings were validated using:

- Intra-subject distance analysis
- Inter-subject distance analysis
- Statistical separability tests
- Gallery-query protocols
- Cumulative Match Characteristic (CMC) curves

The framework demonstrated clear subject separability and effective subject-level discrimination.

---

# Explainable AI Results

SHAP and Grad-CAM visualizations revealed that the model focuses primarily on:

- Outer ring regions
- Internal crack structures
- Texture boundaries
- Drying-induced morphology

These findings align with known fluid dynamic and blood chemistry effects during droplet evaporation.

---

# Technologies Used

- Python
- PyTorch
- DenseNet201
- Random Forest
- SHAP
- Grad-CAM
- Scikit-learn
- NumPy
- Pandas
- OpenCV
- Matplotlib

---

# Workflow

1. Blood droplet image preprocessing
2. DenseNet201 feature extraction
3. Random Forest classification
4. Embedding analysis
5. Gallery-query evaluation
6. CMC curve generation
7. SHAP interpretation
8. Grad-CAM visualization

---

# Applications

- Biometrics
- Personalized healthcare
- Longitudinal patient monitoring
- Blood morphology analysis
- AI-assisted diagnostics
- Biomedical image analysis

---

# Future Scope

- Disease-specific droplet morphology analysis
- Multi-modal biomarker fusion
- Real-time droplet analysis systems
- Mobile microscopy integration
- Clinical biometrics applications
- Few-shot subject identification

---

# Authors

- Reshmma Vijayakumar
- K. S. Vuppalapati
- N. N. S
- R. M

---

# License

This repository is intended for academic and research purposes only.

---

# Acknowledgement

The authors acknowledge IEEE WiSPNET 2026 for supporting the dissemination of this research work.
