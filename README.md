# Discharge-Risk-NS
Neurosymbolic Framework for Hospital Discharge Risk Classification
# Discharge-Risk-NS 🩺

**Neurosymbolic Framework for Rule-Based Risk Flagging from Hospital Discharge Summaries**

[![Scientific Reports](https://img.shields.io/badge/Scientific%20Reports-Under%20Review-blue)](https://www.nature.com/srep/)
[![License](https://img.shields.io/github/license/sravanthivelavolu/Discharge-Risk-NS)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](requirements.txt)

## 🎯 Key Results (MIMIC-IV n=21,283)
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| TF-IDF+RF | 85.2% | 82.1% |
| Rules Only | 87.4% | 84.1% |
| **Discharge-Risk-NS** | **99.6%** | **98.9%** |

## 🚀 Quick Demo
```bash
git clone https://github.com/sravanthivelavolu/Discharge-Risk-NS.git
cd Discharge-Risk-NS
pip install -r requirements.txt
jupyter notebook notebooks/01_demonstration.ipynb
```

## 📊 Reproduce Results
- `notebooks/Discharge-Risk-NS github.ipynb` ← All your charts/tables
- MIMIC-IV: https://physionet.org/content/mimiciv/2.2/

## 📚 Citation
