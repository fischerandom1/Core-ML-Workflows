# 🚀 Robust ML Framework: Predictive Maintenance & Agricultural Diagnostics

This repository demonstrates a systematic, end-to-end approach to the **Machine Learning lifecycle**, bridging traditional ML algorithms with advanced AI pipelining techniques.

The projects focus on **high-stakes domains**—industrial maintenance, consumer pricing, and agricultural pathology—where **data imbalance, robustness, and model generalization** are critical.

---

## 📂 Project Portfolio

### 1️⃣ Plant Pathology: Foliar Disease Predictive Analysis

**Domain:** Agricultural AI / Computer Vision

**Context:**
Based on my technical research paper (included in this repository), this project explores supervised learning methods to classify apple leaf diseases:

* Rust
* Scab
* Multiple Disease

**Highlights:**

* Implemented directional edge detection techniques
* Applied image preprocessing to reduce noise
* Improved multi-class classification performance
* Designed experimental evaluation aligned with academic research standards

---

### 2️⃣ Machine Failure Classification (Predictive Maintenance)

**Problem Statement:**
Identify potential equipment failure in a factory environment where a single breakdown costs thousands of dollars.

**Challenge:**
Extreme class imbalance (~3.4% failure rate)

**Data Strategy:**

* Implemented **SMOTEENN (SMOTE + Edited Nearest Neighbors)**
* Clarified decision boundaries
* Reduced noise while balancing classes

**Modeling Insight:**

* Prioritized **Recall over Accuracy**
* Minimized false negatives to prevent undetected failures
* Reduced downtime and opportunity costs

---

### 3️⃣ PC Price Regression Analysis

**Objective:**
High-precision market price estimation for custom PC builds.

**Performance Metrics:**

* $R^2$: **1.00**
* Test MAE: **15.71**
* Outperformed dummy baseline by **98%+**

**Feature Engineering:**

* Implemented `RobustScaler`
* Built custom preprocessing pipelines
* Handled extreme outliers ($6,000–$8,000 builds)
* Structured reusable transformation workflows

---

## 🛠️ Advanced Methodology

### 🔒 Clean Pipeline Architecture

All transformations are implemented within **Scikit-Learn Pipelines** to ensure production-grade integrity.

**Leakage Prevention**

* SMOTE nested within cross-validation folds
* Prevents validation data contamination

**Robust Preprocessing**

* Automated missing data handling
* Robust scaling for high-variance technical specs
* Structured and reproducible transformations

---

## 📊 Performance Diagnostics

### 📈 Learning Curve Analysis

* Evaluated Bias-Variance Tradeoff
* Diagnosed underfitting vs. overfitting
* Identified whether improvements required:

  * More data (variance issue)
  * Increased model complexity (bias issue)

### 🔍 Error Analysis

* Investigated extreme values (outliers)
* Examined model decision behavior
* Ensured transparency in performance limitations

---

## 🧠 Technical Stack & Skills

**Languages**

* Python

**Core Libraries**

* Scikit-Learn
* Imbalanced-Learn
* Pandas
* NumPy
* Seaborn
* Matplotlib

**Techniques**

* SMOTEENN
* Feature Engineering
* HalvingGridSearchCV
* Hyperparameter Optimization
* Regularization (L1 / L2)

**Research Skills**

* Technical Writing
* Academic Literature Review
* Experimental Design
* Model Evaluation Frameworks

---

## 📄 Documentation

* **Technical Paper:** `technical paper -yuwei.doc`

  * Details full methodology for the Foliar Disease study
* **Notebooks:**

  * Comprehensive EDA
  * Feature importance analysis
  * Learning curve diagnostics
  * Final model evaluations

---
* Or a **visually enhanced GitHub README with badges and structure polish**
