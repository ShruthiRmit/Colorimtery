# Colorimetric Analysis using Computer Vision

## Overview
This project presents a computer vision-based pipeline for automated analysis of colorimetric assays from paper-based microfluidic devices. The goal is to replace manual interpretation with a consistent, data-driven approach for estimating analyte concentration.

The system detects circular test spots, extracts color features across multiple color spaces, and maps them to concentration values using statistical modeling.

---

## Problem Statement
Traditional colorimetric analysis relies on manual observation or expensive laboratory equipment, leading to:
- Subjective interpretation
- Inconsistent results
- Limited scalability in low-resource settings

This project aims to develop a low-cost, automated, and reliable alternative using image processing and data analysis.

---

## Methodology

### 1. Image Preprocessing
- Input images are normalized and enhanced
- Noise reduction and smoothing applied

### 2. Spot Detection
- Circular regions (assay spots) detected using image processing techniques
- Contours and geometric filtering used for accurate localization

### 3. Feature Extraction
Color features are extracted from multiple color spaces:
- RGB
- HSV
- LAB
- XYZ

This ensures robustness to lighting variations and improves feature representation.

### 4. Quantitative Analysis
- Extracted features are mapped to concentration values
- Regression models used for prediction
- Statistical validation performed (R², correlation analysis)

---

## Tech Stack
- Python
- OpenCV
- NumPy
- scikit-learn
- Matplotlib / Seaborn

---

## Results
- Accurate detection of colorimetric spots
- Strong correlation between extracted features and concentration values
- Improved consistency compared to manual estimation

---

## Key Insights
- Multi-color space analysis significantly improves robustness
- Lighting variations can impact results if not normalized
- Feature engineering plays a critical role in prediction accuracy

---

## Applications
- Point-of-care diagnostics
- Low-cost biochemical testing
- Environmental monitoring

---

1. Install dependencies:
