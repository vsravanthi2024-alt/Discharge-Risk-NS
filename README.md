# Discharge-Risk-NS
Neurosymbolic Framework for Hospital Discharge Risk Classification
# Discharge-Risk-NS 🩺

**Neurosymbolic Framework for Rule-Based Risk Flagging from Hospital Discharge Summaries**

[![Scientific Reports](https://img.shields.io/badge/Scientific%20Reports-Under%20Review-blue)](https://www.nature.com/srep/)
[![License](https://img.shields.io/github/license/sravanthivelavolu/Discharge-Risk-NS)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](requirements.txt)

## 🎯 Key Results (MIMIC-IV)
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| TF-IDF+RF | 85.2% | 82.1% |
| Rules Only | 87.4% | 84.1% |
| **Discharge-Risk-NS** | **99.6%** | **98.9%** |

## 📋 Data Structure
Discharge-Risk-NS/
├── Discharge-Risk-NS git.ipynb      # notebook
├── requirements.txt                 # Dependencies
├── README.md                       # Main page
└── DATASET_DETAILS.md              # Dataset

## 🚀 How to Run

### **1. Clone & Install**
```bash
git clone https://github.com/sravanthivelavolu/Discharge-Risk-NS.git
cd Discharge-Risk-NS
pip install -r requirements.txt
```

### **2. Run Your Notebook**
```bash
jupyter notebook "Discharge-Risk-NS git.ipynb"
```
**← Contains ALL your charts, tables, and code!**

## 📊 What You'll Get
- ✅ Top 5 High-Risk Diseases chart (Pneumonia, HF, AKI, Sepsis, COPD)
- ✅ Publication tables (99.6% accuracy)
- ✅ Model demo with eGFR/K+/Na+ rules

## 🔗 MIMIC-IV Data
https://physionet.org/content/mimic-iv-note/2.2/

## 📚 Citation
[1] Johnson, A., Pollard, T., Horng, S., Celi, L. A., & Mark, R. (2023). MIMIC-IV-Note: Deidentified free-text clinical notes (version 2.2). PhysioNet. RRID:SCR_007345. https://doi.org/10.13026/1n74-ne17
[2] Johnson, A., Bulgarelli, L., Pollard, T., Horng, S., Celi, L. A., & Mark, R. (2023). MIMIC-IV (version 2.2). PhysioNet. RRID:SCR_007345. https://doi.org/10.13026/6mm1-ek67
[3] Johnson, A.E.W., Bulgarelli, L., Shen, L. et al. MIMIC-IV, a freely accessible electronic health record dataset. Sci Data 10, 1 (2023). https://doi.org/10.1038/s41597-022-01899-x
