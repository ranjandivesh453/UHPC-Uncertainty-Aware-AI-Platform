# UHPC Uncertainty-Aware AI Platform

**ANN-ASO-Based Compressive Strength Prediction and Reliable Mix Design Optimization**

---

## Developer

**Dr. Divesh Ranjan Kumar**  
Postdoctoral Researcher  
Department of Civil Engineering  
**Chulalongkorn University**  
Bangkok, Thailand

---

# Overview

The **UHPC Uncertainty-Aware AI Platform** is a standalone Windows application developed in MATLAB for predicting the compressive strength of Ultra-High-Performance Concrete (UHPC) and performing reliability-based inverse mix design optimization.

The software integrates the optimized **Artificial Neural Network–Atom Search Optimization (ANN-ASO)** model with uncertainty quantification, reliability assessment, and practical engineering decision-support tools. It enables rapid compressive strength prediction, batch evaluation, and inverse mix design while ensuring that all predictions remain within the experimentally validated domain.

> **Research Use Only:** This software has been developed exclusively for academic and research purposes.

---

# Main Features

- Single UHPC compressive strength prediction
- Batch prediction using Excel (.xlsx) files
- Reliability-based inverse mix design optimization
- 95% prediction intervals
- Ensemble disagreement analysis
- Applicability-domain assessment
- Decision confidence evaluation
- Material-efficiency indicators
- Multiple robust optimization strategies

---

# Modules

## 1. Single Prediction

Predict compressive strength from user-defined UHPC mixture proportions.

## 2. Batch Prediction

Predict compressive strength for multiple UHPC mixtures using Excel files.

## 3. Reliable Mix Design Optimization

Generate optimum UHPC mixtures for a target compressive strength using multiple optimization strategies.

---

# Input Variables

Water (W), Silica Fume (SF), GGBS, Cement (C), Superplasticizer (SP), Coarse Aggregate (CA), Fine Aggregate (FA), Curing Temperature (T), Curing Age (A), Steel Fiber (StF), and Polypropylene Fiber (PPF).

---

# Supported Input Range

| Variable | Min | Max |
|-----------|----:|----:|
| Water |148.00|158.00|
| SF |0.00|133.20|
| GGBS |0.00|370.00|
| Cement |281.20|740.00|
| SP |8.88|9.00|
| CA |1055.71|1102.01|
| FA |497.59|519.41|
| Temperature |28|120|
| Age |1|56|
| Steel Fiber |0|78|
| Polypropylene Fiber |0|78|

**Target Compressive Strength:** **25.32–169.57 MPa**

All predictions and optimization searches are automatically constrained within these validated limits.

---

# Installation

1. Run **UHPC_Uncertainty_Aware_Installer.exe**.
2. Install MATLAB Runtime if prompted.
3. Launch the application.
4. MATLAB is **not required**.

---

# How to Use

### Single Prediction
- Enter all input variables.
- Click **Predict**.
- Review the predicted strength and uncertainty information.

### Batch Prediction
- Import an Excel (.xlsx) file.
- Click **Predict**.
- Export the results.

### Mix Design Optimization
- Select the optimization mode.
- Enter the target compressive strength.
- Click **Optimize**.
- Review the ranked optimum mixtures.

---

# Outputs

- Predicted compressive strength
- 95% prediction interval
- Decision confidence
- Applicability-domain score
- Total binder
- Water-to-binder ratio
- SCM replacement ratio
- Aggregate-to-binder ratio
- Total fiber
- Robust binder efficiency
- Robust cement efficiency
- Material-efficiency score

---

# Excel Format

Required column names:

```
W
SF
GGBS
C
SP
CA
FA
T
A
StF
PPF
```

---

# Disclaimer

This software is intended **solely for academic and research purposes**.

The AI models were developed using experimentally validated UHPC data. Predictions outside the supported input ranges are intentionally restricted to avoid extrapolation beyond the validated domain.

The software is intended to support researchers and engineers and should not replace laboratory testing or professional engineering judgment.

---

# Citation

Please cite the associated journal paper if this software is used in your research.

---

# License

Copyright © 2026

**Dr. Divesh Ranjan Kumar**  
Department of Civil Engineering  
**Chulalongkorn University**

This software is distributed **for research and educational purposes only**.

Commercial use without permission is prohibited.

---

# Contact

**Dr. Divesh Ranjan Kumar**  
Department of Civil Engineering  
Chulalongkorn University  
Bangkok, Thailand

For questions, bug reports, or research collaboration, please contact the developer.
