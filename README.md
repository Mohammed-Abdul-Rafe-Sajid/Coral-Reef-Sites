# Coral Diversity at Reef Sites 

Predicting which coral species are present at synthetic reef sites using machine learning.

## Overview
Coral reefs host a diverse mix of species shaped by environmental conditions and geography.  
Identifying which coral species occur at different sites can reveal:
- Patterns in reef structure  
- Changes over time  
- Responses to local conditions  

This project explores **multi-label classification**, predicting the species composition at reef sites from **environmental and spatial data**.

---

##  Project Aim
- Build machine learning models to predict coral species presence/absence across reef sites  
- Handle multi-label classification where each site may contain multiple species  
- Evaluate models using **Hamming Loss** (lower is better)

---

##  Dataset
- Site-level **environmental and spatial features**  
- Binary species labels (0 = absent, 1 = present)  
- ~1,600 reef sites in the test set  


---

## Current Progress
- **Baseline model (GPT-initialized):** Achieved **1.1461 Hamming Loss**  
- **Next steps:**  
  - Feature engineering on spatial/environmental variables  
  - Test traditional ML (LogReg, RF, XGBoost, LightGBM) vs neural networks  
  - Address label imbalance and improve multi-label handling  

---

## Citation
Peter Moorhouse. *Coral Diversity at Reef Sites.* 2025.  
[Dataset Source](https://kaggle.com/competitions/coral-diversity-at-reef-sites)

---

