# 🦟 Modeling Malaria Dynamics in Sudan: Bridging the Gaps

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Data Source](https://img.shields.io/badge/Data-WHO%20%26%20World%20Bank-green.svg)](https://data.who.int/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Overview
This repository contains a data-driven analysis to validate the **Research Gaps** addressed in my PhD thesis. The study focuses on Sudan, utilizing real-world epidemiological and climatic data to justify a new **9-equation compartmental model** that integrates larval dynamics and social awareness.

---

## 🔍 Identified Research Gaps & Evidence

### 1. Biological Lag & Larval Stage ($L_v$)
**The Gap:** Most traditional models neglect the aquatic development phase of mosquitoes, assuming instantaneous transmission after rainfall.
**Empirical Evidence:** * Analysis of **World Bank Precipitation Data** vs. **WHO Incidence Data** for Sudan reveals a consistent **2-month time lag**.
* Rainfall peaks in **August**, while the Malaria epidemic peaks in **October**.
* **Impact:** This justifies the inclusion of the Larval compartment ($\dot{L}_v$) in our model to capture the maturation delay.



### 2. Social Awareness & Behavioral Adaptation ($A_h$)
**The Gap:** Existing models often overlook how human behavior changes in response to disease prevalence (The "Awareness Factor").
**Empirical Evidence:** * Comparing **ITN (Insecticide-Treated Nets) Distribution** with **Actual Incidence Rates** shows a clear divergence.
* Despite increased intervention coverage, incidence rates remain high, indicating that "provision of tools" $\neq$ "effective prevention" without behavioral change.
* **Impact:** This supports the integration of **Social Awareness ($A_h$)** and **Precautionary Behavior ($P_h$)** variables.



---

## 📊 Data Integration & Methodology
The analysis was performed using **Python** in a **Kaggle** environment, pulling live data from:
* **WHO Global Health Observatory:** For annual malaria incidence in Sudan.
* **World Bank Climate Portal:** For historical rainfall and temperature patterns.

## 🚀 Repository Structure
* `notebooks/`: Contains the Jupyter/Kaggle notebooks with the data-fitting code.
* `data/`: Processed datasets from WHO and World Bank.
* `results/`: High-resolution plots and validation metrics.

## 🎓 Author
**[Gehad Alneel Abdall]** PhD Candidate - Mathematical Epidemiology  
*Focusing on the intersection of Climate Change, Human Behavior, and Vector-Borne Diseases.*

---
*Note: This repository is part of a PhD research project. All models and findings are subject to peer-review publication.*
